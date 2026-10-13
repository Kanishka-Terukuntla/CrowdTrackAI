# CrowdTrack AI

**Real-Time Multi-Person Tracking and People Counting**

CrowdTrack AI is a computer vision project that detects and tracks pedestrians in video footage and counts people crossing a configurable virtual line.

## Objectives

- Detect pedestrians in video frames.
- Maintain tracking IDs across consecutive frames.
- Count entries and exits using virtual-line crossing.
- Evaluate tracking quality and counting accuracy.
- Measure inference speed and latency.

## Technology Stack

- Python
- OpenCV
- Ultralytics YOLO
- Multi-object tracking
- NumPy and Pandas
- Scikit-learn and Matplotlib

## Dataset

This project uses the MOT17 multi-object tracking benchmark.

The dataset is not included in this repository. Download it from the [official MOTChallenge website](https://motchallenge.net/data/MOT17/) and follow its licensing and attribution requirements.

## Project Status

Currently in development.

## Planned Components

1. Dataset inspection and visualization
2. Person detection
3. Multi-object tracking
4. Virtual-line crossing and directional counting
5. Evaluation and error analysis
6. Demonstration interface

## License

A project license will be selected before public release. Third-party datasets and model weights remain subject to their respective licenses and terms.
