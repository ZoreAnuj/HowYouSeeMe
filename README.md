# HowYouSeeMe: World Perception System

HowYouSeeMe is a unified perception system that integrates multiple computer vision models (YOLO, SLAM, Segmentation, VLMs) to build a comprehensive, real-time world state summarizer. It explores how AI systems can perceive and interpret complex environments, serving as a foundational interface for higher-level reasoning.

## Key Features
- **Multi-Model Integration**: Combines object detection, spatial mapping, and semantic segmentation.
- **Unified World State**: Fuses disparate vision outputs into a single, coherent representation.
- **Real-Time Summarization**: Provides continuous, interpretable descriptions of the perceived environment.

## Tech Stack
- Python
- YOLO (Object Detection)
- SLAM (Simultaneous Localization and Mapping)
- Segment Anything Model (Segmentation)
- Vision Language Models (VLMs)

## Getting Started
```bash
git clone https://github.com/zoreanuj/HowYouSeeMe.git
cd HowYouSeeMe
pip install -r requirements.txt
python main.py
```