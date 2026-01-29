# LHT-LargeBackbones
This repository contains the PyTorch implementation of extending our Label Hierarchy Transition (LHT) method to additional backbones.

## Dataset Preparation

Please refer to the repo [label-hierarchy-transition](https://github.com/renzhenwang/label-hierarchy-transition)

## Setup and Training

To train our method **LHT** on **CUB-200-2011** (e.g., Swin), one can directly run the experiment with relabeled ratio **$\mathcal R=90\%$** three times (random seeds 10, 100, 1) as follows.
```
cd cub_swin
run run_ours.sh
```