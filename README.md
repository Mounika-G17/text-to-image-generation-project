# Text-to-Image Generation Project

## Overview

This project was developed as part of a Text-to-Image Generation internship. The objective was to implement and compare different text-to-image generation techniques, including Conditional GANs (CGAN), Attention-based GANs, and pre-trained diffusion models.

---

## Task 1: Fine-tuning a Pre-trained Text-to-Image Model

* Dataset: Hugging Face Anime Faces Dataset
* Model: Stable Diffusion v1.5
* Caption generation using BLIP
* Generated domain-specific anime artwork

### Output

* Stable Diffusion generated anime images

---

## Task 2: Conditional GAN (CGAN)

* Implemented a Conditional GAN using label conditioning
* Generated images based on labels:

  * Label 0 → Square
  * Label 1 → Circle

### Results

* Successfully generated conditioned shapes
* Visual outputs included in repository

---

## Task 3: Text Embeddings

* Implemented text preprocessing and embedding generation
* Used embeddings as conditioning information

---

## Task 4: Dataset Exploration and Visualization

* Loaded custom image datasets
* Performed visualization and preprocessing analysis
* Included dataset visualization outputs

---

## Task 5: Attention-based GAN

* Extended CGAN architecture using self-attention
* Compared generated outputs against baseline CGAN
* Evaluated qualitative image quality improvements

### Model Comparison

* CGAN generates basic shapes with slight noise
* Attention GAN improves visual consistency and boundary quality

---

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Diffusers
* Stable Diffusion
* BLIP
* Matplotlib
* Google Colab

---

## Repository Contents

* Text_to_Image_Project.ipynb
* training_loss.png
* cgan_output.png
* attention_gan_output.png
* model_comparison.png
* stable_diffusion_output.png
* task4_flower_dataset_visualization.png

---

## Conclusion

This project demonstrates multiple approaches to text-to-image generation, including GAN-based image generation, attention mechanisms, and diffusion-based image synthesis.
