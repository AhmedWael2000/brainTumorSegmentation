# brainTumorSegmentation
This Jupyter Notebook implements a brain tumor segmentation model utilizing the U-Net architecture with a VGG16 backbone for the encoding part.

# Objective:

The model aims to generate a binary mask for brain tumors in medical images.
# outputs
![image](https://github.com/AhmedWael2000/brainTumorSegmentation/assets/95596511/fc4468d6-fb3b-438e-88a1-b7922c1902d9)

# Evaluation Metrics

We use Intersection over Union (IoU) to assess the similarity between the predicted mask and the ground truth mask.

# Loss Function

Initially, we employed Dice Loss but encountered issues. Therefore, we utilize Mean Squared Error (MSE) for this beta version.

![image](https://github.com/AhmedWael2000/brainTumorSegmentation/assets/95596511/ebfe6378-7b28-4521-898a-ef4a3549346a)

# Additional Information

Dataset:[Brain MRI segmentation]([https://www.google.com](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation)).
Libraries: Specify the programming language and libraries used (e.g., Python, TensorFlow, Keras).
Running the Notebook: If applicable, include instructions on how to run the notebook (e.g., dependencies, environment setup).
# Future Work

Dice Loss: Implement the intended Dice Loss function to address the encountered issues.
Architecture Exploration: Explore alternative architectures for potential improvements.
