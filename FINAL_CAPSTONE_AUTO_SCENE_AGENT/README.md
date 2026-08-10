# Auto Scene Assessment Agent

## ITAI 1378 Final Capstone

This is my final Computer Vision capstone project and the most complete system in my portfolio.

I developed a Tier 2 computer vision agent that combines YOLO object detection and CLIP scene understanding with rule-based reasoning. The agent analyzes information from both models before making a final decision and can recommend human review when confidence is low or the models disagree.

## Technologies Used

- Python
- YOLO
- CLIP
- PyTorch
- Transformers
- OpenCV
- Google Colab
- Rule-Based AI Agents

## System Workflow

Image Input  
→ YOLO Object Detection  
→ CLIP Scene Classification  
→ Rule-Based Reasoning  
→ Agent Decision  
→ Results and Trace Logging

## Results

The completed system was evaluated using 10 test images.

- 10/10 successful end-to-end runs
- 100% pipeline completion rate
- 4 cases flagged for review
- 40% review rate
- 0.212 second average YOLO inference time

The project also includes failure analysis, error handling, structured outputs, annotated images, and individual execution traces.

## Key Finding

One of my biggest takeaways from this project was that model confidence does not always mean the prediction is correct.

Using YOLO and CLIP together showed me that two computer vision models can interpret the same image differently. Instead of hiding those disagreements, I used them as part of the agent's reasoning and included human review for uncertain results.

## Full Project

The complete project has its own GitHub repository containing:

- Jupyter notebook with code and outputs
- Sample test images
- YOLO results
- CLIP results
- Annotated images
- Agent decisions
- Evaluation metrics
- Execution traces
- Architecture documentation
- AI usage log
- Final presentation

### View the Complete Project

https://github.com/CB-Tech25/IATI1378_Auto_Scene_Agent
