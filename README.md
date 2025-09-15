# Pneumonia Detection Using X-ray

Empowering Computer Vision for improving Healthtech by automatically detecting pneumonia from chest X-ray images using deep learning.

---

## Overview

This project demonstrates the use of **deep learning models** to classify chest X-ray images as either "Pneumonia" or "Normal," supporting faster and more accurate healthcare diagnostics. The workflow leverages convolutional neural networks (CNNs) and transfer learning to automate pneumonia detection, aiming to assist radiologists and improve clinical workflow efficiency[1][3].

---

## Dataset

- **Source:** [Chest X-Ray Images (Pneumonia) from Kaggle][5]
- **Total images:** 5,863 X-ray images of pediatric patients
- **Classes:** `PNEUMONIA`, `NORMAL`
- **Folders:** Structured into `train/`, `test/`, and `val/`, each with class subfolders

Download the dataset and extract it into a `data/` or `chest_xray/` directory at the project root[2][1].

[5]: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

---

## Features

- **Automatic data preprocessing:** Resizing, normalization, augmentation
- **Model:** CNN (TensorFlow/Keras or PyTorch)
- **Evaluation:** Reports accuracy, confusion matrix, and prediction examples
- **Deployment:** Trained model can be exported and used for real-time inference[4][3]

---

## Installation


Download the Kaggle dataset and place it in the correct folder.

---

## Usage

1. **Training**
   - Run the Jupyter notebook or Python training script.
   - Ensure the dataset path is correctly set in the code.

2. **Testing**
   - Evaluate the trained model on the test set to see overall performance.
   - Visualize results and check misclassified images.

3. **Prediction**
   - To predict a new X-ray image:
     ```
     python predict.py --image_path /path/to/xray.png
     ```
   - Modify file/script names as needed for your codebase.

---

## Results

- High accuracy in distinguishing pneumonia from normal chest X-rays.
- Outputs include a confusion matrix and sample image predictions.

---

## References

- Kaggle Dataset: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)[2]


---

## License

MIT License

---

## Acknowledgements

Thanks to the Kaggle and research community for open datasets and technical resources that power modern healthcare innovation[1][2].

