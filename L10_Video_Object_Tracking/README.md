# Video Analysis and Object Tracking

## Project Overview

This project moves computer vision from analyzing individual images to analyzing objects across video frames.

The system uses YOLO for object detection and compares ByteTrack and BoT-SORT for object tracking.

## Problem Statement

Detecting an object in one image is different from maintaining that object's identity across an entire video.

A tracking system must determine whether an object appearing in the next frame is the same object it detected previously.

## Approach

The project uses tracking-by-detection.

YOLO first detects objects in video frames. A tracker then assigns and maintains track IDs as those objects move through the video.

The project includes:

- YOLO object detection
- Video frame processing
- Object tracking
- Unique track IDs
- ByteTrack
- BoT-SORT
- Comparison of tracker behavior
- Analysis of tracking failures

## Technologies Used

- Python
- Ultralytics YOLO
- ByteTrack
- BoT-SORT
- OpenCV
- Google Colab
- Video Analysis
- Multi-Object Tracking

## Results

The completed notebook contains the tracking outputs and comparison results from the video analysis.

The experiment demonstrates that detecting objects successfully does not automatically mean their identities will be tracked perfectly across frames.

## Key Findings

One of the biggest things I learned from this project was the difference between detection and tracking.

YOLO can detect an object in an individual frame, but the tracker has the additional job of maintaining that object's identity over time.

Tracking can become difficult when objects overlap, leave the frame, reappear, or become temporarily hidden.

Comparing ByteTrack and BoT-SORT also showed that different tracking approaches can behave differently on the same video.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Install the required dependencies.
3. Load the YOLO model.
4. Upload or load the test video.
5. Run YOLO with ByteTrack.
6. Review the tracking output and track IDs.
7. Run the comparison using BoT-SORT.
8. Compare the results and review tracking failures.
