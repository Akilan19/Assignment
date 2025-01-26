## Automatic Hand Tracking with SAM 2 and MediaPipe

This repository contains a pipeline for automatic hand tracking in videos using Google MediaPipe and Segment Anything Model (SAM 2). The pipeline detects hands in video frames, generates bounding boxes, and tracks hand movements across all frames, outputting a video with masked hands.

## Features
Hand Detection: Uses Google MediaPipe to detect hands in the first frame of a video.
Hand Tracking: Utilizes SAM 2 to propagate masks for hand regions throughout the video.
Output: Generates a video with masked hands, visualizing hand movement across frames.

## Pre-requisites
Ensure you have Python 3.12 and conda installed on your system.

Run the Jupyter notebook demo.ipynb for a step-by-step demonstration of the pipeline.

## Results
The masked video is saved as output/masked_video.mp4.
Hand regions are clearly segmented and tracked across frames.
