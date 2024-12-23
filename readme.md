# Audio Classifier for Capuchin bird calls

This project implements a convolutional neural network (CNN)-based audio classifier to detect and distinguish Capuchin bird sounds from other environmental sounds. The project uses forest audio clips for training and evaluation and is designed to classify sounds with high accuracy.

## Project Structure

```
.
|-- dataset
|   |-- Forest Recordings
|   |-- Parsed_Capuchinbird_Clips
|   |-- Parsed_Not_Capuchinbird_Clips
|-- papers
|-- main.ipynb
|-- readme.md
|-- req.txt
|-- results.csv
```

### Key Files and Directories

- `dataset/`: Contains the audio data used for training and evaluation.
  - `Forest Recordings`: Raw recordings from the forest.
  - `Parsed_Capuchinbird_Clips`: Processed audio clips of Capuchinbird sounds.
  - `Parsed_Not_Capuchinbird_Clips`: Processed audio clips of other sounds.
- `papers/`: Contains reference papers related to audio classification and Capuchinbird studies.
- `main.ipynb`: The main Jupyter Notebook containing the code for training, testing, and evaluating the model.
- `req.txt`: List of Python dependencies required to run the project.
- `results.csv`: Contains the classification results and performance metrics.

## Setup and Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Nomaanrizvi/Audio-Classifier-for-Capuchin-bird-calls.git
   cd Audio Classifier for Capuchin bird calls
   ```

2. Install the required dependencies:
   ```bash
   pip install -r req.txt
   ```

3. Ensure the dataset is placed in the `dataset/` directory as per the structure mentioned above.

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

2. Follow the steps in the notebook to:
   - Preprocess the data.
   - Train the CNN model.
   - Evaluate the model on the test data.

3. Check the `results.csv` file for detailed classification results.

## Results

The results of the audio classification are stored in `results.csv`. Key metric includes `the number of calls of the capuchin birds` .

## References

The `papers/` directory contains research papers and reference materials that were used to guide the development of this project. These include studies on Capuchinbird sound detection and CNN-based audio classification.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

Special thanks to researchers and data providers for making audio datasets available on kaggle for analysis and experimentation.