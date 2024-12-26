# Fabrico - Fabric Defect Detection System

Fabrico is an intelligent system designed for fabric defect detection using machine learning and computer vision techniques. It uses a combination of deep learning algorithms, image processing, and a web interface to detect defects in fabric for quality control in the textile industry.

## Features

- **Fabric Defect Detection**: Automatically detects defects in fabric images.
- **Real-time Detection**: Capable of processing fabric images in real-time for quality assurance.
- **Web Interface**: An easy-to-use interface for uploading images and viewing results.
- **Deep Learning Model**: Uses a trained deep learning model for defect detection.
- **Image Processing**: Utilizes OpenCV for image pre-processing and defect enhancement.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- pip (Python package manager)
- Virtual environment (optional but recommended)

### Steps to Install

1. Clone the repository:

    ```bash
    git clone https://github.com/MuhammadHassaan2002/FYP-FABRICO.git
    cd FYP-FABRICO
    ```

2. Create a virtual environment (optional):

    ```bash
    python -m venv venv
    source venv/bin/activate  # For Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start the Flask web server:

    ```bash
    python app.py
    ```

2. Open your browser and go to `http://127.0.0.1:5000/` to access the web interface.

3. Upload fabric images for defect detection.

4. View the results, including any detected defects in the fabric.

## Model Training

To train the defect detection model, follow these steps:

1. Prepare your dataset of fabric images with labeled defects.
2. Pre-process the images using OpenCV and save them in the correct format.
3. Train a machine learning model (e.g., a CNN) using a framework like TensorFlow or PyTorch.
4. Save the trained model and integrate it into the system.

## Contributing

Contributions are welcome! If you would like to improve the system or add new features, please fork this repository, create a new branch, and submit a pull request.

### How to Contribute

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/) - For building the web application.
- [OpenCV](https://opencv.org/) - For image processing.
- [TensorFlow](https://www.tensorflow.org/) - For machine learning model training.
- [Keras](https://keras.io/) - For deep learning model development.

## Contact

If you have any questions or suggestions, feel free to reach out via email or open an issue in the repository.
