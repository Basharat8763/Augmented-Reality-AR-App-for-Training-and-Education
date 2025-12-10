Augmented Reality (AR) App for Training and Education
Project Details

Project-Based Learning (PBL-2)
Semester: 4th | Session: 2023–24
Duration: 03 Jan 2024 – 18 Apr 2024
Developed By: Basharat Hassan (2022521926)
Institution: Sharda University, Greater Noida

Overview

This project is an interactive, marker-based Augmented Reality (AR) application built to enhance training and education through immersive 3D visualizations.
Using Unity, ARCore, Vuforia, and custom-designed 3D models created in Blender, the application projects detailed 3D objects such as the sun, boat, sea, car, house, and airplane when the camera detects predefined image markers.

The application also features animations, voice-over explanations, and background audio, creating an engaging and realistic learning environment for users.
It is packaged as a fully functional Android APK that runs smoothly on AR-supported devices.

Objectives

Enhance learning through interactive AR-based visualizations.

Provide an intuitive, user-friendly interface for students and trainees.

Demonstrate real-time marker-based AR object projection.

Leverage 3D assets, animation, and audio for engaging educational experiences.

Showcase ARCore and Vuforia integration within Unity.

Features

Marker-based AR detection using Vuforia/ARCore.

Projection of high-quality 3D models when camera recognizes image targets.

Multiple interactive models including:

Sun

Boat and ocean environment

Car with movement animation

House model

Airplane with flight animation

Integrated voice narration for explanation of each model.

Background music for enhanced immersion.

Smooth, optimized performance on Android devices.

Fully packaged as an APK with a simple UI and instructions.

Tech Stack
Category	Tools / Technologies
Game Engine	Unity
AR SDKs	ARCore, Vuforia, ARToolKit
Programming Language	C#
3D Modeling	Blender
IDE	Visual Studio / VS Code
Version Control	Git
Platform	Android (APK)

Hardware Used:
AR-supported Android phone, GPU-enabled development system, RAM/Storage as required for Unity and Blender.

Project Structure
ar-training-education-app/
├── Assets/
│   ├── Scripts/              # C# scripts (marker detection, UI, animations)
│   ├── Models/               # Blender 3D models
│   ├── Audio/                # Voice-over and background music
│   ├── Animations/           # AR animations
│   └── Vuforia/              # Image targets and AR markers
├── Scenes/
│   └── MainScene.unity
├── ProjectSettings/
├── Packages/
└── README.md

How It Works

The user opens the AR application on their Android device.

The camera scans printed image markers.

When the marker matches the stored target in Vuforia, the app:

Loads the associated 3D model

Plays predefined animations

Adds voice-over explanation and background music

The model appears fixed in the real world, allowing the user to walk around and explore it from all angles.

Multiple models can be viewed by changing markers.

Results

Successfully deployed as a complete AR Android application (APK).

High-quality 3D models with smooth animations.

Accurate marker detection with minimal latency.

Effective use of AR for visual learning and training.

Demonstrated the ability to integrate audio, animation, and ARCore/Vuforia workflows within Unity.

(Screenshots and demo video will be added soon.)

Future Improvements

Add gesture-based interaction with 3D models.

Expand the number of educational modules and models.

Introduce quizzes and learning assessments inside the app.

Cloud-based content updates for new AR lessons.

Port to iOS using ARKit.

Improve UI with multiple learning pathways.

License

This project is intended for educational and research use.
