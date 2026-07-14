# 🎨 Face Cartoonization using Pix2Pix and CycleGAN

A Deep Learning project that compares **Pix2Pix** and **CycleGAN** for face cartoonization. The project evaluates both models in terms of image quality and performance using quantitative image similarity metrics.

---

## 📌 Project Overview

The objective of this project is to transform real human face images into cartoon-style images using Generative Adversarial Networks (GANs).

Two state-of-the-art image-to-image translation models were implemented and compared:

- Pix2Pix (Paired Image Translation)
- CycleGAN (Unpaired Image Translation)

The comparison highlights the strengths and limitations of each model when generating cartoonized faces.

---

## 🚀 Models Used

### Pix2Pix
- Conditional GAN
- Requires paired datasets
- Supervised image-to-image translation

### CycleGAN
- Unpaired image-to-image translation
- Uses Cycle Consistency Loss
- Does not require paired datasets

---

## 📂 Dataset

Face2Comics Dataset

The dataset contains:

- Real face images
- Cartoon face images

---

## 🛠 Technologies

- Python
- PyTorch
- NumPy
- Matplotlib
- PIL
- scikit-image
- scikit-learn

---

## 📊 Evaluation Metrics

The generated images were evaluated using:

- PSNR (Peak Signal-to-Noise Ratio)
- SSIM (Structural Similarity Index)
- MSE (Mean Squared Error)
- MAE (Mean Absolute Error)

---

## 📈 Comparison

| Model | Paired Data | Unpaired Data | Image Quality |
|--------|-------------|---------------|---------------|
| Pix2Pix | ✅ | ❌ | High |
| CycleGAN | ❌ | ✅ | High |

---

## 📁 Project Structure

```
Face-Cartoonization/
│
├── pix2pix/
├── cyclegan/
├── images/
├── models/
├── notebooks/
├── requirements.txt
└── README.md
```

---

## 📷 Results

Example outputs include:

- Original Face
- Pix2Pix Output
- CycleGAN Output

Performance comparison is provided using quantitative metrics.

---

## Future Improvements

- Train on larger datasets
- Improve image resolution
- Deploy as a web application using Streamlit
- Add FID and LPIPS evaluation metrics

---

## Author

Clara Samir Fakeh

AI Engineer | Computer Vision | Deep Learning
