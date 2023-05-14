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

## About The Project

This project aims to track people in different videos accounting for different angles.

The framework used to accomplish this task relies on MOT and ReID to track and re-identify ID's of humans, respectively. The tracking can be completed using YOLO_v3 or YOLO_v4 and ReID relies on Torchreid library.

Pretrained YOLO v3 : https://drive.google.com/file/d/1a7JI-A920lrdt6OKya-qCXx-5ZUWvkMg/view

Pretrained  YOLO v4 : https://drive.google.com/file/d/1pwFo4aHKPi0ztpL5tEYaXIr8RltYYQeY/view?usp=sharing

model.pth : https://drive.google.com/file/d/1z1yC4dlYsN5OgtlUNHqIMf8VwnWeE4Ty/view?usp=sharing

How to Run ? 

python demo.py --videos videos\init\Double1.mp4 videos\init\Single1.mp4 --version v3
