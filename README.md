# Day-13-Automatrix
Day 13: Deploy a compact TensorFlow Lite Iris classifier for ESP32 inference. The model uses four normalized features to predict one of three classes.


# Day 13: TensorFlow Lite Iris Classifier

This project uses a compact TensorFlow Lite model to classify Iris flower samples. The model accepts four normalized input features and produces scores for three output classes.

## Model details

- Inputs: 4 normalized features
- Outputs: 3 classes
- Model size: 5,040 bytes
- Operations: Fully connected and softmax

## Project files

- `model.h` — generated model data and sample input arrays.
- `sketch.ino` — ESP32 inference code, if included.
- `diagram.json` — Wokwi ESP32 configuration, if included.
- `python.py` — model training and conversion code, if included.

Update the file names above to match the files in your repository.

## Wokwi Simulation

[Open the Wokwi simulation](https://wokwi.com/projects/469378874786036737)

Replace the placeholder with your Wokwi project’s **Share** link.

## How it works

The input sample contains four normalized feature values. The TensorFlow Lite model processes them and returns three output scores. The classifier selects the class with the highest score.

## Run

1. Open the Wokwi simulation.
2. Start the ESP32 simulation.
3. Open the Serial Monitor to view the input values and predicted class.
