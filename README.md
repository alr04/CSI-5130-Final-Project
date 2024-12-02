# Piano Chord Classification

## Introduction
This project focuses on classifying audio samples of piano chords. The approach involves converting audio files into spectrogram images and using these images to train a machine learning model for classification.

## Dataset
- Half of the `.wav` audio samples were downloaded from the [Zenodo Piano Chord Dataset](https://zenodo.org/records/4740877).
- A script was used to generate additional audio samples to assist in training, but this isn't required to run the model.

## Installation
1. Clone the repository:
   ```bash
   git clone <https://github.com/alr04/CSI-5130-Final-Project>
   cd <CSI-5130-Final-Project>
2. Install the required dependencies
   ```bash
   pip install -r requirements.txt

## Usage
1. Open the `PerformPrediction.ipynb` notebook.
2. Run all cells in the notebook

## Running with GPU v CPU
To enable GPU support, modify the following line in the notebook:
```python
device = "cuda or cpu"
```
and change it to:
```python 
device = "cuda"
```
To enable CPU support, change the original line to:
```python
device = "cpu"
```

```markdown
## Notes
- Ensure your system has the required dependencies installed before running the notebook.
- For GPU acceleration, ensure you have a compatible CUDA setup.

## License
This project uses the [Zenodo Piano Chord Dataset](https://zenodo.org/records/4740877). Please review the dataset license for more details.

