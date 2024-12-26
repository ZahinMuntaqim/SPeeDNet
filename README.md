# SPeeDNet: A High-Performance Lite-weight Deep Learning Model for Retinal Disease Classification Utilizing Multi-Branch Feature Aggregation.

## Introduction

This project focuses on classifying eye diseases using deep learning techniques. It leverages the power of neural networks to detect various eye conditions, enabling faster diagnosis and potentially reducing the burden on healthcare systems. The model is trained to identify different diseases from retinal images or related datasets, providing a crucial tool for ophthalmologists and healthcare professionals.

### Key Features:
- SPeeDNet have 0.194M params and 759.29 KB Size. 
- Accurate classification of eye diseases (e.g., diabetic retinopathy, glaucoma, cataracts, etc.)
- Can be integrated with other medical applications for disease prediction and analysis

## Architecture: SpeedNet

The **SpeedNet** architecture is specifically designed for efficient processing of medical images, optimizing both speed and accuracy. Below is a figure illustrating the architecture of SpeedNet:

![SpeedNet Architecture](path_to_your_image/SpeedNet_Architecture.png)

## Results

The model is evaluated on several benchmark datasets for eye disease classification. Below is an example of the results obtained:

![Results](path_to_your_image/Results_Figure.png)

The results demonstrate the model's ability to classify eye diseases with high accuracy, offering potential for real-time diagnostic assistance.

## Installation

To install and run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/eye-disease-classification.git
    ```

2. Navigate into the project directory:
    ```bash
    cd eye-disease-classification
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the main program:
    ```bash
    python classify_eye_disease.py
    ```

## Usage

1. Upload your retinal images or provide the dataset path in the input section.
2. Run the classification script, and the model will output the predicted eye disease and associated confidence score.
3. Analyze the results for further interpretation or integration into medical systems.

## Contributing

Feel free to fork the repository, open issues, and submit pull requests for improvements. Contributions are welcome!


