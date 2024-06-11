Description
This project demonstrates a basic implementation of color detection using OpenCV in Python. The program captures video from the webcam, detects a specified color in the video frame, and draws a bounding box around the detected color.

Features
Capture live video from the webcam.
Convert the video frames from BGR to HSV color space.
Detect a specified color in the video frames.
Draw a bounding box around the detected color.
Print the coordinates of the bounding box.
Requirements
Python 3.10
OpenCV 4.6.0.66
NumPy 1.23.4
Pillow
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/YourUsername/Color_Detection.git
Navigate to the project directory:
bash
Copy code
cd Color_Detection
Create and activate a virtual environment:
bash
Copy code
python -m venv myenv
myenv\Scripts\activate
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Usage
Run the main script:

bash
Copy code
python main.py
The webcam will open, and the program will start detecting the specified color (red in this case) and draw a bounding box around it.

Press 'q' to quit the program.

Files
main.py: The main script to run the color detection.
utils.py: A utility script containing the get_limits function to calculate HSV color limits for detection.
Customization
To detect a different color, change the BGR values in the main.py script:
python
Copy code
red = [0, 0, 255] # BGR values for red
Replace [0, 0, 255] with the BGR values of the color you want to detect.
License
This project is licensed under the MIT License.

