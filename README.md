# Generative Modelling Case Study (GANs)

## Overview

This project explores **Generative Adversarial Networks (GANs)** from fundamentals to advanced real-world applications. It demonstrates how GANs learn data distributions and generate realistic synthetic samples across multiple domains, including mathematical functions, medical imaging, cybersecurity data, and creative sketch generation.

---

## Project Structure

### Part 1: GANs from Scratch

* Implementation of a basic GAN using PyTorch
* Learning 2D data distributions:

  * Sine wave generation
  * 2D spiral distribution
* Step-by-step improvement of architecture:

  * Deeper MLP networks
  * Stabilisation techniques (noise injection, improved optimizers, label smoothing)
* Visual comparison of real vs generated data

---

### Part 2: Real-World Applications

#### 2.1 Medical Imaging (MedMNIST - Blood Cells)

* DCGAN implementation for image synthesis
* Training on blood cell microscopy images
* Evaluation using:

  * Loss curves
  * Real vs fake image comparison
  * FID (Fréchet Inception Distance) score

---

#### 2.2 Cybersecurity (CICIDS 2017)

* GAN applied to tabular network intrusion data
* Synthetic generation of BENIGN vs DoS traffic
* Preprocessing:

  * Feature scaling and cleaning
* Evaluation:

  * t-SNE visualization
  * Statistical comparison (KS test, mean/std differences)

---

#### 2.3 Creative AI (QuickDraw Pizza Sketches)

* GAN trained on sketch-based image data
* Stroke-to-image preprocessing pipeline
* CNN-based Generator and Discriminator
* Outputs:

  * Generated sketch samples
  * Real vs fake comparisons
  * Training stability analysis

---

## Key Techniques Used

* Generative Adversarial Networks (GANs)
* Deep Convolutional GANs (DCGANs)
* Conditional GANs (cGANs)
* MLP-based GANs for tabular data
* Data preprocessing & normalization
* PyTorch deep learning framework
* Model evaluation (FID, t-SNE, statistical metrics)

---

## Results Summary

* GANs successfully learned complex distributions across different data types
* Improved architectures significantly enhanced stability and output quality
* Demonstrated adaptability of GANs in:

  * Scientific data (medical)
  * Security systems (network traffic)
  * Creative AI (sketch generation)

---

## Tools & Libraries

* Python
* PyTorch
* NumPy
* Matplotlib
* Scikit-learn
* MedMNIST
* OpenCV

---

## Conclusion

This project highlights the versatility of GANs in modelling diverse data distributions. From simple mathematical functions to high-dimensional real-world datasets, GANs demonstrate strong potential for synthetic data generation, anomaly detection, and creative AI applications.
