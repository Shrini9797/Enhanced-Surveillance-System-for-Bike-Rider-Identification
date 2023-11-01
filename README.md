# Enhanced Surveillance System for Bike Rider Identification
![image](https://github.com/Shrini9797/Enhanced-Surveillance-System-for-Bike-Rider-Identification/assets/143311077/2eebe6d5-5aaf-4ccf-a540-c8d6cd77d4c0)

video_demo link: https://www.youtube.com/watch?v=gyqZl2y1pWE

## Abstract

Road accidents are a major cause of human deaths, with motorcycle accidents being common and resulting in severe injuries. Helmets serve as a crucial protective measure for motorcyclists. In India, traffic violations related to helmet usage have led to an increase in accidents and fatalities. To address this issue, an automated surveillance system is proposed to detect bike riders without helmets, capture their license plate information, and generate e-challans. This system aims to enhance road safety and enforce traffic regulations effectively.

## Introduction

The proposed Enhanced Surveillance System for Bike Rider Identification aims to leverage advanced technology to improve road safety and reduce traffic violations. In India, riding a motorcycle without wearing a helmet is a punishable offense. However, manual enforcement of this regulation has limitations, especially regarding the speed at which violations occur. This system introduces an automated approach to detect helmetless bike riders, capture vehicle license plate information, and generate e-challans for offenders.

## System Components

The enhanced surveillance system consists of the following components:

1. **Motorcycle Detection**: Utilizing the YOLOv5 model, the system identifies motorcycles in surveillance videos. This detection occurs at the first level of the system.

2. **Helmet Detection**: After identifying a motorcycle, the system employs the YOLOv5 model again to detect whether the rider is wearing a helmet. This step occurs at the second level.

3. **License Plate Recognition**: Once a helmetless rider is detected, the system extracts the license plate number from the motorcycle using the PlateRecognizer API. This information is used for further processing.

4. **Web Automation**: To obtain additional details of the violator, web automation techniques are applied to gather offender information based on the license plate number.

5. **E-challan Generation**: If a bike rider is found not wearing a helmet, an e-challan is automatically generated. The e-challan includes details of the offender and the traffic violation.

6. **Database Creation**: The system maintains a database with records of identified offenders. This database is essential for accurate tracking and enforcement.

## Benefits and Advantages

- **Enhanced Road Safety**: By automatically detecting helmetless bike riders, the system promotes the use of helmets, reducing the risk of severe injuries and fatalities in accidents.

- **Efficient Enforcement**: Manual enforcement of traffic regulations can be slow and inefficient. This system automates the process, ensuring rapid detection and enforcement of helmet-related violations.

- **Minimized Computation Cost**: The system utilizes machine learning to identify various helmet types with minimal computational overhead.

- **Accurate Offender Identification**: The database created by the system ensures accurate tracking and identification of traffic offenders.

## Conclusion

The Enhanced Surveillance System for Bike Rider Identification is a technological solution to enhance road safety and enforce traffic regulations. By automating the detection of helmetless bike riders and generating e-challans for offenders, this system contributes to the reduction of motorcycle accidents and fatalities. Additionally, it provides an efficient means of ensuring compliance with helmet-related traffic regulations.

This system can be a valuable addition to traffic management and safety initiatives, providing a safer environment for both motorcyclists and other road users.
