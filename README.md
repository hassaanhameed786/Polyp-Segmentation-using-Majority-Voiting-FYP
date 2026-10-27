# Polyp Segmentation using Majority Voting - FYP

## Abstract

Colorectal cancer ranks among the most frequently diagnosed cancers in recent years. A significant percentage of these cancers originate in the intestines, potentially leading to a global rise in cancer-related deaths. Conventional colonoscopy, highly reliant on an endoscopist's expertise, is the standard for screening and diagnosis. However, accurately detecting and segmenting polyps remains challenging despite advancements in technology. Our project aims to facilitate early and precise polyp diagnosis using cutting-edge Deep Learning models, leveraging architectures like Res-Net50, Res-Net101, U-net, and others. These models are pretrained on comprehensive polyps datasets like Kvasir-SEG and CVC-Clinic 612, enhancing detection performance.

Preprocessing the Data

We employ various data augmentation techniques to enhance the diversity and quality of the dataset, crucial for improving the model's accuracy and robustness.

### Training Models

Our approach includes training different models to compare their effectiveness in polyp segmentation:

- U-Net
- ResNet
- ResUnet++
- ColonSegNet
- Double−UNet

## Research Work

For detailed insights and methodologies, refer to our research paper: Multimedia Evaluation 2021 Paper. The paper elaborates on the technical aspects and the innovative approaches we have implemented in this project.

[Working Paper Proceedings of the MediaEval 2021 Workshop](https://ceur-ws.org/Vol-3181/paper34.pdf)

##  Web Application

To streamline the polyp detection process, we have developed a web application using Streamlit and Firebase. This app allows for easy uploading and processing of endoscopic images, with the results presented in a downloadable PDF report format.

##  Datasets

The project utilizes datasets from Simula Research Lab, which have been further augmented to enhance the model's training. The original and augmented datasets are available at the following links:

[Original Dataset: Simula Research Lab Dataset](https://www.kaggle.com/datasets/muhammadhassaan786/kavisr-test-dataset)

[Augmented Dataset](https://www.kaggle.com/datasets/muhammadhassaan786/augmented-dataset.)



## Installation and Usage

config and requirement.txt will add

## Contributing

(for other developers on how they can contribute to your project. Include guidelines on pull requests, coding standards, or other procedures you'd like contributors to follow.)

##  License

(will add the license under which your project is released, if applicable.)

##  Acknowledgments

(A  acknowledge any individuals, organizations, or institutions that contributed to the success of the project.)
