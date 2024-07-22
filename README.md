# Hand Detection using Mediapipe

This project demonstrates how to use Mediapipe for real-time hand detection using a webcam. Mediapipe is a powerful framework for building multimodal (video, audio, etc.) machine learning pipelines.

## Features

- Real-time hand detection
- Visualization of hand landmarks
- Supports multiple webcams

## Prerequisites

- Python 3.6+
- OpenCV
- Mediapipe

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/hand-detection-mediapipe.git
   cd hand-detection-mediapipe
   ```

2. **Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages**

   ```bash
   pip install -r requirements.txt
   ```

   *requirements.txt* should include:
   ```plaintext
   opencv-python
   mediapipe
   ```

## Usage

1. **Run the script**

   ```bash
   python hand_detection.py
   ```

2. **Switch between webcams**

   Modify the `webcam_index` in `hand_detection.py` to switch between webcams:
   ```python
   webcam_index = 0  # Default webcam
   # webcam_index = 1  # USB webcam
   ```



## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Mediapipe](https://mediapipe.dev)
- [OpenCV](https://opencv.org)

