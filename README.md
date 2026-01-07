# XR Development Tutorials (Task 1 & Task 2)

This repository contains the source code and build files for the introductory XR tutorials, focusing on **Google Cardboard (VR)** and **AR Development Environment** setup.

---

## 📥 Downloads

### 📱 Task 1: Google Cardboard VR (iOS Build)
[Download Task 1 Build Files](https://drive.google.com/file/d/1ux8DodIMCHx84ChA9x28POG7Q19j5tKx/view?usp=sharing)
* **Description:** A VR demo built for iOS using the Google Cardboard XR Plugin.
* **Instructions:** Unzip the folder on a Mac, open the `.xcodeproj` file in Xcode, and deploy to your iPhone.

### 📱 Task 2: AR Environment Setup (iOS Build)
[Download Task 2 Build Files](https://drive.google.com/file/d/1rohoMCEZxXS9NBkVlh01yRoYaeefWm2b/view?usp=sharing)
* **Description:** A foundational AR project configured for iOS development.
* **Instructions:** Unzip and deploy using Xcode to verify the AR session startup.

---

## 📄 Documentation & Tutorials

### Task 1: Quickstart for Google Cardboard for Unity
**Objective:** Create a VR experience using a mobile phone.

This project follows the official Google guide to implement the "HelloCardboard" demo. Key development steps included:
* **XR Plugin Management:** Installing and configuring the Google Cardboard XR Plugin for Unity.
* **Scene Setup:** Utilizing the demo assets to understand core VR features.
* **Interaction Logic:** Implementing scripts to recenter the head tracker and toggle VR mode on/off programmatically.
* **Platform Configuration:** modifying Player Settings to support iOS deployment (Architecture, Camera Usage, and Bundle Identifiers).

### Task 2: Configure your AR Development Environment
**Objective:** Establish a working pipeline for Augmented Reality development.

This project focuses on the infrastructure required to build AR applications, specifically addressing the dual-machine workflow (Development Computer + Mobile Device). Steps taken:
* **Software Verification:** Ensuring compatible Unity versions and platform-specific modules (iOS Build Support) were installed.
* **Project Configuration:** Setting up a new Unity project with the necessary AR packages (AR Foundation, ARKit/ARCore).
* **Device Connection:** Verifying the connection between the Unity Editor and the physical mobile device for testing and deployment.

---

## 🛠️ How to Open Source Code

To inspect the source code for either task:
1.  Open **Unity Hub**.
2.  Click **Add** and select the specific Task folder (e.g., `Task1_Source`).
3.  Ensure you have the correct Unity Editor version installed.
4.  Open the project to view the `Assets` and settings.
