# Patent Image Retrieval
## Summary
The repository contains a Patent Image Retrieval, Transformer backbone, deep metric learning, and preprocessing in Python/PyTorch.

The repository is based on the paper: Kotaro Higuchi, Keiji Yanai, **Patent Image Retrieval Using Transformer-based Deep Metric Learning**, World Patent Information(WPI) 2023. [PDF(WPI)] [[PDF(IW-FCV)]](https://iwfcv2023.github.io/assets/Poster/P1-6%20Patent%20Image%20Retrieval%20Using%20Cross-entropy-based%20Metric%20Learning_Kotaro%20Higuchi.pdf) [[Poster(IW-FCV)]](https://mm.cs.uec.ac.jp/yanai/report/semiconf22/230222higuchi_14_ppt.pdf)

## Update(Jul. 29, 2023)
- Pre-training & Fine-tuning codes
- Downloadable dataset(deeppatent) [[Project]](https://github.com/GoFigure-LANL/DeepPatent-dataset)

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
- Python
- Pytorch Metric Learning
- CUDA
- CuDNN
- Graphic board (worked at NVIDIA A6000*8)

## Dataset
If you would like to fine-tune on an conventional dataset, you must prepare the DeepPatent dataset.

## Terms of use
The authors affiliated in The University of Electro-Communications(UEC) are not responsible for the reproduction, duplication, copy, sale, trade, resell or exploitation for any commercial purposes, of any portion of the images and any portion of derived the data. In no event will we be also liable for any other damages resulting from this data or any derived data.
