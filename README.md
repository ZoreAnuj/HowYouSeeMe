# HowYouSeeMe: World Perception System

HowYouSeeMe is a unified perception system that integrates multiple computer vision models (YOLO, SLAM, segmentation, VLMs) into a cohesive world state summarizer. It explores how AI systems can build and maintain a persistent, interpretable understanding of visual environments, acting as a foundational layer for more complex reasoning.

## Key Features
- **Multi-Model Integration**: Combines object detection, spatial mapping, and semantic segmentation.
- **Unified World State**: Maintains a persistent and queryable representation of the visual environment.
- **MCP Interface**: Provides a standardized Model Context Protocol server for easy interaction with other AI components.

## Tech Stack
- Python, OpenCV, PyTorch
- YOLO, Segment Anything Model (SAM), Visual Language Models (VLMs)
- FastMCP, NumPy

## Getting Started
```bash
git clone https://github.com/zoreanuj/HowYouSeeMe.git
cd HowYouSeeMe
pip install -r requirements.txt
python main.py
```