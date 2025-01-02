BLIP Live Image Captioning with Real-Time Video Stream

This repository provides a Python-based implementation for real-time image captioning using the BLIP (Bootstrapped Language-Image Pretraining) model. The program captures live video from a webcam, generates captions for each frame using the BLIP model, and overlays the captions along with FPS and GPU usage information onto the video feed.
Features

    Real-Time Video Stream: Captures live webcam feed and displays it with captions.
    BLIP Image Captioning: Leverages the Salesforce/blip-image-captioning-large model for generating accurate and descriptive captions.
    GPU Acceleration: Supports CUDA for faster inference when a GPU is available.
    Performance Metrics: Displays GPU memory usage and real-time FPS on the video stream.
    Threaded Caption Generation: Ensures smooth video streaming with asynchronous caption processing.

Prerequisites

    Python 3.8 or higher
    Dependencies: OpenCV, PyTorch, Transformers, Pillow



git clone https://github.com/zawawiAI/BLIP_CAM.git
cd BLIP_CAM


pip install -r requirements.txt

python BLIP_CAM.py


Applications

    AI-powered video content analysis.
    Assistive technologies for visually impaired users.
    Enhanced video conferencing with automatic scene descriptions.

Contributions

Feel free to submit issues, pull requests, or suggestions to improve this project. Let’s make real-time AI captioning more accessible and robust!

    


https://github.com/user-attachments/assets/3750ada3-811e-4e7a-a572-c9a57099b847

