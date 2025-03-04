# Multi-Scale Sensing and Multi-Dimensional Feature Enhancement for Surface Defect Detection of Hot-rolled Steel Strip
## Introduction
Here is the paper we publish "Multi-Scale Sensing and Multi-Dimensional Feature Enhancement for Surface Defect Detection of Hot-rolled steel strip". 

Please refer to the paper for more information. This repo is based on PyTorch.

## :open_file_folder: Dataset and Weight
GC10-DET [Google Drive](https://drive.google.com/drive/folders/1il-h-ijcIpq4LUIcwOvegy7BqeBCabf9?usp=drive_link)

NEU-DET  [Google Drive](https://drive.google.com/drive/folders/1A0UFpEhH_Wa98OvncSeX5IXnuCNOyF-J?usp=drive_link)

MDGC10-DET [Google Drive](https://drive.google.com/drive/folders/15kABnLhL2p_5LY73B34omKnDQKgAHQfl?usp=drive_link)

Weights [Google Drive](https://drive.google.com/file/d/1Ki4GqtnGQqE67DvWUY3p7YJWSBZOgB8S/view?usp=drive_link)  [Google Drive](https://drive.google.com/file/d/1U2L_YcLlSmxIxvMBf6K-7ZnV1zxmyZeg/view?usp=drive_link)

## 🚀 Training
More configuration please see train.py and where you can set dataset path, batch size, weight path, and so on.

##  Packages
The following packages must be installed to use this project.
```
pip install -U openmim
mim install mmengine
mim install "mmcv>=2.0.0"
```

## 🔍 Result

⭐PR_curve
<img src="assets/pr1.png">

⭐PR_curve
<img src="assets/pr2.png">

## Cite this article

🔗🔗Paper link：https://www.tandfonline.com/doi/abs/10.1080/10589759.2024.2408441

Li X, Xu C, Li J, et al. Multi-scale sensing and multi-dimensional feature enhancement for surface defect detection of hot-rolled steel strip[J]. Nondestructive Testing and Evaluation, 2024: 1-24.

@article{li2024multi,
  title={Multi-scale sensing and multi-dimensional feature enhancement for surface defect detection of hot-rolled steel strip},
  author={Li, Xianguo and Xu, Changyu and Li, Jie and Zhou, Xinyi and Li, Yang},
  journal={Nondestructive Testing and Evaluation},
  pages={1--24},
  year={2024},
  publisher={Taylor \& Francis}
}
