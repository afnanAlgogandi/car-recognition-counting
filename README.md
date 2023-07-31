# Car Counting Program

This program is used to detect and count cars in an image, similar to how modern cameras do on roads and streets. The image to be inspected is loaded, and a special program called "Haar Cascade classification" is used to detect the presence of cars in the image. Rectangles are drawn around each car found, and the total number of cars present in the image is displayed. This type of program can be used for traffic analysis, and to improve road planning and management.

## Requirements

- Python 3.5+
- OpenCV

## Installation

1. Clone the repository or download the code as a zip file and extract it.
2. Install the required libraries using pip: `pip install opencv-python`

## Usage

1. Add the image you want to analyze to the same folder as the program file.
2. Open the program file "car_count.py" and replace the image path with your image path.
3. Run the program by executing `car_count.py`.
4. The program will load the image and detect cars using Haar Cascade classification. Rectangles will be drawn around each car found, and the total number of cars present in the image will be displayed. The image with the detected cars will be displayed.

Note: If you get an error message that the image file or Haar Cascade classifier file could not be opened, make sure the file path is correct and the files are in the correct location.


