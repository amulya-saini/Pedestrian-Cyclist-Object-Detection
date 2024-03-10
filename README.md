# Pedestrian & Cyclist Detection

# Key Features:

**Multi-Object Detection:**
The implementation includes the detection of both pedestrians and cyclists, providing a versatile solution for scenarios involving various moving entities.

**OpenCV Integration:** 
The project uses the powerful OpenCV library to seamlessly process video frames, extract relevant information, and annotate objects with bounding boxes.

**YOLO Integration:**
The YOLO model, specifically YOLOv3, is integrated for accurate and efficient object detection. The configuration files and weights are included for ease of use.

**Pre-Annotated Output:**
 The output video is pre-annotated with bounding boxes around detected objects, enabling easy visualization of the model's performance.

## Required Input Files:
1. **YOLOv3 Weights:** Download the YOLOv3 weights file from the official YOLO website or repository and save it as "yolov3.weights".
2. **YOLOv3 Configuration File:** Obtain the YOLOv3 configuration file (yolov3.cfg) from the YOLO repository and save it as "yolov3.cfg".
3. **COCO Names File:** Download the COCO names file (coco.names) from the COCO dataset website and save it as "coco.names".
4. **Video File:** Provide the input video file in a common format (e.g., MP4) and update the file name in the code (replace "production_id_4791196.mp4" with your video file).

The below link will take you to the "YOLO: Real-Time Object Detection" webpage, you can download the yolov3.weights and yolov3.cfg file:
https://pjreddie.com/darknet/yolo/
 
I got my video files from the client, however, if you are learning you can get similar videos from the web. One such website that I like: https://www.pexels.com/search/videos/pedestrians/

## The links below will lead to videos that show the footage both before and after annotations:

1. https://youtu.be/kmZ-NZzmhMY (Not yet annotated)
2. https://youtu.be/Zlq10-vJgm0 (Not yet annotated)
3. https://youtu.be/9ASyzAXzn7Y (annotated)
4. https://youtu.be/UNazEjO-pwc (annotated)

## Required Packages:
1. **OpenCV (cv2):** OpenCV is a crucial library for computer vision tasks. Install it using:
   ```bash
   pip install opencv-python
   
2. **NumPy (np):**  NumPy is used for numerical operations. Install it using:
   ```bash
   pip install numpy

## Installation Steps:
1. Download the YOLOv3 weights, configuration file, and COCO names file.
2. Install the required packages using the provided commands.
3. Place the downloaded files in the same directory as your code file.
4. Replace the video file name in the code with your specific video file.
5. Run the code, and the output will be saved as "annotated.avi."
