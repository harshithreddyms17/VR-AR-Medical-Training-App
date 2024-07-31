# VR/AR Medical Training Application

## Overview

The VR/AR Medical Training Application aims to revolutionize medical training by leveraging augmented reality (AR) and virtual reality (VR) technologies. This application provides immersive and interactive experiences that enhance learning, skill development, and patient care for healthcare professionals.

The project compiles various medical procedures into AR and VR environments using Unreal Engine and Unity. It includes interactive 3D models, animations, and textures to simulate specific medical scenarios such as CT scans, CPR training, and regular health check-ups.

## Augmented Reality in Medical Training

Augmented reality offers significant benefits in medical training, including:

- **Anatomy Education**: Interactive 3D models of anatomical structures allow medical students and trainees to visualize and explore complex anatomy.
- **Surgical Training**: AR simulates surgical procedures, offering real-time guidance and data overlays to improve precision and decision-making.
- **Patient Simulations**: AR creates realistic patient scenarios for trainees to practice diagnostic and treatment procedures in a controlled environment.
- **Medical Imaging Interpretation**: AR enhances the interpretation of medical imaging, providing additional information and 3D reconstructions.

## Virtual Reality in Medical Training

Virtual reality provides realistic simulations for various medical training scenarios, such as:

- **Surgical Simulation**: VR allows trainees to practice complex surgical procedures using haptic feedback and virtual instruments.
- **Procedural Training**: VR offers a realistic environment for practicing procedures like intubation, catheterization, and ultrasound-guided interventions.
- **Anatomical Visualization**: Detailed 3D models help trainees explore and understand complex anatomy.
- **Patient Interaction and Communication**: VR simulates realistic patient interactions, improving communication and interpersonal skills.
- **Medical Imaging Interpretation**: VR enhances understanding of medical images, aiding in diagnostic accuracy.


## System Configuration

- **Laptop**: OMEN by HP Gaming Laptop 16-n0xxx
- **Processor**: AMD Ryzen 7 6800H with Radeon Graphics 3.20 GHz
- **RAM**: 16 GB
- **System Type**: 64-bit operating system, x64-based processor

## Implementation

### Technology Stack

- **Unreal Engine 5.0.3**: A powerful game development engine by Epic Games, used for high-quality interactive experiences.
- **Unity 2022.3.1f1**: A versatile game development engine with a wide range of tools and features.
- **Blender 3.5**: A 3D creation suite for modeling, animation, rendering, and more.
- **Android Studio 4.0 & 4.2 Electric Eel**: IDEs for Android app development.

### Unity Projects

#### First-Person Perspective Based Model

This Unity application features a hospital environment with interactive medical procedures. Key elements include:

- **Reception, Operation Theatre, General Ward**: Built or imported assets, rigged animations, and interactive elements.
- **CT Scan**: Provides visual aid for CPR administration, with animations triggered by keyboard input.
- **Sonogram**: Simulates ultrasound operation with interactive elements.
- **Weighing Machine and Thermometer Animations**: Interactive tasks demonstrating medical equipment use.

### Unreal Projects

#### Augmented Reality CPR Animation

A consultation room extracted from Sketchfab with a CPR animation built in Blender. The AR session is triggered by scanning a candidate image, displaying the animation in real-time.

#### Instrument Selection

Allows users to choose between a syringe, mask, and dropper, with each instrument's appearance triggered by scanning specific book covers.

#### Virtual Reality

A VR room featuring a CT scan animation. The application, packaged for Oculus, includes images of CT scans due to technical constraints.

### Mini-Project

An AR project replicating the solar system, featuring animated planets and celestial bodies. The UI displays planet names upon interaction, providing an educational experience.

## Flutter Application

A mobile application with frontend in Flutter and backend in Firebase. It includes:

- **Phone Authentication**: Secure sign-in using email, password, or SMS verification.


## References

1. Adobe Systems Incorporated. (2021). Mixamo. Adobe Inc.
2. Unity Technologies. (2021). [AR Overview](https://docs.unity3d.com/Manual/AROverview.html). Unity Documentation.
3. Epic Games, Inc. (2021). [AR Overview](https://docs.unrealengine.com/4.26/en-US/SharingAndReleasing/XRDevelopment/AR/HandheldAR/AROverview/). Unreal Engine.
4. EC_UnrealEngineTutorial. (2021, September 15). [Introduction to Unreal Engine](https://www.youtube.com/watch?v=ABC123). YouTube.
5. Unity Technologies. (2021). [VR Overview](https://docs.unity3d.com/Manual/VROverview.html). Unity Documentation.
6. Flutter. (2021). [Get Started: Install on Windows](https://docs.flutter.dev/get-started/install/windows). Flutter Documentation.

