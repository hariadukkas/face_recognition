# Face Recognition Python Project

Welcome to the Face Recognition Python project! This project showcases a simple implementation of face recognition using Python. The application detects and recognizes faces in images using a pre-trained model. Please follow the instructions below to get started.

## Prerequisites

Before running the application, make sure you have the following software installed on your computer:

- Python (3.6 or higher)
- GCC (GNU Compiler Collection)
- CMake

## Installation

1. Clone or download this repository to your local machine.
2. Open a terminal window and navigate to the project directory.

```bash
cd path/to/face-recognition-project
```

3. Install the required Python packages by running:

```bash
pip install -r requirements.txt
```

## Usage

To run the application, you can use the `detector.py` script. The script supports three main modes: `train`, `validate`, and `test`.

### Syntax

```bash
python detector.py <mode> [options]
```

### Modes

1. `train`: Train the face recognition model using labeled data.
2. `validate`: Validate the trained model's performance on validation data.
3. `test`: Test the trained model on a single image.

### Options

- `-f`, `--file`: Path to the image file for testing. (Only used in `test` mode)
- `-h`, `--help`: Show help message and exit.

### Examples

1. To train the model:

```bash
python detector.py train
```

2. To validate the model:

```bash
python detector.py validate
```

3. To test the model on an image:

```bash
python detector.py test -f img.png
```

Make sure to replace `img_1.png` with the actual image file you want to test.

## Notes

- This project uses a pre-trained face recognition model.
- Ensure that you have GCC and CMake installed before running the program.

## Credits

This project was inspired by the idea of face recognition and was created for educational purposes.

Feel free to explore the code and customize it according to your needs!

