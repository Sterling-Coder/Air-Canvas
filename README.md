# Air Canvas

Air Canvas is an interactive drawing application that allows users to draw on a digital canvas using hand gestures captured by a webcam. This project uses computer vision and hand tracking to create a virtual drawing experience without any physical input devices.

## Features

- **Color Selection**: Choose between blue, green, red, and yellow drawing colors
- **Clear Canvas**: Reset the canvas with a simple gesture
- **Real-time Drawing**: Instantly see your drawings appear as you move your hand
- **Hand Tracking**: Utilizes MediaPipe for accurate hand landmark detection

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- MediaPipe

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/YOUR-USERNAME/Air-Canvas.git
   cd Air-Canvas
   ```

2. Install the required packages:
   ```
   pip install opencv-python numpy mediapipe
   ```

## Usage

1. Run the application:
   ```
   python Air_Canvas.py
   ```

2. Position yourself in front of the webcam.

3. Use your index finger to draw on the canvas:
   - Move your hand to the colored rectangles at the top to select a color
   - Move to the "CLEAR" button to reset the canvas
   - Draw anywhere else on the screen

4. To stop drawing temporarily, bring your thumb close to your index finger.

5. Press 'q' to quit the application.

## How It Works

The application uses MediaPipe to detect hand landmarks in real-time. It tracks the position of your index finger to determine where to draw, and monitors the distance between your thumb and index finger to detect when you want to pause drawing.

The drawing interface has color selection buttons at the top of the screen and a separate window showing your drawing on a clean canvas.

Enjoy! 😄
