# HowYouSeeMe: World Perception System

HowYouSeeMe is a unified perception system that integrates multiple computer vision models (YOLO, SLAM, segmentation, VLMs) to build a comprehensive world state summarizer. It explores how AI systems can perceive and interpret complex environments, serving as a foundational interface for downstream reasoning and action.

## Key Features
- **Multi-Model Integration**: Combines object detection, spatial mapping, and semantic segmentation.
- **World State Summarization**: Aggregates disparate visual data into a unified scene representation.
- **MCP Interface**: Provides a standardized Model Context Protocol interface for other AI components.

## Tech Stack
- Python, OpenCV, PyTorch
- YOLO, Segment Anything Model (SAM), Visual Language Models (VLMs)
- MCP (Model Context Protocol)

## Getting Started
```bash
git clone https://github.com/zoreanuj/HowYouSeeMe.git
cd HowYouSeeMe
pip install -r requirements.txt
python main.py
```