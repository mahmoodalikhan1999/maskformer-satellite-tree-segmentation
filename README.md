# MaskFormer Satellite Tree Segmentation 🌳🛰️

This project leverages the **MaskFormer** model to perform semantic segmentation on satellite imagery, specifically focusing on **tree and vegetation detection**. Built in Python using PyTorch and Detectron2, this notebook provides a complete pipeline from dataset loading to training and evaluation.

## 🧠 Model

**MaskFormer** is a transformer-based architecture for image segmentation tasks. It unifies semantic, instance, and panoptic segmentation into a single framework.

## 📁 Contents

- `Copy_of_maskformer_satellite_trees.ipynb`: Main notebook with all preprocessing, model setup, training, and evaluation steps.
- Example visualizations of segmented tree regions.
- Dataset assumed to be compatible with COCO or Detectron2 format (custom loading logic included).

## 📦 Requirements

- Python 3.8+
- PyTorch
- Detectron2
- OpenCV
- NumPy
- Matplotlib
- Jupyter

Install Detectron2 (official method):
```bash
pip install 'git+https://github.com/facebookresearch/detectron2.git'
