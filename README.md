# Pedestrian & Cyclist Detection

# Key Features:

**Multi-Object Detection:**
The implementation includes the detection of both pedestrians and cyclists, providing a versatile solution for scenarios involving various moving entities.

**OpenCV Integration:** 
Leveraging the powerful OpenCV library, the project seamlessly processes video frames, extracts relevant information, and annotates objects with bounding boxes.

**YOLO Integration:**
The YOLO model, specifically YOLOv3, is integrated for accurate and efficient object detection. The configuration files and weights are included for ease of use.

**Pre-Annotated Output:**
 The output video is pre-annotated with bounding boxes around detected objects, enabling easy visualization of the model's performance.

## Required Input Files:
1. **YOLOv3 Weights:** Download the YOLOv3 weights file from the official YOLO website or repository and save it as "yolov3.weights".
2. **YOLOv3 Configuration File:** Obtain the YOLOv3 configuration file (yolov3.cfg) from the YOLO repository and save it as "yolov3.cfg".
3. **COCO Names File:** Download the COCO names file (coco.names) from the COCO dataset website and save it as "coco.names".
4. **Video File:** Provide the input video file in a common format (e.g., MP4) and update the file name in the code (replace "production_id_4791196.mp4" with your video file).

The below link will take you to "YOLO: Real-Time Object Detection" webpage, you can download the yolov3.weights and yolov3.cfg file:

https://pjreddie.com/darknet/yolo/
 
I got my video files from the client, however, if you are learning you can get similar videos from the web. One such website that I like: https://www.pexels.com/search/videos/pedestrians/

## Required Packages:
1. **OpenCV (cv2):** OpenCV is a crucial library for computer vision tasks. Install it using:
   ```bash
   pip install opencv-python
