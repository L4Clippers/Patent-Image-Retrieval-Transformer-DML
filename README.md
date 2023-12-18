# Patent Image Retrieval
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/patent-image-retrieval-using-transformer/image-retrieval-on-deeppatent)](https://paperswithcode.com/sota/image-retrieval-on-deeppatent?p=patent-image-retrieval-using-transformer)

## Summary
The repository contains a Patent Image Retrieval, Transformer backbone, deep metric learning, and preprocessing in Python/PyTorch.

The repository is based on the paper: Kotaro Higuchi, Keiji Yanai, **Patent Image Retrieval Using Transformer-based Deep Metric Learning**, World Patent Information(WPI) 2023. [[Abstract(WPI)]](https://www.sciencedirect.com/science/article/abs/pii/S0172219023000479) 

## Update(Dec 17, 2023)
- Thank you for your contact and interest. We have published the model for evaluation at the following [[link]](https://www.dropbox.com/scl/fi/wnnubycc5o7jhpbnk1t9z/swin-arcface-test_epoch19.pth?rlkey=xyti9tfph50t4y6y16fcbbqtp&dl=0). We hope you will find it useful.

## Update(Jul 21, 2023)
- This project was accepted to World Patent Information. We achieved the State-Of-The-Art(SOTA) score of mAP in patent image retrieval. [[Abstract(WPI)]](https://www.sciencedirect.com/science/article/abs/pii/S0172219023000479)  [[Code]](https://github.com/L4Clippers/Patent-Image-Retrieval-Transformer-DML/blob/main/20230110_ArcFace-DPat-SwinV2_v38_384RandCrop.ipynb)
- Pre-training & Fine-tuning codes
- DeepPatent link [[Project]](https://github.com/GoFigure-LANL/DeepPatent-dataset)

## Update(Feb 1, 2023)
- Initial project "Patent Image Retrieval using Cross-entropy-based Metric Learning" was released. The paper was accepted to International Workshop on Frontiers of Computer Vision(IW-FCV). We achieved to search patent image without traditional IPC or CPC. [[PDF(IW-FCV)]](https://iwfcv2023.github.io/assets/Poster/P1-6%20Patent%20Image%20Retrieval%20Using%20Cross-entropy-based%20Metric%20Learning_Kotaro%20Higuchi.pdf) 

## Citation
If you use this code, please cite the following paper:

```
@article{HiguchiWPI2023,
  title = {Patent image retrieval using transformer-based deep metric learning},
  journal = {World Patent Information},
  volume = {74},
  pages = {102217},
  year = {2023},
  doi = {https://doi.org/10.1016/j.wpi.2023.102217},
  author = {Kotaro Higuchi and Keiji Yanai},
}

@inproceedings{HiguchiIWFCV2023,
  author={Higuchi, Kotaro and Honbu, Yuma and Yanai, Keiji},
  title={Patent Image Retrieval Using Cross-entropy-based Metric Learning},
  article={International Workshop on Frontiers of Computer Vision(IW-FCV)},
  year={2023},
}
```

## Requirements
- PyTorch > 1.6.0
- torchvision > 0.7.0
- Pytorch Metric Learning
- CUDA
- CuDNN
- FAISS
- OpenCV
- Graphic board (worked at NVIDIA A6000*8)

## Instllation
### Requisites
- PyTorch Metric Learning
  -  ``conda install -c conda-forge pytorch-metric-learning``
- FAISS
  -  ``conda install -c conda-forge faiss-gpu``
### Run
- Jupyter Notebook
  - Run this Notebook file on Ubuntu 22.04 LTS

## Note
- This repository contains the legendary version of the ArcFace implementation with the Python interface. [Code](https://github.com/ronghuaiyang/arcface-pytorch/blob/master/models/metrics.py)
- We tested this notebook with Python3, on Ubuntu.
- Patlist is from DeepPatent dataset. It teaches the path to the substantial dataset.

## Dataset
- If you would like to fine-tune on an conventional dataset, you must prepare the DeepPatent dataset. [[Project]](https://github.com/GoFigure-LANL/DeepPatent-dataset)
- Same test/val/train split as the DeepPatent dataset

## Models
- Our pre-trained models are available at this following [link][(https://www.dropbox.com/scl/fi/wnnubycc5o7jhpbnk1t9z/swin-arcface-test_epoch19.pth?rlkey=xyti9tfph50t4y6y16fcbbqtp&dl=0).

## Terms of use
The authors affiliated in The University of Electro-Communications(UEC) are not responsible for the reproduction, duplication, copy, sale, trade, resell or exploitation for any commercial purposes, of any portion of the images and any portion of derived the data. In no event will we be also liable for any other damages resulting from this data or any derived data.
