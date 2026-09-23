# FluoSense - Microplastic Detection System

An AI-enhanced fluorescence-based system designed for the detection and quantification of microplastics in water samples.

## Overview

Microplastic contamination in aquatic environments is an environmental concern. Traditional detection methods can be expensive, time-consuming, and dependent on laboratory facilities.

FluoSense proposes a low-cost and portable approach that combines fluorescence imaging, artificial intelligence, and IoT-based monitoring for microplastic detection.

Approximately 50 mL of a water sample is treated with Nile Red dye and introduced into a transparent chamber. Blue LED illumination causes stained microplastics to emit fluorescence, which is captured using a camera with optical filters.

The captured images are proposed to be processed using a Raspberry Pi and a Convolutional Neural Network (CNN) to identify, count, and measure microplastic particles. The processed information can then be transmitted to an IoT dashboard for visualization and data logging.

## Proposed System

The proposed FluoSense system combines sample preparation, fluorescence imaging, AI-based image analysis, and IoT visualization into a single workflow.

Water Sample → Nile Red Staining → Fluorescence Chamber → Blue LED Illumination → Camera Capture → Raspberry Pi + CNN → Microplastic Detection → IoT Dashboard

## System Workflow

The proposed system follows a step-by-step process for microplastic detection. A water sample is collected and treated with Nile Red dye before being introduced into a transparent chamber. Blue LED illumination is used to excite the stained particles, and a camera captures the resulting fluorescence. The captured image is then processed using a Raspberry Pi for analysis, and the detected results can be visualized through a monitoring dashboard.

![FluoSense System Workflow](microplastic-detection-workflow.png)

## Technical Approach

1. Collect approximately 50 mL of water sample.
2. Treat the sample with Nile Red dye.
3. Introduce the treated sample into a transparent chamber.
4. Illuminate the chamber using blue LED light.
5. Capture fluorescent particles using a camera with optical filters.
6. Process the captured images using a Raspberry Pi.
7. Apply a CNN model for identifying, counting, and measuring microplastic particles.
8. Send the processed information to an IoT dashboard for visualization and historical logging.

## Fluorescence Imaging

The fluorescence image shows bright fluorescent particles against a dark background after the sample is treated with Nile Red dye and exposed to suitable illumination. This type of image provides the visual input proposed for further computer-vision-based analysis and microplastic detection.

![Microplastic Fluorescence Image](microplastic-fluorescence-image.png)

## Key Components

- Raspberry Pi
- High-resolution Camera
- Blue LED
- Optical Filters
- Transparent Sample Chamber
- Nile Red Dye
- IoT Dashboard
- CNN-based Image Processing

## Technologies Used

- Raspberry Pi
- Python
- Computer Vision
- Convolutional Neural Network (CNN)
- Fluorescence Imaging
- IoT
- Image Processing

## Key Features

- Fluorescence-based microplastic detection
- AI-assisted image analysis
- Particle counting and measurement
- Portable system concept
- Real-time data visualization
- IoT-based data logging

## Applications

- River and lake water monitoring
- Environmental research
- Aquatic pollution monitoring
- Field-based microplastic analysis
- Environmental monitoring

## Advantages

- Low-cost system concept
- Portable design
- AI-assisted detection
- Real-time analysis
- IoT-enabled monitoring
- Suitable for field deployment

## Future Scope

- Improved CNN-based classification
- Detection of different types of microplastics
- Improved particle-size analysis
- Cloud-based data storage
- Mobile application integration
- Large-scale environmental monitoring

## Project Status

Proposed / Concept Development

The project presents a proposed AI-enhanced fluorescence system combining low-cost hardware, computer vision, CNN-based analysis, and IoT monitoring for microplastic detection.
