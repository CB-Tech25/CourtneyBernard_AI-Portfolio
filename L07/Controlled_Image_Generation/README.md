# Controlled Image Generation

## Project Overview

This project explores controlled image generation using generative AI models. The goal was to see how different inputs and settings can influence the images produced by a generative computer vision system.

Instead of treating image generation as completely random, I experimented with ways to control the output and compare the results.

## Problem Statement

Generative image models can create very different results from similar prompts. This project explores how prompt design, seeds, and image-to-image generation can be used to create more controlled and repeatable outputs.

## Approach

The project included:

- Text-to-image generation
- Prompt engineering
- Seed control
- Comparing generated outputs
- Image-to-image generation
- Adjusting generation settings
- Reviewing how changes affected the final image

One of my generated scenes used a Marrakech rooftop setting, which allowed me to experiment with creating a specific visual environment instead of using only generic prompts.

## Technologies Used

- Python
- Google Colab
- Generative AI
- Diffusion Models
- Text-to-Image Generation
- Image-to-Image Generation
- Prompt Engineering

## Dataset and Model

This project does not use a traditional public training dataset.

The image generation experiments use the pretrained **Stable Diffusion v1.5** model through the Hugging Face Diffusers library.

**Model source:**  
https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5

The model is loaded directly in the notebook using:

StableDiffusionPipeline.from_pretrained(
    "stable-diffusion-v1-5/stable-diffusion-v1-5"
)

The model weights are downloaded automatically when the notebook is run, so they are not stored in this GitHub repository.

For the image-to-image portion of the project, I used a personal travel photograph that I took myself as the input image rather than a public dataset.

## Results

The notebook contains the generated images and comparisons produced during the lab.

Using the same or controlled settings helped demonstrate how seeds can make image generation more reproducible, while changing prompts or image inputs produced different visual results.

## Key Findings

This project helped me understand that generative computer vision is not only about writing a prompt and accepting whatever image is produced.

Small changes in the prompt, seed, and generation settings can significantly affect the result.

I also learned how image-to-image generation provides another level of control because an existing image can influence the structure and appearance of the generated output.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Run the installation and import cells.
3. Load the image generation model.
4. Run the text-to-image generation cells.
5. Compare results using controlled seeds and prompts.
6. Run the image-to-image section.
7. Review and compare the generated outputs.
