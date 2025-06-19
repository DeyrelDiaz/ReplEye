# ReplEye: An Open Source Pipeline for Gathering, Analyzing, and Replaying Eye-Tracking Data with MRTK

## About the Pipeline

**ReplEye** is an open-source toolkit for developers and researchers working with the Microsoft Mixed Reality Toolkit (MRTK). It enables the recording, analyzing, and replaying of eye-tracking data from Mixed Reality devices. This toolkit is ideal for prototyping, usability testing, and behavioral research. Sample use cases are provided and ready to run on the Microsoft HoloLens 2 as a standalone Universal Windows Platform (UWP) application.

This toolkit is released under the **MIT License**.

This toolkit was presented as a paper highlighting the toolkit's inspiration, design choices, and structure. If you use any part, or all, of this toolkit for research, we ask that you cite the corresponding paper.

> Diaz, D., Zamanifard, S., Volonte, M., & Duchowski, A. T. (2025). ReplEye: An Open-Source Pipeline for Gathering, Analyzing,
and Replaying Eye-Tracking Data with MRTK. *Extended Reality*


---

## Getting Started

---

---
## Tools

### Capsule Collider Dimensions and Degree of Visual Angle (DVA)

This tool calculates the **real-world dimensions** and **DVA** of each `CapsuleCollider` relative to the Main Camera. This is useful for eye-tracking and behavioral analysis where spatial awareness and visual perception matter.

- Not included in builds (Editor-only)
- Script location: `Assets/Editor/Tools/CapsuleColliderDimensionsAndDVA/`
- Output file: `Assets/Data/ColliderMeasurements/CapsuleColliderDimensionsAndDVA.csv`

### 🔧 How to Use

1. In Unity, select one or more GameObjects with CapsuleColliders.
2. Go to `Tools > Calculate Capsule Collider Dimensions and DVA`.

---

## Updates

**v1.0.0 – Initial public release!**
- Includes sample scenes, data recording, and eye-gaze replay scripts
- Outputs eye-tracking data to CSV files
- Provides R scripts for analyzing and visualizing eye-tracking data

---

## Running the Samples

---

## Used Materials

Please note that this eye tracking pipeline utilizes/ builds upon other toolkits and open-source projects.

- [MRTK 3](https://github.com/MixedRealityToolkit/MixedRealityToolkit-Unity)
- [Microsoft Rocketbox Avatar library](https://github.com/microsoft/Microsoft-Rocketbox)

---

## Contributors

- Deyrel Diaz  
- Samaneh Zamanifard  
- Matias Volonte  
- Andrew T. Duchowski

---

## Want to Contribute?

This project welcomes contributions and suggestions! Your input is appreciated, whether it's bug fixes, feature requests, documentation improvements, or new modules.

To contribute:
1. Fork the repository
2. Create your feature branch:  
   ```bash
   git checkout -b feature/my-feature
3. Commit your changes:
   ```bash
   git commit -m "Add my feature"
5. Push to the branch:
   ```bash
   git push origin feature/my-feature
7. Open a pull request

---
