# Navttc-Project-Face-Detection-Using-OpenCV
# Real-Time Face and Eye Detection using OpenCV

This project demonstrates real-time face and eye detection using Python and OpenCV. The application captures video from a webcam, processes the frames, and detects faces and eyes using Haar cascades.

## Features

- Real-time face detection
- Real-time eye detection within detected faces
- Display of rectangles around detected faces and eyes

## Prerequisites

Make sure you have the following installed:

- Python 3.x
- OpenCV (`opencv-python`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Nasir-Sharif/Navttc-Project-Face-Detection-Using-OpenCV.git
    cd Navttc-Project-Face-Detection-Using-OpenCV
    ```

2. Create and activate a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install opencv-python
    ```

## Usage

1. Download the Haar Cascade XML files and place them in the project directory:
    - [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
    - [haarcascade_eye.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye.xml)

2. Run the script:

    ```bash
    python main.py
    ```

3. The application will open a window displaying the video feed with rectangles around detected faces and eyes.

4. Press `Esc` to exit the application.

## Project Structure

```plaintext
Face-Detection-Opencv/
│
├── haarcascade_frontalface_default.xml  # Pre-trained face detection model
├── haarcascade_eye.xml                  # Pre-trained eye detection model
├── main.py                              # Main Python script
└── README.md                            # This file
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- OpenCV for providing the powerful computer vision library.
- The OpenCV community for the Haar Cascade XML files.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

---

**Author:** Nasir Sharif
