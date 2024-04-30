

# <h1>SafeSonic</h1>

## Overview

SafeSonic is a web application built with Flask that allows users to record and test audio samples for speaker identification using Gaussian Mixture Models (GMMs). This system can be used for various applications such as voice authentication, speaker recognition, and more.

## Features

- **Record Audio**: Users can record audio samples for training and testing purposes directly from the web application.
- **Train Model**: The application trains Gaussian Mixture Models (GMMs) using the recorded audio samples to identify different speakers.
- **Test Model**: Users can test the trained models by providing new audio samples for speaker identification.
- **Real-time Updates**: The application provides real-time updates using Socket.IO to notify users about the progress of audio recording and training.

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/safesonic.git
    ```

2. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**:

    ```bash
    python app.py
    ```

4. **Access the Application**:

    Open your web browser and go to [http://localhost:5000](http://localhost:5000) to access the application.

## Usage

1. **Record Audio Samples**:
   
    - Navigate to the "Record Train" or "Record Test" section of the application.
    - Follow the on-screen instructions to record audio samples.

2. **Train the Model**:

    - Navigate to the "Train" section of the application.
    - Click on the "Train" button to start training the Gaussian Mixture Models (GMMs).

3. **Test the Model**:

    - Navigate to the "Test" section of the application.
    - Click on the "Test" button to provide new audio samples for speaker identification.

## Configuration

- **Secret Key**: Set the `SECRET_KEY` environment variable to a secure random value. This key is used for encrypting session data and should be kept secret.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/) - Web framework for Python
- [Socket.IO](https://socket.io/) - Real-time bidirectional communication between web clients and servers

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---


