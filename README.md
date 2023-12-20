# home-surveillance-project
This project focuses on Home Surveillance and motion detection using Raspberry Pi and Python to capture images and securely transmit them to Dropbox. Motion detection, involving the identification of changes in an object's position relative to its surroundings, is a key aspect of this initiative. The primary objective is to vigilantly monitor a residence, promptly notifying the homeowner of any unusual activity and storing a backup copy in their Dropbox account.

The proposed solution entails connecting a Raspberry Pi with a Pi camera and establishing an internet connection. Once configured, the entire system is capable of performing comprehensive surveillance tasks. The overarching goal of this project is to safeguard privacy and assets by implementing an intelligent surveillance monitoring system. This system captures images of potential intruders, subsequently notifying the homeowners through their Dropbox accounts upon motion detection triggers.
## Table of contents
[Technological Overview](link)
    [Python](link)
## Technological Overview
### Python

This project employs Python as the main programming language due to its interpretability, high-level nature, and versatility. Python's object-oriented approach and comprehensive standard library make it suitable for projects of various scales. Its seamless integration with Raspberry Pi and support for multiple programming paradigms contribute to the project's clarity and efficiency.

### Image Processing

Image processing is a vital component, enhancing raw images obtained from cameras or sensors. This technique is crucial for detecting undesirable camera shakes and motions, contributing to the overall success of the surveillance system.

### Computer Vision

Computer vision forms the basis for understanding and manipulating images and videos. It is instrumental in self-driving cars, robotics, and photo correction apps, detecting motion through frame segmentation and grayscale conversion.
### OpenCV

OpenCV, an open-source library, plays a pivotal role in computer vision and image processing. Its functionalities include object/feature detection, computational photography, and machine learning, making it essential for this project.

Platform Requirement
IoT Device - Raspberry Pi 3

The project's IoT device is based on Raspberry Pi 3, a single-board computer with Bluetooth and wireless LAN connectivity. It interfaces with a PIR sensor, USB web camera, and a power supply, running on the Raspbian OS.

Software Requirements

    Raspbian OS:
        The Debian-based operating system is the primary OS for Raspberry Pi devices.

    Advanced IP Scanner:
        Fast software for network scanning, essential for detecting and accessing network computers.

    Etcher:
        An open-source utility for writing image files onto storage media, facilitating live SD cards and USB flash drives.

    Python:
        The chosen programming language, preinstalled on Raspbian OS, selected for its power and ease of use.

    MobaXterm:
        An enhanced terminal for Windows, featuring an X11 server and SSH client for remote computing.

    Dropbox:
        A cloud storage service for file synchronization and sharing.

Hardware Requirements

    Raspberry Pi 3 (Model B, 1 GB RAM):
        A powerful single-board computer with quad-core 64-bit CPU, Wi-Fi, and Bluetooth capabilities.

    Ethernet Cable (RJ45):
        Used for wired connections to the Internet, supported by Raspberry Pi 3 Model B.

    Pi Camera Module:
        A portable, lightweight camera supporting Raspberry Pi, crucial for image processing and surveillance.

    Micro SD Card (8 GB):
        A removable flash memory card designed for storing various file types, including images, videos, and software.


