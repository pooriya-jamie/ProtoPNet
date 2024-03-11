# ProtoPNet for Medical Image Classification

This repository contains code adapted from the ProtoPNet project (https://github.com/cfchen-duke/ProtoPNet) for the classification of medical images. The primary dataset used for this adaptation is the MedMNIST dataset (https://medmnist.com/), specifically focusing on the PneumoniaMNIST subset.

## Overview

ProtoPNet is a neural network architecture designed for few-shot image classification tasks, which are often encountered in medical imaging scenarios where labeled data is scarce. By adapting ProtoPNet to medical datasets, particularly focusing on pneumonia classification using chest X-ray images, we aim to demonstrate its efficacy in a domain where labeled data is typically limited.

## Dataset

The primary dataset used in this project is the PneumoniaMNIST subset of MedMNIST, which consists of binary-class chest X-ray images labeled as either pneumonia-positive or pneumonia-negative. The dataset comprises the following splits:

- **Training Set:** 4,708 samples
- **Validation Set:** 524 samples
- **Test Set:** 624 samples

For citing the dataset, please refer to the following papers:

- Jiancheng Yang, Rui Shi, Donglai Wei, Zequan Liu, Lin Zhao, Bilian Ke, Hanspeter Pfister, Bingbing Ni. "MedMNIST v2-A large-scale lightweight benchmark for 2D and 3D biomedical image classification." *Scientific Data*, 2023.
- Jiancheng Yang, Rui Shi, Bingbing Ni. "MedMNIST Classification Decathlon: A Lightweight AutoML Benchmark for Medical Image Analysis". *IEEE 18th International Symposium on Biomedical Imaging (ISBI)*, 2021.

Additionally, supplementary data might have been collected from external sources, which should be properly cited as per their respective licenses and guidelines.

## Usage

1. **Data Preparation:** Download the PneumoniaMNIST dataset from the MedMNIST website or other authorized sources. Preprocess the data as necessary for training, validation, and testing.

2. **Model Training:** Train the ProtoPNet model using the provided code. Adjust hyperparameters and network architecture as needed based on the specific requirements of the medical image classification task.

3. **Evaluation:** Evaluate the trained model on the validation and test sets to assess its performance. Utilize appropriate metrics such as accuracy, precision, recall, and F1-score to measure classification performance.

4. **Deployment:** Once satisfied with the model's performance, deploy it in relevant medical applications for pneumonia classification tasks. Ensure compliance with regulatory standards and ethical guidelines governing medical AI applications.

## Acknowledgments

We acknowledge the developers of ProtoPNet for providing the foundational codebase for this project. Additionally, we express our gratitude to the authors of the MedMNIST dataset for curating and releasing a valuable resource for the medical imaging community.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore the code and adapt it to your needs. If you have any questions or suggestions, please reach out to Pooriya Jamie.
