# MachineLearningImageRecognition

An iOS demo app that classifies images from the photo library using **Core ML** and **Vision**.  
It loads a `MobileNetV2` model, runs a `VNCoreMLRequest`, and shows the top prediction with confidence.

## Features
- Pick an image from the Photos library
- Run on‑device classification with Vision + Core ML
- Display top‑1 label and confidence

## Setup
1. **Clone & open**
   ```bash
   git clone https://github.com/zelihainan/MachineLearningImageRecognition.git
   open MachineLearningImageRecognition.xcodeproj
   ```
2. **Build & run on a device or simulator.**
