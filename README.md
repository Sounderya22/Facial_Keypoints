# Facial Keypoint Detection

## Project Description
This project implements a facial keypoint detection system using Convolutional Neural Networks (CNNs). It detects faces in images and predicts the coordinates of 68 facial keypoints.

## Notebooks
- **Notebook 1**: Load and visualize the data.
- **Notebook 2**: Define and train the CNN architecture.
- **Notebook 3**: Run the full detection pipeline.
- **Notebook 4**: Apply fun filters using keypoints.

## Setup Instructions

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/udacity/P1_Facial_Keypoints.git
    cd P1_Facial_Keypoints
    ```

2.  **Create and activate environment**:
    ```bash
    conda create -n cv-nd python=3.6
    source activate cv-nd
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
    *Note: Ensure PyTorch is installed suitable for your system (CPU or GPU).*
