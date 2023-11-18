# Fashion MNIST Classification

## Dependencies

Before running the project, ensure that you have the required dependencies installed. You can choose one of the following methods:

### Method 1: Using requirements.txt

1. Open a terminal or command prompt.

2. Navigate to the project directory.

3. Run the following command to install the dependencies listed in the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

### Method 2: Using install_requirements.py

1. Open a terminal or command prompt.

2. Navigate to the project directory.

3. Run the following command to execute the `install_requirements.py` script:

    ```bash
    python install_requirements.py
    ```

   This script will install the required dependencies using `pip`.

# Data Organization

Before running the code, make sure to organize your data in the following structure and place it in the `Data` folder:

data - https://drive.google.com/drive/folders/1loTGJ2XxOBBh4R8nGSha1FeQMs2QTzkJ?usp=sharing

# CNN Model Tuning Results

After thorough experimentation and tuning, the following three sets of model parameters demonstrated the highest validation accuracy. These configurations are recommended for their outstanding performance:

| Rank | Convolution 1 Filters | Convolution 2 Filters | Filter Size | Dense Layer | Validation Accuracy |
|------|------------------------|------------------------|-------------|-------------|----------------------|
| 1    | 32                     | 64                     | 3           | 64          | 92.01%               |
| 2    | 64                     | 128                    | 3           | 32          | 91.84%               |
| 3    | 64                     | 128                    | 3           | 64          | 91.89%               |

These configurations represent the top-performing models based on their validation accuracy.

# ResNet-Inspired Model Tuning Results

Inspired by the ResNet architecture, the following three configurations of the model were experimented with, showcasing their validation accuracies:

| Rank | Residual Blocks | Filters | Validation Accuracy |
|------|------------------|---------|----------------------|
| 1    | 3                | 64      | 92.81%               |
| 2    | 4                | 64      | 92.51%               |
| 3    | 5                | 64      | 92.11%               |

These configurations represent the top-performing models based on their validation accuracy.
