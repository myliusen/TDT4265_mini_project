# TDT4265 Mini-Project

This repository contains code developed for the mini-project in the NTNU course **TDT4265 - Visual Intelligence**.

The project addresses automated tumor segmentation for **Subtask 1 (pre-treatment MRI)** of the Head and Neck Tumor Segmentation for MR-Guided Applications (HNTS-MRG) challenge.

## Dataset

*   The code is designed to work with the **HNTS-MRG** dataset.
*   Due to redistribution restrictions, the dataset is **not included** in this repository.
*   Users must obtain access to the HNTS-MRG dataset independently through the official challenge organizers or relevant data access agreements.

## Implementations

The primary implementations explored in this project are:

*   `unet.ipynb`: Implementation using a standard U-Net architecture.
*   `swin_unetr.ipynb`: Implementation using the Swin-UNETR architecture.

## Pretrained Weights

*   The `swin_unetr.ipynb` notebook utilizes pretrained weights for the Swin UNETR model.
*   These weights (`model_swinvit.pt`) were obtained from the official MONAI tutorials repository, specifically from the BTCV segmentation example:
    *   [MONAI Swin UNETR BTCV Tutorial](https://github.com/Project-MONAI/tutorials/blob/main/3d_segmentation/swin_unetr_btcv_segmentation_3d.ipynb)
*   The weights file is expected to be placed in the root directory for the notebook to load it correctly.
*   Final Swin-UNETR model weights can be obtained on request, bnt are not included here as the file is 800 megabytes.

---

**Disclaimer:** This README file was generated with the assistance of generative artificial intelligence.
