# POST-TOOLS

A collection of macOS utilities, scripts, and colour tools developed to streamline professional post-production workflows.

Most of these projects began as internal tools built to solve real-world challenges encountered during feature film, television, and commercial post-production. Some were developed entirely by me, while others were created in collaboration with software developers and, more recently, with the assistance of AI-powered development tools to accelerate prototyping and implementation.

The philosophy behind this repository is simple:

* Automate repetitive tasks
* Reduce friction in everyday workflows
* Improve consistency across projects
* Save time for editors, colourists, DITs, and post-production teams

I'm making these tools freely available in the hope they'll be useful to others working in post-production.

Feedback, feature requests, and contributions are always welcome. If you have ideas for improvements or discover a bug, please open an issue or get in touch.

---

# Applications & Tools

## Folder Sync

A lightweight AppleScript utility for synchronising two or more folders.

The application is built around `rsync`, providing fast and reliable folder synchronisation between a source and destination while generating a detailed log file upon completion.

**Ideal for:**

* Backup workflows
* Media synchronisation
* Deliverables
* General file management

---

## File Report

A macOS utility that generates comprehensive reports for every file within a selected folder.

Each report includes:

* File name
* Full file path
* File size
* MD5 checksum

Reports are exported as Excel spreadsheets, making the tool particularly useful for DITs, archive management, media verification, and production deliveries.

---

## Project Structure Script

A simple utility that creates a standardised folder hierarchy for new projects.

Originally developed for colour grading facilities operating across multiple workstations, it ensures every project starts with a consistent directory structure, making remote collaboration and project management significantly easier.

---

## Simple 3D LUT Viewer

A lightweight macOS application for visualising **3D LUTs (.cube)** in an interactive 3D environment.

The application displays LUTs as point clouds inside a wireframe colour cube, allowing users to better understand how different LUTs transform colour.

### Features

* Load multiple LUTs simultaneously
* Interactive 3D rotation
* Zoom using trackpad or mouse wheel
* Fast and responsive rendering
* Great for comparing LUT behaviour

Designed for colourists, cinematographers, DITs, VFX artists, and anyone working with colour pipelines.

---

## EDL/XML Timeline Inspector

A powerful macOS application designed for video editors, assistant editors, colourists, and post-production professionals.

Load and inspect **EDL** and **Final Cut XML** timeline files with an intuitive interface that makes navigating complex timelines fast and efficient.

### Features

* Drag & Drop support
* Colour-coded event visualisation
* Accurate timecode conversion
* Detailed inspection panels
* Frame-rate conversion
* Comment editing
* CSV export
* EDL export
* Support for a wide range of XML formats

### Version 1.5

* Bug fixes for CSV export
* Added EDL export support
* Added the ability to remove unwanted events
* Expanded compatibility with additional XML formats
* Improved user interface

---

## Video File Naming Tool

A lightweight macOS utility that generates clean, consistent, industry-standard video filenames.

Instead of manually typing delivery filenames, the application guides users through a structured series of prompts covering:

* Resolution
* Mastering codec
* Colour space
* HDR / SDR
* Frame rate
* Audio configuration
* Version number
* Delivery date

The completed filename can be copied directly to the clipboard, reducing human error and ensuring consistent delivery naming conventions.

---

## LAB-TOOLS (DCTL)

A DCTL designed for ACEScct that introduces a perceptually inspired LAB-style control layer for intuitive colour manipulation.

Rather than relying on traditional gain-based adjustments, the controls are designed to feel more natural while remaining compatible with an ACES scene-referred workflow.

### Controls

**Exposure**

Perceptual lightness adjustment designed to behave naturally inside ACEScct rather than functioning as a simple gain control.

**A Axis**

Shifts colour along the **Red ↔ Cyan** axis.

**B Axis**

Shifts colour along the **Blue ↔ Yellow** axis.

**Selective Colour Boost**

Enhances saturation primarily along the blue-yellow axis, enriching skies, warm tones, and natural colour separation while avoiding excessive global saturation.

---

## Future Development

This repository will continue to grow as new tools are developed for production use.

Most future additions will focus on:

* Colour pipeline utilities
* DaVinci Resolve workflow tools
* DCTL development
* Automation scripts
* Data management
* Quality control
* Editorial and finishing utilities

If you find these tools useful, consider starring the repository, sharing feedback, or contributing ideas for future improvements.
