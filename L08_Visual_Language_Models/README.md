# Visual Language Models (VLMs)

## Project Overview

This project explores Vision-Language Models and how AI can connect visual information with natural language.

The lab included CLIP for zero-shot image classification and BLIP for image captioning.

## Problem Statement

Traditional computer vision models are often designed for a specific task or fixed set of labels. Vision-Language Models connect images and text, allowing a system to interpret visual content using natural-language descriptions.

## Approach

The project explored two different Vision-Language Model capabilities:

### CLIP

CLIP was used for zero-shot image classification.

Instead of training a new classifier from scratch, the model compared images against text descriptions and selected the description that best matched each image.

I also experimented with different prompt wording to see how the text descriptions affected classification performance.

### BLIP

BLIP was used for image captioning.

Instead of selecting from predefined categories, the model generated natural-language descriptions of image content.

## Technologies Used

- Python
- PyTorch
- CLIP
- BLIP
- Transformers
- CIFAR-10
- Google Colab
- Vision-Language Models
- Zero-Shot Classification
- Image Captioning

## Results

During CLIP testing, prompt wording affected classification performance.

One of the strongest prompt formats tested was:

`a blurry low-resolution photo of a {}`

Using this prompt produced a zero-shot classification result of approximately **90.7%** during the experiment.

The BLIP portion of the project demonstrated a different Vision-Language capability by generating text captions from image inputs.

## Key Findings

One of the biggest things I learned from this project was that the text given to a Vision-Language Model matters.

CLIP did not require me to train a traditional classifier on every category. Instead, it used relationships between images and language to perform zero-shot classification.

I also learned that prompt wording can affect model performance.

This project later helped me understand how CLIP could be used for scene-level understanding in my final Computer Vision capstone.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Run the installation and import cells.
3. Load the required models and dataset.
4. Run the CLIP zero-shot classification section.
5. Compare the different text prompts.
6. Run the BLIP image-captioning section.
7. Review the classification and captioning outputs.
