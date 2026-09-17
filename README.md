# Magical Newspaper

Magical Newspaper is an augmented reality iOS application built with Swift and ARKit. The app detects predefined newspaper images through the device camera and overlays video content directly onto the recognized image.

## Features

* Detects predefined reference images using ARKit image tracking
* Displays video content on top of the detected physical image
* Tracks the image in real time as the device moves
* Uses SceneKit for rendering AR content
* Uses AVFoundation for video playback

## Technologies

* Swift
* ARKit
* SceneKit
* AVFoundation
* Xcode

## How It Works

The application uses `ARImageTrackingConfiguration` to recognize images stored in the AR resource group.

When a reference image is detected, the app creates a SceneKit node positioned over the image and uses an `AVPlayer` to play video content directly on the detected surface.

## Project Structure

* `ARImageTrackingConfiguration` — handles image tracking
* `ARReferenceImage` — defines the images that can be recognized
* `SCNNode` — displays content in the AR scene
* `AVPlayer` — manages video playback

## Requirements

* iPhone or iPad with ARKit support
* Xcode
* iOS device with camera access

## Running the Project

1. Clone the repository.
2. Open the project in Xcode.
3. Make sure the reference images are included in the AR Resources asset group.
4. Add the required video files to the project.
5. Connect an ARKit-compatible iOS device.
6. Build and run the application.
7. Point the camera at one of the predefined reference images.

## What I Learned

This project helped me gain hands-on experience with:

* Augmented reality development on iOS
* ARKit image tracking
* SceneKit nodes and positioning
* Integrating video content into AR experiences
* Working with multimedia using AVFoundation

## Author

**Can Şar**

Computer Science Student
Binghamton University

