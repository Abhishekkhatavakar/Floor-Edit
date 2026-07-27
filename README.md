# 🏗️ FloorEdit for Revit

![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![Target](https://img.shields.io/badge/Target-Autodesk_Revit-0696D7?logo=autodesk)
![License](https://img.shields.io/badge/License-Proprietary-red)

**FloorEdit** is a premium, productivity-boosting add-in designed to automate your most frustrating floor geometry tasks in **Autodesk Revit**. 

Built with a clean, native WPF interface, it features a robust 3D boolean geometry engine that instantly combines overlapping boundaries, separates disjointed solids, and automates solid-solid cuts—saving hours of repetitive manual sketch editing.

---

## ✨ Key Features

* **3D Boolean Engine:** Extrudes, welds, and rebuilds flat profiles natively using Revit's core geometry engine.
* **Smart Parameter Retention:** Automatically preserves original Height Offsets and Structural Usage parameters when modifying or rebuilding floors.
* **Aggressive Unjoin Logic:** Seamlessly severs conflicting geometry joins (even between identical materials) before forcing perfect solid-solid cuts.
* **Instant Visual Feedback:** Live element highlighting during continuous manual selection without freezing the UI thread.
* **Native Revit UI Integration:** Built cleanly into the Revit Ribbon with high-resolution iconography and full F1 Contextual Help support.

## 🧱 Supported Actions

Target your workflow with 4 powerful geometry and selection tools:
* **Combine Selected:** Merges overlapping floors of the exact same Type, Level, and Offset.
* **Separate Disconnected:** Bakes existing cuts into sketches and rips disjointed solids into entirely independent floor elements.
* **Auto-Cut & Unjoin:** Drives floors cleanly through walls, framing, and intersecting geometry.
* **Smart Selection Scopes:** Target elements by Active View or Entire Project using Type-matching, All, or Continuous Picking.

---

## 📥 Download & Installation

> **Note:** This repository serves as the public release hub for the compiled installers. The core `.NET` source code remains private and proprietary.

1. Navigate to the **[Releases](../../releases/latest)** page on the right side of this repository, or find us on the **Autodesk App Store**.
2. Download the latest `FloorEdit.Setup.msi` file.
3. Run the installer. 
4. The application will automatically place the `.addin` manifest and `.dll` files into your `%AppData%\Autodesk\Revit\Addins` directory so it is natively recognized by Revit on your next startup.

## ⚖️ License & Copyright

**© 2026 AK Tools. All Rights Reserved.**

This software is provided under a proprietary End User License Agreement (EULA). By downloading and installing this software, you agree that you may not decompile, reverse engineer, disassemble, modify, or redistribute the installer or underlying source files without explicit written consent. 

See the attached `LICENSE` file for full terms.

---
*Developed by [Abhishek Khatavakar](https://www.linkedin.com/in/abhishek-khatavakar) at AK Tools.*
