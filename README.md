Download a slice from the beginning of a huggingface dataset and save it to disk.

```
.venv/bin/python ./huggingface-slice-dataset --path uonlp/CulturaX --name en --split train --rows-limit 10000 --save-path ~/.local/share/datasets/CulturaX/en-5
```

```
./slurm_run uonlp/CulturaX train 10000 ~/.local/share/datasets/CulturaX
```
