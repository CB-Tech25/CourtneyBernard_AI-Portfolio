# Courtney Bernard | Computer Vision & Applied AI Portfolio

## About Me

Hi, I'm Courtney Bernard, an AI & Robotics student at Houston Community College and a U.S. Army veteran.

This portfolio highlights my work in computer vision and applied artificial intelligence through ITAI 1378. Throughout the course, I progressed from image classification and convolutional neural networks to object detection, controlled image generation, vision-language models, and finally the development of a complete computer vision agent.

I am especially interested in understanding how AI systems work beyond simply getting code to run. My projects include testing model behavior, analyzing failures, comparing different approaches, and recognizing when human review is still necessary.

---

## Technical Skills

**Programming & Development**
- Python
- Jupyter Notebook
- Google Colab
- GitHub

**Computer Vision & AI**
- Convolutional Neural Networks (CNNs)
- Image Classification
- Object Detection
- Transfer Learning
- YOLO
- CLIP
- BLIP
- Vision-Language Models
- Generative AI
- Image-to-Image Generation
- Rule-Based AI Agents
- Human-in-the-Loop AI

**Libraries & Frameworks**
- PyTorch
- TensorFlow / Keras
- Transformers
- OpenCV
- NumPy
- Matplotlib

---

## ITAI 1378 – Computer Vision

This portfolio represents my progression through ITAI 1378, from learning how computer vision models process and classify images to developing an agent that combines multiple computer vision tools.

### Featured Projects

---

### 1. Chihuahua or Muffin with CNN

**Focus:** CNN Image Classification

This project uses a Convolutional Neural Network to distinguish between images of Chihuahuas and muffins.

Because the two classes can have surprisingly similar visual features, the project demonstrates how CNNs learn patterns such as edges, textures, shapes, and other image features.

**Skills demonstrated:**
- Image preprocessing
- CNN architecture
- Model training
- Image classification
- Model evaluation

➡️ See the `L05-CNN-Image-Classification` folder for the complete notebook, project README, and supporting report.

---

### 2. Object Detection Using Transfer Learning

**Focus:** Object Detection & Transfer Learning

This project moves beyond assigning one label to an entire image and explores how pretrained computer vision models can identify and locate objects within images.

It also demonstrates how transfer learning allows developers to use knowledge from an existing model instead of training a computer vision system completely from scratch.

**Skills demonstrated:**
- Object detection
- Transfer learning
- Pretrained models
- Confidence scores
- Bounding boxes
- Visualizing model predictions

➡️ See the `L06-Object-Detection` folder for the complete notebook, project README, and supporting report.

---

### 3. Controlled Image Generation

**Focus:** Generative Computer Vision

This project explores how generative image models can be controlled through prompts, seeds, and image-to-image generation.

I experimented with how changing inputs and generation settings affected the resulting images, including the creation of a Marrakech rooftop scene.

**Skills demonstrated:**
- Text-to-image generation
- Image-to-image generation
- Prompt engineering
- Seed control
- Generative AI
- Comparing generated outputs

➡️ See the `L07-Controlled-Image-Generation` folder for the complete notebook, project README, and supporting report.

---

### 4. Visual Language Models

**Focus:** CLIP, BLIP & Vision-Language AI

This project explores models that connect computer vision with natural language.

I used CLIP for zero-shot image classification and experimented with different prompt formats to see how language affected classification results. I also explored BLIP for image captioning.

One of the strongest CLIP prompt formats tested produced approximately **90.7% zero-shot classification performance** during the experiment.

**Skills demonstrated:**
- CLIP
- BLIP
- Zero-shot classification
- Image captioning
- Prompt experimentation
- Vision-Language Models

➡️ See the `L08-Visual-Language-Models` folder for the complete notebook, project README, and supporting report.

---

## Featured Capstone

### Auto Scene Assessment Agent

**Focus:** Multi-Tool Computer Vision Agent

My final ITAI 1378 capstone brings several concepts from the course together into one complete system.

The Auto Scene Assessment Agent combines:

**YOLO Object Detection + CLIP Scene Understanding + Rule-Based Reasoning + Human Review**

The agent analyzes an image using both computer vision models and then compares their outputs before making a final decision.

When model confidence is low or YOLO and CLIP disagree, the system can recommend human review rather than automatically trusting the prediction.

### Final Evaluation

- **10** test images
- **10/10** successful end-to-end runs
- **100%** pipeline completion rate
- **4** cases flagged for review
- **40%** review rate
- **0.212 seconds** average YOLO inference time

One of my biggest takeaways from this project was that **model confidence does not always mean the model is correct**. Some of the most useful test cases were the ones where the models failed or disagreed.

➡️ See the `Final-Capstone-Auto-Scene-Agent` folder for the portfolio overview.

### Complete Capstone Repository

https://github.com/CB-Tech25/IATI1378_Auto_Scene_Agent

---

## What I Learned

My biggest growth throughout this course was learning to look beyond whether a model simply produced an answer.

I learned to ask:

- What information is the model actually using?
- How confident is the prediction?
- Does the output make sense?
- What happens when two models disagree?
- What can I learn from the failures?
- When should a human make the final decision?

Working through classification, object detection, generative models, vision-language models, and AI agents helped me see how individual computer vision concepts can eventually be combined into a larger AI system.

---

## Portfolio Structure

```text
Courtney-Bernard-AI-Portfolio/
│
├── README.md
│
├── L05-CNN-Image-Classification/
├── L06-Object-Detection/
├── L07-Controlled-Image-Generation/
├── L08-Visual-Language-Models/
└── Final-Capstone-Auto-Scene-Agent/
