# Medicinal Leaf Image Dataset - Binary Masks  

## Overview  

This repository contains a dataset of **binary mask images** of five medicinal plant species:  

- **Annona Muricata**  
- **Cestrum Diurnum**  
- **Nyctanthes Arbor-Tristis**  
- **Ocimum Tenuiflorum**  
- **Psidium Guajava**  

Each image in this dataset represents a **binary mask**, where the ideal leaf is extracted from complex backgrounds using advanced computer vision techniques such as **Mask R-CNN** and **semantic segmentation** models.  

## Dataset Description  

- The dataset consists of pre-processed binary masks of medicinal leaves.  
- The original images were processed using **deep learning-based segmentation models** to remove background noise and isolate the leaf structures.  
- These masks provide a **clean, standardized representation** of medicinal leaves, making them ideal for training **computer vision models** in medicinal plant research.  

## Applications  

This dataset is particularly useful for:  

- **Medicinal Plant Identification:** Training AI models for automated classification and recognition of medicinal leaves.  
- **Feature Extraction:** Studying leaf morphology and vein structures for plant taxonomy research.  
- **Disease Detection:** Analyzing plant health by training models to detect diseases or abnormalities.  
- **Medical and Pharmaceutical Research:** Supporting AI-driven medicinal plant studies and herbal medicine applications.  

## Data Structure  

```plaintext
Medicinal-Leaf-Dataset/  
├── Annona_Muricata/  
│   ├── image_001_mask.png  
│   ├── image_002_mask.png  
│   └── ...  
├── Cestrum_Diurnum/  
│   ├── image_001_mask.png  
│   ├── image_002_mask.png  
│   └── ...  
├── Nyctanthes_Arbor-Tristis/  
│   ├── image_001_mask.png  
│   ├── image_002_mask.png  
│   └── ...  
├── Ocimum_Tenuiflorum/  
│   ├── image_001_mask.png  
│   ├── image_002_mask.png  
│   └── ...  
├── Psidium_Guajava/  
│   ├── image_001_mask.png  
│   ├── image_002_mask.png  
│   └── ...  
└── metadata.csv  # Contains image annotations and metadata  
```
## Citation
If you use this dataset in your research or project, please cite this repository.
