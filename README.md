Repository for Software Engineering Tools Final Project



Project Name: LA City Sidewalk Assessment



i.Jira link: https://calstatela-cs3338-finalproject.atlassian.net/jira/core/projects/CP/summary



ii. Formal Objective



The objective of this project is to design and implement an automated sidewalk assessment system that transforms raw LiDAR scans collected by a rover into segmented hazard detection outputs using a U-Net deep learning model. The system must accurately identify cracks, uplifts, surface irregularities, and other sidewalk defects while maintaining a consistent workflow across data collection, preprocessing, model inference, and post-processing.



This project aims to produce a fully documented and reproducible pipeline that supports scalable field data acquisition, standardized data formatting, and reliable segmentation performance. The outcome is a modular and extensible framework that public agencies, engineering teams, or researchers can use to accelerate sidewalk condition analysis, support maintenance planning, and improve infrastructure accessibility.





iii. Project Goals and Why This Software Matters



This project aims to create an automated pipeline that transforms sidewalk LiDAR scans into meaningful hazard detection outputs using a U-Net segmentation model. Manual sidewalk assessment is time-consuming, inconsistent, and often resource-heavy for agencies. By using a low-cost rover platform and automated processing, this system allows faster, repeatable, and scalable evaluation of sidewalk conditions.



The software improves accuracy by leveraging machine learning, standardizes results across different operators, and enables early identification of surface damage or accessibility hazards. This directly supports infrastructure maintenance, ADA compliance, and data-driven decision making for public works departments.



iv. How to Download or Access



1. Clone the following GitHub repositories: 



\*Step 1 - Rover code that controls sensors and motors C++: https://github.com/Jose-APV/boe-rover-cpp
\*Step 2 - Rover ROS code and Remote Controller: https://github.com/Jose-APV/boe-sidewalk-rover

\*Step 3 - Pointcloud2Orthoimage github:\*https://github.com/jyh100/pointcloud2orthoimage/tree/main

\*Step 4 - U-Net Deep Learning Segmentation Github:\* https://github.com/zhixuhao/unet

\*Step 5 - Vertical Displacement Github:\* https://github.com/Jose-APV/boe-step-4-vertical-displacement



2\. Use the preprocessing scripts to convert raw LiDAR data into model-ready input.



3\. Run the U-Net inference script to generate segmentation outputs.



4\. View the results through the post-processing module or designated UI output folder.

