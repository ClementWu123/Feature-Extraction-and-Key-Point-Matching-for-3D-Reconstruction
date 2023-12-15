# CIS581-Final-Project

# Project Name

Feature Extraction and Key Point Matching for 3D Reconstruction

# Abstract

In computer vision, graphics, and robotics, reconstructing 3D scenes from 2D photographs has emerged as a prominent study and application area. To create complex 3D representations, the technique combines data from multiple sources, such as pictures, point clouds, or sensor data. Accuracy and efficiency have been significantly increased by recent advances in computer vision, photogrammetry, and machine learning. In our project, we focused on the application of 3D reconstruction in heritage recovery. Also, we performed camera pose estimation, which is vital in autonomous vehicles, helping to understand the vehicle's relative position relative to the road and surrounding objects. We implemented the SFM (Structure from Motion) Pipeline and conducted experiments by selecting various feature extractors and matchers, combining different methods and measuring the performance of the model compared to the SIFT+KNN Baseline. Our intended method: DISK with LoFTR, performed well on the training data as we obtained a large amount of 3D points and low mean reprojection error. This indicates a favorable balance between feature matching quality and quantity.

## Data

Obtained from Kaggle Competition "Image Matching Challenge 2023" (https://www.kaggle.com/competitions/image-matching-challenge-2023)

## Install Libraries

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all libraries listed in the requirement,
if not, we provided install command in our notebooks.

Required Libraries:

torch>=1.1\
torchvision>=0.3\
numpy\
opencv-python\
tqdm>=4.36.0\
matplotlib\
plotly\
scipy\
h5py\
pycolmap>=0.3.0\
kornia>=0.6.11\
gdown\
lightglue @ git+https://github.com/cvg/LightGlue
\
iglovikov_helper_functions\
check_orientation\
kornia

## Usage

For usage of 3D_library.ipynb and benchmark_experiments.ipynb, refer to the hierarchical localization (https://github.com/cvg/Hierarchical-Localization) for detailed function uses

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
