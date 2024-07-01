# Lane-Detection

This is a Python code snippet for detecting and drawing lane lines in a video using the OpenCV library. It uses computer vision techniques to identify lane markings and draw lines on the image.

## Prerequisites

- Python 3.x
- OpenCV library (`pip install opencv-python`)
- NumPy library (`pip install numpy`)
- Matplotlib library (`pip install matplotlib`)

## How to Use

1. Install the required dependencies mentioned above.
2. Copy and paste the code into a Python file or Jupyter Notebook.
3. Make sure you have a video file named `test2.mp4` in the same directory as the script. You can change the video file name or path in the code if needed.
4. Uncomment the lines to run the code on a single image if desired.
5. Save the file and run it. The code will open a video file, process each frame to detect lane lines, and display the resulting video with lane lines drawn on top.
6. Press the 'q' key to exit the video playback.

Please note that you can modify the parameters such as Canny edge detection thresholds, Hough transform parameters, and region of interest coordinates to adjust the lane detection algorithm for different scenarios.

Feel free to experiment and tweak the code according to your needs!

### Notes

- Ensure your Python environment is correctly set up with the required libraries.
- Modify the video file path if using a different file.
- Experiment with different parameters to improve lane detection based on your specific video conditions.

---

This project demonstrates basic lane line detection techniques using OpenCV. You can further enhance the algorithm with more sophisticated methods for improved accuracy and robustness.
