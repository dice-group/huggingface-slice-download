Download a slice from the beginning of a huggingface dataset and save it to disk.

```
./huggingface-slice-download --path uonlp/CulturaX --name en --split train --rows-limit 10000 --save-path ~/.local/share/datasets/CulturaX/en
```

```
./slurm_run uonlp/CulturaX train 10000 ~/.local/share/datasets/CulturaX
```

```
import datasets
dataset = datasets.load_from_disk('~/.local/share/datasets/CulturaX/en')
```
