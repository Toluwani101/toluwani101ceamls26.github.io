---
layout: project
title: About My Project
permalink: /about-my-project.html

subtitle: Human-Computer Interaction & Adaptive Systems
project_title: "Developing Edge AI Applications for Human-Robot Collaboration in LEGO Assembling Operations"

problem: |
  LEGO assembly can be difficult for robots because LEGO pieces are small, colorful, and often mixed together in piles. Many pieces may look similar in shape or color, and some pieces may be partly hidden behind others. For a human, finding the correct brick is usually simple, but for a robotic arm, it requires accurate vision, object detection, and precise movement.

    This project tackles the challenge of helping a robot identify, locate, and eventually pick up a specific LEGO brick from a pile. This matters because it connects artificial intelligence with real-world human-robot collaboration. Instead of only detecting objects on a screen, the system must use computer vision results to support a physical task.

    The gap this project addresses is the connection between object detection and robotic action. YOLO models can detect objects quickly, but the project focuses on applying YOLO to small LEGO pieces, evaluating how well the model performs, and moving toward an edge AI system where a webcam, AI model, and robotic arm can work together in real time.

approach: |
  - Step 1 — Prepare and train the YOLO model with a large LEGO dataset
We will use a dataset of about 2,000 labeled LEGO images. The annotations have been converted from XML format to YOLO .txt format so the dataset can be used for YOLO training. The model will be trained using Ultralytics YOLO, Python, and an NVIDIA GPU running on Linux OS.
  - Step 2 — Evaluate the object detection performance
After training, we will evaluate the model using common YOLO performance metrics such as precision, recall, F1 score, IoU, mAP50, and mAP50-95. This will help us understand which LEGO bricks the model detects accurately and which ones are more difficult to detect because of size, color similarity, lighting, or overlapping pieces.
  - Step 3 — Test the model in a real camera setup
The trained model will be tested using a webcam mounted on a tripod to see how well it detects LEGO pieces in real time. We will compare the model’s predictions with the actual LEGO pieces in the scene and use this testing phase to identify problems such as missed detections, false detections, low confidence scores, or inaccurate bounding boxes.
  - Step 4 — Move toward edge AI and robotic arm integration
The next phase is to connect the detection system to an edge AI setup using tools such as NVIDIA Jetson Developer Kits, OpenCV, NumPy, and ROS2. The goal is to allow the system to capture images from a webcam, detect LEGO pieces using YOLO, and eventually send useful position information to a robotic arm such as the Trossen Robotics WidowX 250 S.
  - Step 5 — Develop and test robotic interaction functions
Once the detection model performs well, we will work toward functions such as converting camera coordinates to robotic arm coordinates, sorting LEGO bricks by color and type, and controlling the robot arm to pick and move specific pieces. These functions will help turn the AI model from a detection tool into part of a working human-robot collaboration system.
  - Step 6 — Communicate the results
We will document the process through daily reports, research writing, presentation slides, and a final research symposium presentation. The results will include the model’s performance, lessons learned from testing, limitations of the system, and possible next steps for improving LEGO detection and robotic picking.

outcome: |
  What do you expect to produce by the end of the program? A working prototype?
  A research poster? A short paper? Describe the artifacts and what you hope
  others will be able to do with them.

final_report_url: https://example.com/your-report.pdf

grad_mentor:
  name: Derrick Mirindi
  linkedin: https://www.linkedin.com/in/derrick-mirindi-18b538b8/

faculty_mentor:
  name: Dr. Yuhan Jiang
  linkedin: https://www.linkedin.com/in/yuhan-jiang-aa9097b9/?skipRedirect=true
---
