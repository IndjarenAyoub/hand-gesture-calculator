# Hand Gesture Calculator

This project is a hand gesture-based calculator using OpenCV and the CvZone library. The calculator detects hand gestures using a webcam and allows you to perform basic arithmetic operations by interacting with on-screen buttons.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/hand-gesture-calculator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd hand-gesture-calculator
    ```
3. Install the required dependencies:
    ```bash
    pip install opencv-python cvzone
    ```

## Usage

1. Run the script:
    ```bash
    python hand_gesture_calculator.py
    ```
2. The calculator interface will appear on your screen.
3. Use your hand to interact with the buttons. The index finger and middle finger's distance is used to detect clicks.
4. The equation will be displayed at the top, and the result will be shown when you press the '=' button.
5. Press 'q' to quit the application.
6. Press 'c' to clear the current equation.

## Features

- Hand detection using a webcam.
- Interactive on-screen buttons for basic arithmetic operations.
- Displays the current equation and result.

## Dependencies

- OpenCV
- CvZone

## License

This project is licensed under the MIT License.
