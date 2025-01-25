# Project Setup and Usage Instructions

## Recommended System Requirements:
- **Memory**: 16GB or more

## Software Requirements:
- **Python**: Version >= 3.8
- **TensorFlow**: Version >= 2.9
- **ampligraph**: Version 2.0.1
- **numpy**: Version 1.24.4
- **scikit-learn**: Version 1.3.1

## Data Processing:
Our code includes two types of data processing methods:

1. **Run `embedding.py`**: This script generates embeddings for the triplets and outputs the embedded files.  
   **Note**: Running `embedding.py` may take approximately two days, depending on your hardware configuration. The results may vary based on the hardware performance.

2. **Run `processing_data.py`**: This script combines the disease-metabolite samples with the embedded entities to create trainable sample files.

3. **Run `train.py`**: This script trains the model and evaluates its performance.  
   **Note**: Running `train.py` typically takes about **20 minutes**.

## How to Use:
1. Make sure you have the required dependencies installed as listed above.
2. Run the `embedding.py` script to generate the embedded triplets. Be aware that this may take a significant amount of time.
3. Run the `processing_data.py` script to combine the embedded entities with disease-metabolite samples.
4. Finally, run `train.py` to evaluate the trained model.

## Installation:
To install the required dependencies, run the following command:

```bash
pip install -r requirements.txt
