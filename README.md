# Deep Learning Project: Medical Image Classification and Segmentation

A group deep learning project (Group 12) that applies CNNs and transfer learning to medical imaging.

## Notebooks

| Notebook | Task |
|----------|------|
| `BCancer_class.ipynb` | Breast cancer classification with custom CNNs and transfer learning (VGG16, MobileNet) using early stopping |
| `BCancer_img.ipynb` | Breast cancer image classification experiments |
| `BreastCancerImageSeg.ipynb` | Breast cancer image segmentation |
| `brainmri.ipynb` | Brain MRI tumour analysis |
| `lungs_segmentation_using_u_nets.ipynb` | Lung segmentation from chest X-rays with U-Net |

The project slides are in `Group12_PPT (1).pptx`.

## Tech stack

Python, TensorFlow / Keras, NumPy, pandas, matplotlib, Jupyter

## Getting started

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn opencv-python jupyter
jupyter notebook
```

The datasets aren't included. Each notebook loads its data from public medical imaging datasets, such as those on Kaggle.
