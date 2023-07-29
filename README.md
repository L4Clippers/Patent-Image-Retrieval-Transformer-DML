# Patent Image Retrieval
## Summary
The repository contains a Patent Image Retrieval, Transformer backbone, deep metric learning, and preprocessing in Python/PyTorch.

The repository is based on the paper: Kotaro Higuchi, Keiji Yanai, "", World Patent Information[PDF(IW-FCV)] [PDF(World Patent Information)] [Poster]

## Update(Jul. 29, 2023)
- Pre-training & Fine-tuning codes
- Downloadable dataset(deeppatent) [Link]

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
- Graphic board (worked at NVIDIA A6000 * 8)

## Dataset
If you would like to fine-tune on an conventional dataset, you must prepare the DeepPatent dataset.

## Terms of use
The authors affiliated in Japan Patent Office(JPO), and The University of Electro-Communications(UEC) are not responsible for the reproduction, duplication, copy, sale, trade, resell or exploitation for any commercial purposes, of any portion of the images and any portion of derived the data. In no event will we be also liable for any other damages resulting from this data or any derived data.
