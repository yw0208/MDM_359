# MDM_359
<<<<<<< HEAD

This repository is a fork of [motion-diffusion-model](https://github.com/GuyTevet/motion-diffusion-model), which can be used to generate human motions with dexterous right hand.

## 📥 Setup

### Download SMPL-X Models

Due to file size limitations, large model files are not included in the repository. Please download them manually:

1. Download SMPL-X models from [official source](https://smpl-x.is.tue.mpg.de/)
2. Place them in `body_models/smplx/` directory

```
body_models/smplx/
├── SMPLX_MALE.npz
├── SMPLX_FEMALE.npz
└── SMPLX_NEUTRAL.npz
```

## 🚀 Quick Start

To generate controllable motion, run the following command:

```
python train/train_mdm.py
``` 

The trianed model will be used as the main branch of ScoMoGen. Please refer to [HOSIG](https://github.com/yw0208/HOSIG) for more details.

If you meet any issue, please feel free to contact me!
