# SeoulRestaurant
Code for learning CNN-based model for dicriminating buildings with restaurant in residential area of Seoul, Korea

# System Configuration
| Model parameter | Configuration |
| --------------- | -------------- |
| Model architecture | CNN (Mobilenet-64) |
| Loss function | Cross entropy loss |
| Batch size | 256 |
| Size of input image | (2,64,64) |
| Kernel size | 3 |
| Number of convolutional layers | 14 |
| Number of cells in flattened layer | 1024 |
| Number of metadata combined | 9 |
| Layers in metadata layers | (9,200,200) |
| Data augmentation method | Image: Mirror, Rotation (90º), Gaussian Noise; Metadata: Dropout (0.50) |
| Number of sets in augmented data | 4 |
| Epochs | 100 |
| Class weights used | 1:14.65 |

| Software specification | Specification |
| -------------- | ------------- |
| OS | Windows 10 Home 21H2 Build 19044.2604 |
| IDE | Visual Studio Code 1.76.1 |
| Python | 3.7.2 |
| PyTorch | 1.13.1 |
| Logistic regression model | statsmodel 0.9.0 |

| Hardware specification | Specification |
| -------------- | -------------- |
| CPU | AMD Ryzen™ 5 5600X 3.7GHz |
| GPU | NVidia GeForce RTX 3060 12GB |
| RAM | Samsung DDR4 16GB x 2 |
| HDD | Samsung 850 PRO 256GB |

# Remarks
The code is written in .ipynb format.
In the code, the data is prepared and loaded in binary file.
The data used in this study are publicly available on Korea National Spatial Data Infrastructure Portal (NSDI) (http://www.nsdi.go.kr/) and LocalData portal by Korean Ministry of the Interior and Safety (MOIS) (https://www.localdata.go.kr/). The prepared data cannot be publicly shared because of the copyright policy of Korean government.

