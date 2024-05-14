# SignRec: Traffic Sign Recognition for Autonomous Vehicles

## Project Overview
SignRec is a deep learning project designed to enhance the capabilities of autonomous vehicles by enabling them to recognize and 
respond to traffic signs accurately. Utilizing the German Traffic Sign Recognition Benchmark (GTSRB) dataset, this project employs 
convolutional neural networks (CNNs) to develop a robust traffic sign recognition system. This system aims to improve the safety 
and efficiency of autonomous driving technologies by ensuring compliance with traffic regulations.

## Dataset
The data for this project is sourced from the GTSRB dataset hosted on Kaggle, which can be found [here](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign). The dataset contains over 50,000 images of traffic signs across 43 categories, providing a comprehensive set of training data for our recognition model.


## Project Structure

The repository is structured as follows:

- **SignRec/**: Root folder.
  - **src/**: Contains all source files for the project.
    - **data_preprocessing.py**: Script for data loading and preprocessing.
    - **model.py**: Script for CNN model definition.
    - **train.py**: Script to train the model.
    - **evaluate.py**: Script to evaluate the model.
  - **notebooks/**: Jupyter notebooks for explorations and presentations.
    - **Exploratory_Data_Analysis.ipynb**
    - **Model_Training_and_Evaluation.ipynb**
  - **data/**: Folder for storing data (this folder should be ignored by git).
  - **requirements.txt**: Python dependencies for the project.
  - **README.md**: The project README file.


## Setup and Installation
To set up this project, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/SignRec.git
   cd SignRec

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

4. Download the dataset from Kaggle and place it in the data/ directory.

   
## Usage
To run the project, follow these steps:

1. Preprocess the data:
   ```bash
   python src/data_preprocessing.py

2. Train the model:
   ```bash
   python src/train.py

4. Evaluate the model:
   ```bash
   python src/evaluate.py


## Contributing
Contributions to SignRec are welcome! Please feel free to submit pull requests or open issues to discuss potential improvements or features.
