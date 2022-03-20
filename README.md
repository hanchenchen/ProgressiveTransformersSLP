# ProgressiveTransformersSLP - PHOENIX14T

This project forked from official source code for "Progressive Transformers for End-to-End Sign Language Production" (Ben Saunders, Necati Cihan Camgoz, Richard Bowden - ECCV 2020)

# Update
1. upload the preprocessed dataset

# ToDo:
1. upload codes for processing PHOENIX14T
2. update the pre-trained Progressive Transformer checkpoint

# Usage

Install required packages using the requirements.txt file.

`pip install -r requirements.txt`

To run, start __main__.py with arguments "train" and ".\Configs\Base.yaml":

**text to sign pose**: `python __main__.py train ./Configs/Base-T2P.yaml` 

**gloss to sign pose**: `python __main__.py train ./Configs/Base-G2P.yaml` 

# Data

The unofficial pre-processed Phoenix14T data can be downloaded from https://www.dropbox.com/sh/99u7apw2q52mzn2/AAD0JAmOQ8P4ZK-8VDXDR6xqa?dl=0 

# Reference

If you use this code in your research, please cite the following [papers](https://arxiv.org/abs/2004.14874):

```
@inproceedings{saunders2020progressive,
	title		=	{{Progressive Transformers for End-to-End Sign Language Production}},
	author		=	{Saunders, Ben and Camgoz, Necati Cihan and Bowden, Richard},
	booktitle   	=   	{Proceedings of the European Conference on Computer Vision (ECCV)},
	year		=	{2020}}

@inproceedings{saunders2020adversarial,
	title		=	{{Adversarial Training for Multi-Channel Sign Language Production}},
	author		=	{Saunders, Ben and Camgoz, Necati Cihan and Bowden, Richard},
	booktitle   	=   	{Proceedings of the British Machine Vision Conference (BMVC)},
	year		=	{2020}}

@inproceedings{saunders2021continuous,
	title		=	{{Continuous 3D Multi-Channel Sign Language Production via Progressive Transformers and Mixture Density Networks}},
	author		=	{Saunders, Ben and Camgoz, Necati Cihan and Bowden, Richard},
	booktitle   	=   	{International Journal of Computer Vision (IJCV)},
	year		=	{2021}}

```

## Acknowledgements
<sub>This work received funding from the SNSF Sinergia project 'SMILE' (CRSII2 160811), the European Union's Horizon2020 research and innovation programme under grant agreement no. 762021 'Content4All' and the EPSRC project 'ExTOL' (EP/R03298X/1). This work reflects only the authors view and the Commission is not responsible for any use that may be made of the information it contains. We would also like to thank NVIDIA Corporation for their GPU grant. </sub>
