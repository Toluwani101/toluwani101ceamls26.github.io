---
layout: project
title: About My Project
permalink: /about-my-project.html

subtitle: "Human-Computer Interaction & Adaptive Systems"
project_title: "Developing Edge AI Applications for Human-Robot Collaboration in LEGO Assembling Operations"

problem: |
  LEGO assembly can be difficult for robots because LEGO pieces are small, colorful, and often mixed together in piles. Many pieces may look similar in shape or color, and some pieces may be partly hidden behind others.

  This project tackles the challenge of helping a robot identify, locate, and eventually pick up a specific LEGO brick from a pile.

  The gap this project addresses is the connection between object detection and robotic action.

approach: |
  These are the steps below:

  - Step 1 — Prepare and train the YOLO model with a large LEGO dataset
    We will use a dataset of about 2,000 labeled LEGO images. The annotations have been converted from XML format to YOLO .txt format.

  - Step 2 — Evaluate the object detection performance
    After training, we will evaluate the model using precision, recall, F1 score, IoU, mAP50, and mAP50-95.

  - Step 3 — Test the model in a real camera setup
    The trained model will be tested using a webcam mounted on a tripod to see how well it detects LEGO pieces in real time.

  - Step 4 — Move toward edge AI and robotic arm integration
    The next phase is to connect the detection system to an edge AI setup using tools such as NVIDIA Jetson Developer Kits, OpenCV, NumPy, and ROS2.

  - Step 5 — Develop and test robotic interaction functions
    Once the detection model performs well, we will work toward converting camera coordinates to robotic arm coordinates and controlling the robotic arm.

  - Step 6 — Communicate the results
    We will document the process through daily reports, research writing, presentation slides, and a final research symposium presentation.

expected_outcome: |
  By the end of the program, we expect to produce a trained YOLO object detection model that can identify selected LEGO bricks from images or live webcam footage.

  We also expect to produce Python code, a prepared YOLO-format dataset, performance evaluation results, and a list of LEGO brick types that the model can detect with high accuracy versus those that are more challenging.

  The final artifacts will include a research report or short paper, a research poster or presentation, demonstration materials, trained model results, and documented code.

final_report_url: https://example.com/your-report.pdf

grad_mentor:
  name: Derrick Mirindi
  linkedin: https://www.linkedin.com/in/derrick-mirindi-18b538b8/

faculty_mentor:
  name: Dr. Yuhan Jiang
  linkedin: https://www.linkedin.com/in/yuhan-jiang-aa9097b9/?skipRedirect=true
---
