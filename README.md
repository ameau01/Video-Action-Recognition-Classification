# Video Action Recognition Classification (CSCA-5642 Final Project)

This repository contains a **deep learning solution for human action recognition (HAR)** from video clips using spatial-temporal modeling. The task is to classify short video sequences into action categories (e.g., kayaking, horse riding, tennis swing) by learning motion and appearance patterns from raw video data.

Action recognition (a form of video classification) is fundamental in computer vision with applications in sports analytics, robotics, surveillance systems, and human–machine interaction.

---

## Project Summary

- **Dataset:** UCF50 dataset from the University of Central Florida — a subset of the UCF101 benchmark for human actions in videos.  
  - ~6999 `.avi` clips
  - 50 action categories
  - Multi-view, unconstrained real-world videos
  - Resolution typically 320×240 with varied temporal frame counts :contentReference[oaicite:2]{index=2}

- **Goal:** Build and evaluate a **deep neural network-based classifier** that predicts the action class for each video clip.

- **Approach:**  
  - Analyze and preprocess the video dataset
  - Explore video frame statistics (resolution, FPS, duration, frame counts)
  - Build and train a **3D Convolutional Neural Network (3D-CNN)** to capture spatial and temporal features jointly (code in the Jupyter notebook)

---

## Directory Structure
Below is the directory structure of the project:

  ├── data/<br>
  │    ├── v_ApplyEyeMakeup_g01_c01.avi<br>
  │    ├── ...<br>
  │    └── v_ApplyLipstick_g01_c01.avi<br>
  └── video-action-recognition-final-project.ipynb<br>


## Files
- data/xxx.avi: Sample avi file from the UCF (University of Central Florida) Action Recognition Data Set.
- Video-Action-Classifier.ipynb: The main Jupyter Notebook containing the 3D Convolutional network definition. 

## Author
- **Author**: Alexander Meau
- **Email**: alme9155@colorado.edu
