<br/>
<p align="center">
  <h3 align="center">Multi-Camera-Person-Tracking-and-ReID
</h3>

  <p align="center">
    Multi Camera Person Tracking and Re-Identification (Computer Vision, Deep Learning): "Detect/Track" and
"Re-Identify" individuals in different cameras/videos using YOLO v3/v4 and ReID
    <br/>
    <br/>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/Aditya5052/Multi-Camera-Person-Tracking-and-ReID?color=dark-green) ![Stargazers](https://img.shields.io/github/stars/Aditya5052/Multi-Camera-Person-Tracking-and-ReID?style=social) ![Issues](https://img.shields.io/github/issues/Aditya5052/Multi-Camera-Person-Tracking-and-ReID) 

### Overview

**Multi-Camera-Person-Tracking-and-ReID** is a comprehensive computer vision and deep learning project designed for the detection, tracking, and re-identification of individuals across various cameras or videos. This project leverages cutting-edge technologies such as YOLO v3/v4 for detection and the Torchreid library for ReID. The goal is to provide a robust solution capable of accurately tracking people in different video streams, accommodating variations in angles and perspectives.

### Project Objectives

1. **Person Detection and Tracking**: The project employs YOLO v3/v4 for precise person detection and tracking across diverse camera angles, ensuring reliable tracking even in challenging scenarios.

2. **Re-Identification (ReID)**: Utilizing the Torchreid library, the project focuses on re-identifying individuals across different cameras. This is essential for maintaining consistent tracking of identities across multiple video feeds.

### Project Structure

- **`model_data\models` Folder**: Add the following pre-trained models to this folder:
  - [Pretrained YOLO v3](https://drive.google.com/file/d/1a7JI-A920lrdt6OKya-qCXx-5ZUWvkMg/view)
  - [Pretrained YOLO v4](https://drive.google.com/file/d/1pwFo4aHKPi0ztpL5tEYaXIr8RltYYQeY/view?usp=sharing)
  - [Torchreid Model](https://drive.google.com/file/d/1z1yC4dlYsN5OgtlUNHqIMf8VwnWeE4Ty/view?usp=sharing)

### Usage

#### Prerequisites

- Install the necessary dependencies:

  ```bash
  pip install torch torchvision numpy
  ```

- Clone the repository:

  ```bash
  git clone https://github.com/Aditya5052/Multi-Camera-Person-Tracking-and-ReID.git
  cd Multi-Camera-Person-Tracking-and-ReID
  ```

#### Run the Demo

```bash
python demo.py --videos videos\init\Double1.mp4 videos\init\Single1.mp4 --version v3
```

Replace the video paths with your own and specify the YOLO version (`v3` or `v4`) accordingly.

### Result 

![Complete](https://github.com/Aditya5052/Multi-Camera-Person-Tracking-and-ReID/assets/72243114/98e6349e-41e8-4d45-b537-19eb760c4f76)
