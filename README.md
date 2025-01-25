# AI-Brain-MRI-Segementation

A deep learning model for automated brain MRI segmentation using Convolutional Neural Networks. This model can detect and segment brain tumors, lesions, and analyze white/gray matter boundaries.

## Features

- Automated segmentation of brain MRI scans
- Multi-class tissue classification
- Real-time visualization of segmentation results
- Custom CNN architecture optimized for medical imaging
- Data augmentation specific to MRI processing
- Support for common medical image formats (.nii, .dcm)

## Key Applications

- Tumor detection and segmentation
- White/gray matter boundary analysis
- Lesion identification
- Brain structure analysis
- Medical research and diagnostics

## Requirements

- Python 3.8+
- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-image
- scikit-learn

## Installation

```bash
git clone https://github.com/yourusername/brain-mri-segmentation.git
cd brain-mri-segmentation
pip install -r requirements.txt
```

Folder:
BrainMRI/
├── training/
│   ├── images/
│   │   ├── image1.nii
│   │   └── image2.nii
│   └── masks/
│       ├── mask1.nii
│       └── mask2.nii
└── mri_results/

mkdir -p BrainMRI/training/images
mkdir -p BrainMRI/training/masks
mkdir -p mri_results

run it:
python brain_mri_cnn.py

Model Architecture
Input Layer: 256x256x1 (grayscale MRI slices)
Multiple convolutional layers with increasing then decreasing filters
ReLU activation functions
Specialized left and right convolutional layers
Output Layer: Segmentation mask
Results
The model generates:

Segmentation masks
Visualization plots showing:
Original MRI slice
Ground truth segmentation
Predicted segmentation
Training progress metrics
Performance Metrics
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
Real-time visualization every 2 epochs
Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
MIT License - see LICENSE.md

Citation
If you use this code in your research, please talk to me before.


