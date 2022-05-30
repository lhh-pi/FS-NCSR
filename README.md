# FS-NCSR
Official PyTorch implementation of "FS-NCSR: Increasing Diversity of the Super-Resolution Space via Frequency Separation and Noise-Conditioned Normalizing Flow"  [[paper](https://arxiv.org/abs/2204.09679)]

CVPRW 2022, Runner-up at NTIRE 2022 Learning the Super Resolution Space Challenge

This repository is heavily based on [SRFlow](https://github.com/andreas128/SRFlow) and [NCSR](https://github.com/younggeun-kim/NCSR)

<p align="center">
	<img src="figs/fig1.png" alt="photo not available" width="90%" height="90%">
</p>

## Setup
### Preparing data
```.bash
cd code
python prepare_data.py /path/to/img_dir
```
### RRDB pretrained weights
Download pretrained weights of RRDB and move them in 'pretrained_weights' folder

[RRDB_DF2K_4X.pth](https://drive.google.com/file/d/1597Gblp_lsPEsyBuD8YrqelSMFbauObS/view?usp=sharing)\
[RRDB_DF2K_8X.pth](https://drive.google.com/file/d/1nyggiyxTZLAEOAjV6_x8UEmdoMdI5ulp/view?usp=sharing)

These pretrained weights are originally from [SRFlow](https://github.com/andreas128/SRFlow)
