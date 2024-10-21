# Camera System README

This project is a camera system application with real-time face recognition. It is developed using the Flask web framework and the OpenCV library.

## Requirements

- Python 3.x
- Flask
- OpenCV

## Installation

1. Install the required Python packages:
    ```bash
    pip install flask opencv-python
    ```

2. Run the `app.py` file in the project directory:
    ```bash
    python app.py
    ```

## Usage

1. After running the `app.py` file, go to `http://127.0.0.1:5000/` in your web browser.
2. Open the page to see the real-time face recognition stream.

## File Structure

- `app.py`: The main Python file containing the Flask application and face recognition functionality.
- `templates/index.html`: The HTML file for the web interface.
- `README.md`: This file, providing information about the project.

## Explanation

- In the `app.py` file, the `generate_frames` function uses OpenCV to detect faces in the images captured from the camera and sends these images to the web browser.
- The `index.html` file is a simple HTML page served by Flask that displays the real-time video stream.
