# Vehicle Detection and Counting System using OpenCV

This Python script detects vehicles in a video stream using background subtraction and contour detection. It counts vehicles that pass a defined line on the screen.

## Features

- Background subtraction using MOG (Mixture of Gaussians) algorithm.
- Vehicle detection based on contour analysis.
- Real-time vehicle counting.
- Adjustable parameters for minimum vehicle size and line position.

## Requirements

- Python 3.8
- numpy==1.21.4
- opencv-python==4.5.4.58

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/LakshmiReddy-Sanikommu/Vehicle-Detection-using-Machine-Learning.git
   ```
2. Navigate to the project directory:
   ```bash
   cd vehicle-detection-using-Machine-Learning
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have Python 3.8 installed.

2. Install the required dependencies as mentioned above.

3. Adjust the video path in cap = cv2.VideoCapture('Data/video.mp4') according to your video file location.

4. Run the script with the command:
   ```bash
   python vehicle_detection.py
   ```
5. The video window will display the original video with vehicle detection and counting overlay.

## Configuration

- `offset`: Allows adjustment for error tolerance in pixel detection.
- `min_width_react` and `min_height_react`: Minimum width and height thresholds for valid vehicle detection.
- `count_line_position`: Y-coordinate position of the counting line on the video frame.

## Controls

- Press `Enter` key to exit the program.

## Contributing

If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. Don't forget to star the repository if you find it useful!

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.


