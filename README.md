# Enhanced-Railway-Track-Object-Detection-Using-YOLOv8-and-Knowledge-Distillation
This project presents an efficient two-stage deep learning pipeline for real-time detection of foreign objects on railway tracks. By combining a lightweight image classification network with YOLOv8 and knowledge distillation, it enhances both speed and accuracy, aiming to prevent accidents and ensure rail safety.

# Enhanced Railway Track Object Detection Using YOLOv8 and Knowledge Distillation

## Description
This project presents an efficient two-stage deep learning pipeline for real-time detection of foreign objects on railway tracks. By combining a lightweight image classification network with YOLOv8 and knowledge distillation, it enhances both speed and accuracy, aiming to prevent accidents and ensure rail safety.

## Abstract
The efficient and accurate detection of foreign objects on railway tracks is critical to ensuring the safety and smooth operation of train systems. This work addresses the limitations of existing foreign object detection methods, including low efficiency and suboptimal accuracy, by proposing an enhanced railway foreign object intrusion detection framework leveraging YOLOv8 and Overhaul Knowledge Distillation. The proposed method consists of a two-stage architecture. In the first stage, a lightweight image classification network quickly determines whether a railway image contains foreign objects. This stage minimizes reliance on computationally intensive object detection models, thereby enhancing detection speed. In the second stage, YOLOv8 is employed to precisely detect and localize foreign objects in images flagged by the classification network. The choice of YOLOv8 provides notable improvements in accuracy and inference speed over previous versions such as YOLOv3. Additionally, the Overhaul Knowledge Distillation algorithm is applied to train the lightweight classification network under the supervision of a larger, more robust network, ensuring competitive classification performance while maintaining efficiency. Experimental results demonstrate that the proposed method achieves state-of-the-art performance in both detection accuracy and speed, with significant improvements in FPS and detection robustness compared to earlier approaches.

## Technologies Used
- YOLOv8 (You Only Look Once - Object Detection)
- Overhaul Knowledge Distillation
- PyTorch / Ultralytics YOLO
- Python
- OpenCV
- Image Classification Networks (e.g., MobileNet, EfficientNet)

## Features
- Two-stage detection pipeline:
  - Stage 1: Fast image classification to detect presence of foreign objects.
  - Stage 2: Accurate localization using YOLOv8.
- Enhanced inference speed and robustness.
- Lightweight model training with knowledge distillation.
- Real-time detection performance.
- Compatible with large-scale datasets.

## Dataset
-Custom dataset of railway track images with and without foreign objects.
-Annotated in YOLO format for training and evaluation.

#Performance Metrics
-Increased detection FPS (frames per second).
-High classification accuracy and detection precision.
-Robust under varied lighting and environmental conditions.

## Future Improvements
-Integration with edge devices like Jetson Nano for on-track deployment.
-Live video feed analysis for continuous railway monitoring.
-Use of thermal imagery for night-time detection.

## License
This project is licensed under the MIT License.

