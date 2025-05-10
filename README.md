
# 🌥️ CloudSeg: Deep Learning for Cloud and Cloud-Shadow Segmentation

**Author:** Emmanuel Asante  
**Affiliation:** Graduate Student, Northeastern University  
**Program:** MPS in Analytics (Concentration: Machine Intelligence)

---

## 📘 Overview

**CloudSeg** is a research-driven project that explores and compares deep learning models for cloud and cloud-shadow detection in satellite imagery, using the [38-Cloud dataset](https://www.kaggle.com/datasets/sorour/38cloud-cloud-segmentation-in-satellite-images).

This repository contains several Jupyter notebooks implementing various models and preprocessing techniques to perform semantic segmentation of clouds from multispectral satellite images.

---

## 🧠 Models Implemented

- **LightCSPNet**: A lightweight CNN-based model benchmarked for cloud segmentation.
- **SegFormer**: A transformer-based architecture applied to cloud masking tasks.
- **CloudViT**: Vision Transformer architecture used for cloud detection and comparison.
- **Otsu Thresholding**: A classical baseline method for binary mask generation using pixel-level intensity distributions.

---

## 📂 Repository Contents

| File Name | Description |
| --------- | ----------- |
| `LightCSPNet_38Cloud.ipynb` | Training and evaluation of LightCSPNet on the 38-Cloud dataset |
| `SegFormer_38Cloud_Eval.ipynb` | Evaluation of SegFormer outputs and Dice/IoU scores |
| `CloudViT.ipynb` | Vision Transformer (ViT) pipeline for segmentation |
| `LightCSPNet_Cloud_Masking_with_Threshold_Slider.ipynb` | Interactive cloud masking using sliders and LightCSPNet predictions |
| `Otsu's method for mask generation.ipynb` | Classical thresholding for mask creation |

---

## 📊 Dataset

- **Source**: 38-Cloud
- **Format**: Multispectral Landsat 8 imagery
- **Ground Truth**: Binary cloud masks
- **Link**: https://drive.google.com/file/d/1K7kGhtxy2sHfiimci0GW08kaEzvHA69G/view?usp=sharing

Each image is processed into RGB format or full multispectral input for training and evaluation.

---

## 🛠️ Features & Highlights

- Interactive threshold tuning (with sliders)
- Dice coefficient & IoU evaluation metrics
- Model comparison: CNNs vs. Transformers
- Custom mask visualizations with overlay

---

## 🏁 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cloudseg.git
   cd cloudseg
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 📈 Sample Output

*(Insert sample visual here of cloud mask prediction vs. ground truth)*

---

## 🤝 Acknowledgments

- Kaggle 38-Cloud Dataset
- SegFormer, LightCSPNet, and ViT source papers
- Northeastern University – Roux Institute

---

## 📜 License

This project is for academic and research use. Feel free to fork and build on it with attribution.

---

> For questions, collaborations, or feedback, reach out at [emanuelasante2@gmail.com](mailto:emanuelasante2@gmail.com)
