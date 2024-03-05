# ted_classificaiton_monai
Use 3-d CNN backbones from MONAI (pytorch implementations) to classify CTs into Yes/No flags (Yes=presence of Thyroid Eye Disease)

1. Use pydicom, VTK/ITK modules to help with pre-processing
2. Train a 3-D CNN (DenseNet121 backbone)
3. Evaluate accuracy
4. Carry out sensitivity analysis using Occlusion Sensitivity 
