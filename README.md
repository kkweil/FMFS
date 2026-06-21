# HyperSL-FS

Official implementation of **Efficient Foundation Model Adaptation for Few-shot Hyperspectral Image Classification**.

## Introduction

This repository provides the official implementation of **HyperSL-FS**, an efficient foundation model adaptation framework for few-shot hyperspectral image classification.

The proposed method is built upon **HyperSL**, a pretrained spectral foundation model for hyperspectral image interpretation. By leveraging the transferable spectral representations learned from large-scale hyperspectral pretraining, HyperSL-FS can achieve effective adaptation under sample-limited conditions, especially when only a few labeled samples are available for each class.

This work focuses on:

* Few-shot hyperspectral image classification
* Cross-scene hyperspectral image classification
* Efficient adaptation of pretrained hyperspectral foundation models
* Limited-label learning for hyperspectral remote sensing

## Download

### Pretrained Weights

The pretrained HyperSL weights can be downloaded from the official HyperSL release:

* Baidu Netdisk: https://pan.baidu.com/s/11uuzhKs-dtFExlnph1IYTQ
  Extraction Code: `27mh`

* HuggingFace: https://huggingface.co/WeilKon/HyperSL/tree/main

After downloading, please place the pretrained weights under:

```bash
pretrained/
```

### Training Dataset

The HyperSL pretraining dataset can be downloaded from:

* Baidu Netdisk: https://pan.baidu.com/s/1YP_OMkAf4LytjyowQBq9JQ
  Extraction Code: `tw7g`

* HuggingFace: https://huggingface.co/WeilKon/HyperSL/tree/main

For downstream few-shot classification experiments, please prepare the corresponding hyperspectral classification datasets following the instructions in the code.

## Citation

If you find this repository useful, please consider citing our work:

```bibtex
@article{hypersl_fs,
  title={Efficient Foundation Model Adaptation for Few-shot Hyperspectral Image Classification},
  author={Kong, Weili and others},
  journal={},
  year={2026}
}
```

This repository is built upon HyperSL. Please also cite:

```bibtex
@ARTICLE{10981753,
  author={Kong, Weili and Liu, Baisen and Bi, Xiaojun and Yu, Changdong and Li, Xinyao and Chen, Yushi},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  title={HyperSL: A Spectral Foundation Model for Hyperspectral Image Interpretation},
  year={2025},
  volume={63},
  number={5513119},
  pages={1-19},
  doi={10.1109/TGRS.2025.3566205}
}
```

## Acknowledgement

This work is developed based on the pretrained hyperspectral foundation model **HyperSL**.
