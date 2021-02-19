# Intel® IoT Template Repository

This repository contains recommended requirements for projects hosted in the Intel IoT GitHub organization. This 
includes naming convention, file directory and other recommendations. 

*Note: Some recommendations may not be applicable for your project.*

<img src="https://www.intel.com/content/dam/www/public/us/en/images/photography/rwd/ai-in-production-join-us-rwd.png" alt="Illustration" width="600"/>

*An image or gif illustrating the project* 

## File Directory
```
.
├── build                   # Compiled files (alternatively `dist`)
├── src                     # Source files (alternatively `lib` or `app`)
├── test                    # Automated tests (alternatively `spec` or `tests`)
│   ├── benchmarks          # Load and stress tests
│   ├── integration         # End-to-end, integration tests (alternatively `e2e`)
│   └── unit                # Unit tests
├── tools                   # Tools and utilities
├── LICENSE
└── README.md
```

## Table of Contents
* [Description](#description)
* [How It Works](#how-it-works)
* [Requirements](#requirements)
* [Pre-Trained Models](#pre-trained-models)
* [Setup](#setup)
* [Learn More](#learn-more)

## Description
Welcome to our instructional guide for {project name}.

This repo uses {technologies} for {value proposition} on Intel® {Hardware} systems, improving {benefit 1} and 
{benefit 2}.

## How It Works

<img src="./images/HL_Reference_Arch.png" alt="Reference Architecture" width="600"/>

*Reference Architecture*

## Requirements

### Operating System
* Ubuntu 18.04

### Hardware
* [Intel® Core i3](https://software.intel.com/content/www/us/en/develop/topics/iot/edge-solutions/hardware.html?query=core&currentPage=1)

### Software
* [Intel® Distribution of OpenVINO™ Toolkit](https://software.intel.com/content/www/us/en/develop/tools/openvino-toolkit.html)

### Dependencies
* Video file / Camera
* Text file
* Audio file / Microphone

## Pre-Trained Model(s)
This project uses a number of [optimized pre-trained models](https://software.intel.com/content/www/us/en/develop/tools/openvino-toolkit/pretrained-models.html) that are accessible via the Intel® Distribution of 
OpenVINO™ Toolkit Model Downloader] tool:

### Object Detection
| Network       |
| --------------|
| [MobileNet](https://docs.openvinotoolkit.org/latest/omz_models_intel_face_detection_adas_0001_description_face_detection_adas_0001.html)       |

### Object Recognition
| Network       |
| --------------|
| [ResNet-50](https://docs.openvinotoolkit.org/latest/omz_models_intel_person_attributes_recognition_crossroad_0234_description_person_attributes_recognition_crossroad_0234.html)       |

...

## Setup
### Step 1 -
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Step 2 -
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Step 3 -
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Step n -
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

## Learn More

* [Intel® Edge Software Hub](https://software.intel.com/content/www/us/en/develop/topics/iot/edge-solutions.html) - Download prevalidated software to learn, develop, and test your solutions for the edge.


* [Intel® DevCloud for the Edge](https://software.intel.com/content/www/us/en/develop/tools/devcloud/edge.html) - 
  Innovate at the edge with a cloud-hosted Intel® hardware and software platform specifically designed for developers.


* [Intel® IoT Zone](https://software.intel.com/content/www/us/en/develop/topics/iot.html) - Discover Intel® 
  software tools, documentation, certification programs as well as on-demand and upcoming Live training sessions
