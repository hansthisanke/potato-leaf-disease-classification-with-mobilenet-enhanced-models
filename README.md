# potato-leaf-disease-classification-with-mobilenet-enhanced-models
Enhancing Potato Leaf Disease Classification through MobileNet Variant custom models fine-tuning, transfer learning and data pre-processing techniques.

## Overview
This repository contains the code, experiments on improving potato leaf disease detection using MobileNet fine-tuning, transfer learning and advanced data pre-processing strategies. The project benchmarks MobileNetV1, V2, and V3-Small for real-time performance evaluation and accuracy measures. Furthermore, a comparison between the original MobileNetV1 and the custom fine-tuned models is carried out to highlight the improvements made with the changes on the model architecture. 

## Repository Structure
- `notebooks/` – Jupyter notebooks for training and evaluation
- `images/` – Sample test results and visualizations
- `requirements.txt` – Python dependencies
- `README.md` – Project documentation

## Datasets
- **PlantVillage Open Dataset**  
  Used for model fine-tuning.  
  Contains potato leaf images categorized into:
  - Late blight  
  - Early blight  
  - Healthy leaves  

- **Real-field Imagery Dataset**  
  Used for evaluation under uncontrolled environments.  
  Contains sample potato leaf images collected in real-world conditions (lighting variations, background noise, natural field settings).  
  This dataset was used to validate robustness beyond controlled datasets.

## Installation Guide
Clone the repo and install dependencies:
```bash
git clone https://github.com/hansthisanke/potat-leaf-disease-classification-mobilenet-customs-variants.git
cd potat-leaf-disease-classification-mobilenet-customs-variants
pip install -r requirements.txt

