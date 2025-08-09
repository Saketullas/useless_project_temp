<img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


# MAYDAY! MAYDAY! EECHA!🎯


## Basic Details
### Team Name: MAYDAY


### Team Members
- Team Lead: Saket - College Of Engineering Munnar
- Member 1: Saket - College Of Engineering Munnar
- Member 2: Zameel- College Of Engineering Munnar

### Project Description
Its purpose is to detectIts purpose is to detect and track motion live on a screen, identifying everything from flying insects to larger movements.

### The Problem (that doesn't exist)
You know the one. It's the tiny, buzzing menace that drives you crazy, yet vanishes the moment you try to find it. With our app, you can finally turn the tables. We give you a high-tech way to spot, track, and ultimately outsmart that ridiculously small problem.

### The Solution (that nobody asked for)
Ever feel hunted by a single, buzzing bug? MAYDAY is your high-tech revenge. This web app uses your device's camera to spot that tiny menace the moment it moves, giving you a live, digital spotlight on its exact location. No more wild swings—just pure, satisfying victory.

## Technical Details
### Technologies/Components Used
For Software:
- HTML, CSS and JavaScript.
- none.This project uses  vanilla JavaScript.
- none.This code relies on a builtin browser APIs.
- A modern web browser and a code editor.

For Hardware:
- A device with an integrated camera (like a laptop or smartphone) or an external webcam.
- A modern web browser that supports the getUserMedia API for camera access.
- Only a device with a working camera and a web browser.

### Implementation
For Software: The app works by taking a live video feed from the camera and processing it frame-by-frame. It converts each frame to a low-resolution grayscale image and compares it to the previous frame to detect differences, or motion. Any significant movement is identified as a "blob," and a centroid tracker is used to give each blob a unique ID so it can be followed. The app then draws bounding boxes and IDs on a transparent canvas overlay, showing you exactly where the motion is happening in real-time.
# Installation
No installation required .This is a single file web application.

# Run
Simply open the index.html file in any modern web browser.

### Project Documentation
For Software:

# Screenshots (Add at least 3)
![Screenshot1] <img width="1920" height="1080" alt="Screenshot 2025-08-09 082900" src="https://github.com/user-attachments/assets/5cc0cdd3-a166-4279-9da8-a378f7a56063" />


![Screenshot2] <img width="1920" height="1080" alt="Screenshot 2025-08-09 082918" src="https://github.com/user-attachments/assets/38f9d9dd-161e-4630-a7cb-1287e27c5180" />


![Screenshot3]<img width="1920" height="1080" alt="Screenshot 2025-08-09 082947" src="https://github.com/user-attachments/assets/10436190-2810-4a07-890b-5f83cc9e7c0f" />


# Diagrams
Workflow & Architecture Diagram
> This is a software-only project. The workflow follows a pipeline for each video frame:
>  1. Camera Input: The user's device camera provides a live video stream.
>  2. Frame Processing: The video feed is drawn to a low-resolution canvas for a faster analysis.
>  3. Motion Detection: A "frame-difference" algorithm compares the current frame to the previous one to generate a motion mask.
>  4. Object Identification: A "connected components" algorithm finds distinct blobs of motion in the mask.
>  5. Centroid Tracking: A simple tracker assigns a unique ID to each blob and follows its movement over time.
>  6. Overlay Output: The results (bounding boxes and IDs) are drawn onto a transparent canvas overlay on top of the original video stream.
>  7. Caption explaining your workflow: This diagram outlines the core data flow, showing how the app takes a video input, processes it to detect motion, tracks the moving objects, and displays a visual overlay for the user.

### Project Demo
# Video

https://github.com/user-attachments/assets/c98dd0fb-2f8e-4988-aaea-e4ad3fce8fab




# Additional Demos


https://github.com/user-attachments/assets/66f64011-175c-4b14-a647-785698edea36



## Team Contributions
- Saket: Project Concept and Ieation
- Zameel: Development and Implementation


---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)



