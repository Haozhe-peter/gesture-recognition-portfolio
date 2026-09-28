# Real-Time Gesture Recognition

A computer-vision project for recognizing hand gestures from a live webcam feed.

> **Note:** This public portfolio repository documents my project contribution and approach. The original course-team implementation remains private.

## Overview

Built a low-latency pipeline that tracks hand landmarks and classifies gestures in real time. The system combines video preprocessing with a rule-based recognition layer to turn gesture sequences into control commands.

## Highlights

- Captured and processed live webcam frames with **Python** and **OpenCV**
- Used **MediaPipe** hand landmarks for real-time gesture detection
- Applied adaptive thresholding and noise removal for more stable recognition under changing lighting
- Designed a rule-based state machine for mapping gesture sequences to commands
- Reduced hand-boundary collision loss by 50% through pipeline improvements

## Tech Stack

`Python` · `OpenCV` · `MediaPipe` · `NumPy` · `Jupyter Notebook`

## My Focus

I worked on building a responsive, robust vision pipeline that could perform reliably in real-world webcam conditions.
