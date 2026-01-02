
# DEEPLENSE 
This project is a solution for one among the [DEEPLENSE](https://ml4sci.org/gsoc/projects/2025/project_DEEPLENSE.html) problem of GSoC2025.

## Problem1:  ["Foundation Model for Gravitational Lensing"](https://ml4sci.org/gsoc/2025/proposal_DEEPLENSE1.html):
### Task ideas:
- Develop a pre-training strategy for learning robust representations of gravitational lensing data.
- Fine-tune the foundation model for multiple tasks such as classification, super-resolution, and regression.
- Evaluate the model’s performance on different astrophysical datasets and benchmark against traditional methods.

### Solution : Multi_Class Classification
- To classify images into 3 classes, i.e. no substructure, subhalo substructure, and vortex substructure, I have used ResNet18 pretrained model. As the images are greyscale, to make it compatible with data, one more Convolution layer have been added after ResNet pretrained layer . ROC and AUC parameters have been detrmined from the 


## Problem2: ["Gravitational Lens Finding"](https://ml4sci.org/gsoc/2025/proposal_DEEPLENSE4.html)
### Task ideas
- Start with architectures previously explored within the DeepLense project and optimise them for the lens finding task.
- Perform the lens search in the real observational data and analyse the properties of the detected lens candidates.
- Evaluate model performance on different surveys.

### Solution
