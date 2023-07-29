# Patent Image Retrieval
## Summary
The repository contains a Patent Image Retrieval, Transformer backbone, deep metric learning, and preprocessing in Python/PyTorch.

The repository is based on the paper: Kotaro Higuchi, Keiji Yanai, **Patent Image Retrieval Using Transformer-based Deep Metric Learning**, World Patent Information(WPI) 2023. [PDF(WPI)] 

## Update(Jul 21, 2023)
- This project was accepted to World Patent Information. We achieved the State-Of-The-Art(SOTA) score of mAP in patent image retrieval. [[PDF]] [[Code]](https://github.com/L4Clippers/Patent-Image-Retrieval-Transformer-DML/blob/main/20230110_ArcFace-DPat-SwinV2_v38_384RandCrop.ipynb)
- Pre-training & Fine-tuning codes
- DeepPatent link [[Project]](https://github.com/GoFigure-LANL/DeepPatent-dataset)

## Update(Feb 1, 2023)
- Initial project "Patent Image Retrieval using Cross-entropy-based Metric Learning" was released. The paper was accepted to International Workshop on Frontiers of Computer Vision(IW-FCV). We achieved to search patent image without traditional IPC or CPC. [[PDF(IW-FCV)]](https://iwfcv2023.github.io/assets/Poster/P1-6%20Patent%20Image%20Retrieval%20Using%20Cross-entropy-based%20Metric%20Learning_Kotaro%20Higuchi.pdf) [[Poster(IW-FCV)]](https://mm.cs.uec.ac.jp/yanai/report/semiconf22/230222higuchi_14_ppt.pdf)

## Citation
If you use this code, please cite the following paper:

```
@article{HiguchiWPI2023,
  author={Higuchi, Kotaro and Yanai, Keiji},
  title={Patent Image Retrieval Using Transformer-based Deep Metric Learning},
  booktitle={World Patent Information(WPI)},
  year={2023},
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
- Graphic board (worked at NVIDIA A6000*8)
- FAISS

## Instllation
### Requisites
- PyTorch Metric Learning
  **conda install -c conda-forge pytorch-metric-learning** for Ubuntu

## Dataset
- If you would like to fine-tune on an conventional dataset, you must prepare the DeepPatent dataset. [[Project]](https://github.com/GoFigure-LANL/DeepPatent-dataset)
- Same test/val/train split as the DeepPatent dataset

## Terms of use
The authors affiliated in The University of Electro-Communications(UEC) are not responsible for the reproduction, duplication, copy, sale, trade, resell or exploitation for any commercial purposes, of any portion of the images and any portion of derived the data. In no event will we be also liable for any other damages resulting from this data or any derived data.
