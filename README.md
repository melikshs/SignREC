# SpotPOP: Predicting the Popularity of a Song on Spotify

## Project Overview
SpotPOP is a data science project designed to predict the popularity of a song on Spotify given some known features about the song. Utilizing the Spotify Song dataset from Kaggle, this project employs different regression schemes and compares the outcome to converge on the most accurate prediction model. 

## Dataset
The data for this project is sourced from Kaggle, which can be found [here](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset/data). The dataset contains over 100,000 song entries and 20 different features for each entry, making it a suitable dataset or data exploration, cleaning, and training.


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
