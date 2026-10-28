# X-Trainer six simulation scenes

The six X-Trainer simulation scenes are stored directly in this repository as eight numbered parts. The same archive is also available in the [v1.0.0 release](https://github.com/Dobot-Edu/xtrainer-six-scenes/releases/tag/v1.0.0).

Clone the repository and reassemble the 335 MiB archive:

```bash
git clone https://github.com/Dobot-Edu/xtrainer-six-scenes.git
cd xtrainer-six-scenes
cat xtrainer-six-scenes.tar.gz.part-* > xtrainer-six-scenes.tar.gz
echo '5ab95735539fc5d2e85268348b1b6b96a80fb609b67334654526a2dee9db0ede  xtrainer-six-scenes.tar.gz' | sha256sum -c -
```

The archive contains `assets/scenes/task1`, `task2`, `task3`, `gdcc_task1`, `gdcc_task2`, and `gdcc_task3`, along with the vendor USD assets used by the scenes. Model weights and caches are not included.

Extract the verified archive from the root of an X-Trainer project:

```bash
tar -xzf xtrainer-six-scenes.tar.gz
```

SHA-256: `5ab95735539fc5d2e85268348b1b6b96a80fb609b67334654526a2dee9db0ede`
