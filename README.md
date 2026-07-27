<h1 align="center">
  <img src="https://raw.githubusercontent.com/Placeholder/Path/To/Your/Icon32.png" alt="FloorEdit Icon" width="32">
  FloorEdit for Revit®
</h1>

<p align="center">
  <strong>Automate tedious floor geometry editing, boolean combinations, and solid-solid cuts.</strong>
</p>

<p align="center">
  <a href="https://apps.autodesk.com/"><img src="https://img.shields.io/badge/Autodesk_App_Store-Available-0696D7?style=flat-square&logo=autodesk" alt="Autodesk App Store"></a>
  <img src="https://img.shields.io/badge/Revit-2027_Supported-blue?style=flat-square" alt="Revit 2027">
  <img src="https://img.shields.io/badge/.NET-WPF_MVVM-512BD4?style=flat-square" alt=".NET WPF">
  <img src="https://img.shields.io/badge/License-MIT-success?style=flat-square" alt="License">
</p>

<p align="center">
  <!-- 🌟 Drop your professional animated GIF here so people immediately see what the tool does! -->
  <img src="https://raw.githubusercontent.com/Placeholder/Path/To/Your/AnimatedDemo.gif" alt="FloorEdit Demo Animation" width="700">
</p>

---

## 📖 Overview

Editing complex floor geometry in Autodesk® Revit® can be a highly repetitive, manual process. **FloorEdit** is a powerful productivity add-in built to automate your most frustrating floor geometry tasks with a single click. 

Whether you are dealing with overlapping boundaries, floors chopped into disconnected pieces by voids, or elements that need to cleanly cut through slabs, FloorEdit eliminates the need to manually redrawn purple sketch lines.

## ✨ Key Features

<table>
  <tr>
    <td width="50%">
      <h3>🤝 Combine Selected</h3>
      <p>Automatically detects overlapping floors of the exact same Type, Level, and Height Offset. Uses Revit's 3D boolean engine to perfectly weld boundaries together into a single, unified floor while preserving all original parameters.</p>
    </td>
    <td width="50%">
      <h3>✂️ Separate Disconnected</h3>
      <p>Have a floor element chopped in half by a shaft, or drawn with multiple disconnected rectangles? This tool instantly extracts the disjointed solids and bakes them into completely independent floor elements with unique sketches.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🧱 Auto-Cut & Unjoin</h3>
      <p>Draw a floor straight through your walls or framing. FloorEdit rapidly scans the 3D spatial index, aggressively severs conflicting geometry joins, and applies perfect solid-solid cuts to all intersecting elements.</p>
    </td>
    <td width="50%">
      <h3>🎯 Smart Selection Scopes</h3>
      <p>Filter your actions by Active View or Entire Project. Target all floors, match multiple instances by Type, or use the rapid-fire manual toggle selection tool to instantly gather specific elements.</p>
    </td>
  </tr>
</table>

## 🚀 Usage

1. Navigate to the **Add-ins** tab and click the **FloorEdit** icon to launch the tool window.
2. Under **Selection Scope**, choose your target area (`Active View` or `Entire Project`).
3. Select your gathering method:
   * **All:** Targets every floor in the chosen scope.
   * **Type:** Click sample floors to grab all identical floor types.
   * **Select:** Rapid-fire click specific floors. Press <kbd>ESC</kbd> to finish selecting.
4. Under **Action**, select `Combine Selected`, `Separate Floors`, or `Unjoin & Cut`.
5. Click **Apply**. The tool processes the geometry in the background and provides a success summary.
