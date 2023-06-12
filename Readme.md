# Facial Recognition Project

This project implements a web-based face recognition application using the face-api.js library. It detects faces in a live video stream from the user's camera, applies face landmarks and expressions, and displays the results in real-time.

## Prerequisites

- Web browser with webcam support
- Internet connection (for loading face-api.js models)

## Getting Started

1. Clone the repository or download the project files.

2. Open the `index.html` file in a web browser.

## Usage

1. Grant permission to access your webcam when prompted.

2. The video stream will be displayed on the page, and face recognition will start automatically.

3. Detected faces will be outlined, and face landmarks and expressions will be overlaid on each face.

## Files

- `index.html`: The main HTML file that sets up the video element and includes the necessary scripts.
- `style.css`: CSS file for styling the page layout.
- `script.js`: JavaScript file that loads the face-api.js library, starts the video stream, and performs face recognition.

## Dependencies

The project relies on the following libraries:

- face-api.js: A JavaScript API for face detection, recognition, and other face-related tasks.

## Acknowledgements

This project utilizes the face-api.js library developed by Vincent Mühler. More information and documentation for face-api.js can be found at [https://github.com/justadudewhohacks/face-api.js](https://github.com/justadudewhohacks/face-api.js).

## License

This project is licensed under the [MIT License](LICENSE).
