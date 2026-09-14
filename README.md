# Handwritten Digit Recognition

A machine learning project that recognizes handwritten digits from images using Python. The project trains a classification model and predicts the digit represented by an input image.

## Features

- Handwritten digit classification from 0 to 9
- Image preprocessing using OpenCV
- Machine learning model training
- Prediction from images stored in the `digit` folder
- Fully executable from the terminal

## Project Structure

```text
Handwritten_Digit_Recognition/
│
├── hand_written_classification.py
├── requirements.txt
└── digit/
    └── 7.png
```

## Requirements

- Python 3.12
- pip
- Required Python libraries listed in `requirements.txt`

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/dewanganvaibhav256-ops/Handwritten_Digit_Recognition.git
cd Handwritten_Digit_Recognition
```

### 2. Create a virtual environment

```bash
python3.12 -m venv .venv
```

### 3. Activate the virtual environment

**Linux / macOS:**

```bash
source .venv/bin/activate
```

**Windows:**

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Run the Project

Execute the Python file directly from the terminal:

```bash
python hand_written_classification.py --image digit/7.png
```

The program will train the model and process the input image specified in the Python file.

## Input Image

Place your handwritten digit image inside the `digit` folder.

Example:

```text
digit/7.png
```

The image path can be specified in the Python file:

```python
image_path = "digit/7.png"
```

Replace `7.png` with the name of your own image.

## Example Output

```text
Epoch 1/3
Epoch 2/3
Epoch 3/3

Predicted Digit: 7
```
Image:

<img width="693" height="172" alt="image" src="https://github.com/user-attachments/assets/b74afe3f-e591-47ca-bf95-ed33c1883aa0" />

<img width="1017" height="559" alt="image" src="https://github.com/user-attachments/assets/991ac46c-7e10-4aec-82e9-1d6551156b99" />

*The output may vary depending on the input image and model performance.*

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Notes

- Run the commands from the project root directory.
- Ensure the input image exists in the `digit` folder.
- The project is designed to run through the command line using the Python script.
- A compatible Python version is required for TensorFlow installation.

## Author

**Vaibhav Dewangan**

## Repository

https://github.com/dewanganvaibhav256-ops/Handwritten_Digit_Recognition
