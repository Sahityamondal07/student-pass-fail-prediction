# Student Pass/Fail Prediction using ANN

A beginner-friendly Artificial Neural Network (ANN) project built with **TensorFlow/Keras** and **NumPy**.

The model learns a simple binary classification example:

- `0` = Fail
- `1` = Pass

It uses study hours as the input feature and predicts the probability of passing.

## Project structure

```text
Student-Pass-Fail-Prediction/
├── student_pass_fail_ann.py
├── README.md
└── requirements.txt
```

## Requirements

- Python 3.9 or a TensorFlow-supported Python version
- TensorFlow
- NumPy

Install the dependencies:

```bash
pip install -r requirements.txt
```

## Run the project

Make sure `student_pass_fail_ann.py` and the two support files are in the same folder. Then run:

```bash
python student_pass_fail_ann.py
```

The script trains the ANN for 100 epochs, predicts the result for 6 study hours, and prints the predicted probability and classification.

## Model overview

The model contains:

1. An input feature representing study hours.
2. A hidden Dense layer with 8 neurons and ReLU activation.
3. An output Dense layer with 1 neuron and sigmoid activation.
4. The Adam optimizer and binary cross-entropy loss.
5. Accuracy as the training metric.

## Important note

This is a small educational demonstration using only eight hand-written examples. It is not a validated model for real student outcomes. A real-world model would need a representative dataset, suitable evaluation on unseen data, and careful consideration of factors beyond study hours.

## License

Add a license to this repository if you intend to specify how others may use, modify, or distribute the project.
