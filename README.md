# Music Generator using LSTM

## Project Overview

This project focuses on generating music using a Bidirectional LSTM model trained on classical music MIDI datasets. The primary goal is to explore the capabilities of LSTM networks in capturing patterns and generating music compositions.

## Datasets

Two datasets were used for training the model:

1. [Classical Music MIDI Dataset](https://www.kaggle.com/datasets/soumikrakshit/classical-music-midi)
2. [Music Generated LSTM Dataset](https://www.kaggle.com/datasets/karnikakapoor/music-generated-lstm)

Feel free to explore these datasets for a deeper understanding of the input data used in the project.

## Model Training

The core of the project involved training a Bidirectional LSTM model. The model was trained for 200 epochs, and the training process resulted in a final loss of 0.10. This suggests that the model has successfully learned patterns from the training data.

## Generated Music

A function was implemented to generate music using the trained Bidirectional LSTM model. The generated music demonstrated promising results, showcasing the model's ability to create compositions that align with the patterns learned during training.

## Repository Structure

- `datasets/`: Folder containing the MIDI datasets used for training.
- `models/`: Folder containing the saved Bidirectional LSTM model.
- `notebooks/`: Kaggle notebooks used for data exploration, model training, and music generation.
- `src/`: Source code including the Bidirectional LSTM model definition and the music generation function.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/DreamIsMl/Music-Generator-Using-Lstm.git
