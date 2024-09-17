# Lung AutoSegmentation on 3D HRCT Scans <br />
Autosegmentation of Lungs on 3D HRCT Scans <br />

# Dataset <br />
  - Kaggle Data Science Bowl lung Dataset
# Models Used - <br />
  3D UNET <br />

# Configuration <br />
  - Image Augmentation - Rotation, Translational Shifts, Shear, Zoom, Hz Flip <br />
  - Optimizer- Adam Optimizer <br />
  - LR - Cosine Annealing LR <br />
  - Loss Fn - BCEDICE LOSS at Multiple Output Layers/scales <br />

# Results <br />
Dice Score = 0.97 <br />

![ Alt text ](https://github.com/parth-radonc/lung_seg/blob/main/Results/res.jpg?raw=true) 
