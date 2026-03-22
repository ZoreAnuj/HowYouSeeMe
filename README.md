# HowYouSeeMe: World Perception System

HowYouSeeMe is a unified world state summarizer that integrates multiple computer vision models (YOLO, SLAM, segmentation, VLMs) into a cohesive perception system. It explores building a "human layer" for AI by synthesizing diverse visual understanding into a single interpretable interface.

## Key Features
*   Unified integration of YOLO for object detection and SLAM for spatial mapping.
*   Combines segmentation models and Vision Language Models (VLMs) for detailed scene understanding.
*   Provides a summarized world state output from multi-model perception.

## Tech Stack
Python, OpenCV, YOLO, ORB-SLAM3, Segment Anything Model (SAM), Vision Language Models (e.g., LLaVA), MCP Server

## Getting Started
```bash
git clone https://github.com/zoreanuj/HowYouSeeMe.git
cd HowYouSeeMe
pip install -r requirements.txt
python main.py
```