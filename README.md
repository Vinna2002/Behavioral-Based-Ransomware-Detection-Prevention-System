RansomGuardian - Final Year Project
=======================================

Project Title:
---------------
RansomwareDetector - A Behavior-Based Ransomware Detection and Prevention System for Windows Environments

Author:
-------
Vinnath Hesara
BSc (Hons) in Computer Security

Project Description:
--------------------
RansomwareDetector is a Windows-based application designed to detect and prevent ransomware attacks using behavior analysis techniques. It monitors files in real time, calculates entropy to detect suspicious encryption activity, and responds automatically by backing up files, terminating processes, and quarantining threats.

Key Features:
-------------
- Real-time monitoring of selected folders
- Entropy-based file encryption detection
- Automatic backup of files before modification
- Quarantine system for suspicious files
- Process monitoring and termination
- User-configurable settings (paths, thresholds, auto-mitigation)
- Visual activity logs and chart analytics through GUI

System Requirements:
--------------------
- Operating System: Windows 10 or higher (64-bit recommended)
- .NET Framework: Version 4.7.2 or above
- Approx. Disk Space Required: ~100MB

Installation Instructions:
--------------------------
1. Locate and run the setup file: `RansomwareDetectorSetup.exe`.
2. Follow the on-screen installation instructions.
3. After installation, launch the application from the desktop/start menu.

Usage Instructions:
-------------------
1. Open the application after installation.
2. Go to **Settings** to configure:
   - Monitor path (folder to watch for ransomware activity)
   - Quarantine path
   - Backup path
   - Entropy threshold
   - Enable/disable automatic mitigation
3. The application will run in the background, monitoring for threats.
4. Check the **Activity Log** tab to view events, backups, and quarantined items.

Project Folder Structure:
-------------------------
RansomwareDetector/
│
├── Setup/                         -> Published installer files
│   └── RansomwareDetectorSetup.exe
├── SourceCode/                    -> Complete Visual Studio project
│   ├── RansomwareDetector.sln
│   └── (All .cs and resource files)
├── Documentation/
│   └── FinalReport.pdf
│   └── UserGuide.pdf
├── README.txt                     -> This file

Note:
-----
This application is developed as a final year project and is intended for academic use only. It is not certified for production or enterprise deployment.

Contact:
--------
Vinnath Hesara  
Final Year Undergraduate - BSc (Hons) in Computer Security  
vinnathgun@gmail.com
