# Handball Analytics

**AI-Based Handball Player Detection, Tracking, Team Identification and Movement Analytics using Deep Learning and Computer Vision.**

## 1. Project Overview

Handball Analytics is a computer vision-based project designed to analyze handball match videos automatically. The system uses deep learning and object tracking techniques to detect players, assign tracking IDs, identify teams and analyze player movements.

The project aims to support player performance analysis and provide useful movement information from match videos.

## 2. Objectives

- Detect players from handball match videos.
- Track players across video frames.
- Assign unique IDs to detected players.
- Identify teams using visual color features.
- Extract player positions.
- Analyze player movement patterns and statistics.

## 3. Modules

### Module 1: Player Detection and Tracking
- YOLO-based player detection.
- ByteTrack object tracking.
- Unique player ID assignment.

### Module 2: Player Movement Analytics
- Player position extraction.
- Movement trajectory analysis.
- Player movement statistics.
- Heatmap-based movement visualization.

### Additional Component: Team Identification
- Upper-body region extraction.
- HSV color feature analysis.
- K-Means clustering for provisional team classification.

## 4. Technologies Used

- Python
- YOLOv8 / YOLO11
- ByteTrack
- OpenCV
- Deep Learning
- Computer Vision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## 5. Experimental Results

The YOLO11n and ByteTrack implementation was evaluated on sampled handball match video frames.

- Frames processed: 79
- Player detections: 533
- Unique tracking IDs: 38
- Processing time: 16.21 seconds
- Processing speed: 4.87 FPS

The experiments demonstrate the feasibility of automated player detection, tracking and movement analysis.

## 6. Project Files

- `Handball_Working_Source_Code.zip` – Project source code.
- `127163004_latex_source.zip` – LaTeX report source.
- `handball_team_identification_h264[1] (1).mp4` – Project result video.

## 7. Applications

- Handball player performance analysis.
- Player movement monitoring.
- Team movement analysis.
- Sports video analytics.
- Computer vision-based sports analysis.

## 8. Future Enhancements

- Real-time player tracking.
- Improved team identification.
- Player speed and distance estimation.
- Advanced match statistics.
- Automated performance reports.

## 9. Conclusion

This project demonstrates an AI-based approach to handball video analysis using deep learning and computer vision. It combines player detection, tracking, team identification and movement analytics to support automated sports performance analysis.

---

**Project Domain:** Artificial Intelligence, Deep Learning and Computer Vision.
