### Adanomad OA

## Description

A Computer Vision model that uses YOLO pose estimation landmarks from a BJJ dataset to predict the BJJ position executed in images

## Files

The repo has 3 major files:

- `preprocess_data_dense_layers.ipynb`
- `train_dense_layers.ipynb`
- `extract_coordinates.ipynb`

There are also 2 important folders:

- `results`: containing the model history plot (loss and accuracy)
- `runs`: Some YOLOv8 pose estimation demos

## Installation and Setup

Follow these steps to set up your environment and get started with the project.

### 1. Creating a Conda Environment

Use the following command to create a new Conda environment:

```bash
conda create --name <env> --file requirements.txt python=3.10
```

Replace `<env>` with your desired environment name.

### 2. Downloading the Dataset

Download the dataset annotations (JSON file) from the following website:

[VI-COS Jiu-Jitsu Dataset](https://vicos.si/resources/jiujitsu/)

### 3. Data Preprocessing

Follow the instructions provided in the Jupyter Notebook to preprocess the data:

```
preprocess_data_dense_layers.ipynb
```

### 4. Training the Model

To train the model, run the cells in the following Python script:

```
train_dense_layers.py
```

### 5. Inference on New Images

To extract coordinates from a new image and run inference, use:

```
extract_coordinates.ipynb
```
