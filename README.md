# 🧠 Interactive 3D Medical Image Viewer with Slice Navigation and Dynamic Zoom

This Unity-based project provides an interactive 3D medical image viewer that allows MRI technicians and doctors to **explore a volumetric rendering of the human head** using MRI slice images. Users can dynamically adjust cross-sectional slices, move a secondary camera for inspection, zoom into specific areas, and capture high-quality screenshots of the 3D head.

[🔗 GitHub Repository](https://github.com/sreeragss/UnityVolumeRenderingProject)

---

## 📌 Project Overview

The project uses a **fixed main camera** and a **movable secondary camera** to explore a 3D volume-rendered MRI dataset. With real-time slice control and camera zoom features, this viewer offers a powerful tool for visualizing internal anatomical structures.

---

## ✨ Key Features

- ✅ **3D Volume Rendering from 2D MRI Slices**  
- ✅ **Slice Navigation UI**  
- ✅ **Secondary Camera Control**  
- ✅ **Zoom into Internal Regions**  
- ✅ **Screenshot Capture**

---

## 🛠️ Technologies Used

- Unity 3D (version: `6000.1.7f1`)
- C#
- [UnityVolumeRendering](https://github.com/mlavik1/UnityVolumeRendering)
- Unity UI Toolkit
- Mouse-controlled camera system
- Screenshot API

---

## 📥 How to Open and Use the Project

1. **Download the Project**  
   Clone or download this repository and extract the ZIP file to your preferred location.

2. **Open in Unity Hub**
   - Launch Unity Hub
   - Click `Add > Add project from disk`
   - Select the extracted folder location
   - You will now see the project listed in Unity Hub

3. **Open in Unity Editor**
   - Click on the project to open it in Unity Editor  
   _(Make sure Unity version `6000.1.7f1` is installed)_

4. **View the 3D Volume**
   - In the Project panel, go to: `Assets > test1`
   - Double-click `test1` to load the scene

5. **Play the Scene**
   - Click the **Play ▶️** button to enter Game mode

6. **Control the Cameras**
   - 🎥 Main Camera: Fixed view of the 3D head  
   - 🎮 Secondary Camera:
     - Right-click + drag mouse: rotate around the head
     - Mouse scroll: zoom in/out
     - UI buttons: switch cross-sectional plane (XY, XZ, YZ)

7. **Capture Screenshot**
   - Press `S` during Game mode  
   - Screenshot will be saved to the local folder

---

## 📸 Example Screenshots

> Screenshots taken from the secondary camera in Game mode.

![Game_Play_mode_unity](Screenshots/Game_Play_mode_unity.png)  
![Game_view_Unity](Screenshots/Game_view_Unity.png)  
![Scene_view_unity](Screenshots/Scene_view_unity.png)  
![SecondCam_Zoom_Playmode_unity](Screenshots/SecondCam_Zoom_Playmode_unity.png)  
![SecondCam_imageSaved_playmode_unity](Screenshots/SecondCam_imageSaved_playmode_unity.png)  
![Secondcamera_anglechange_playmode_unity](Screenshots/Secondcamera_anglechange_playmode_unity.png)

---

## 🔮 Future Scope

- 🥽 Direct VR headset support using Unity XR Toolkit  
- 🖊️ Annotation and measurement tools for diagnostic use  
- 🧠 Automatic tissue/region highlighting using machine learning  
- 📁 Support for DICOM file loading and PACS integration  
- 💡 Medical education and training applications  

---

## 📧 Contact

If you would like to contribute, report issues, or collaborate, feel free to reach out via GitHub Issues or Pull Requests.

> Developed with 💙 using Unity to support medical imaging, analysis, and education.
