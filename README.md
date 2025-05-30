# motion_detection_opencv
Motion Detection using Background Subtraction and OpenCV


This project applies and compares three background subtraction methods—MOG, MOG2, and KNN on different videos to detect motion and draw bounding boxes around moving objects.

##  Project Structure

- `motion_detection.ipynb` – Google Colab notebook containing the full code and explanation.
- `motion_detection.py` – Optional Python script version.
- `sample_input/` – Folder containing sample video(s).
- `results/` – Folder with output videos and screenshots.

## Methods Used

- **MOG (Mixture of Gaussians)**: Legacy method with simple background modeling.
- **MOG2**: Improved version with better shadow detection and dynamic background learning.
- **KNN**: Uses pixel neighborhood comparison and adaptive learning.

## Features

- Applies morphological filters to reduce noise.
- Detects motion using bounding boxes.
- Annotates each method’s results with color-coded labels.
- Saves output videos separately for each method.
- Includes a combined frame comparison.

## How to Use

1. Upload your input video to the `videos/` directory.
2. Run the notebook or script.
3. Check the `results/` folder for output videos.
4. Use the comparison frame for visual analysis.

## Sample Result

![sample result](results/motion_detection_output_1.mp4)

## Requirements

- Python
- OpenCV
- NumPy
- Google Colab or Jupyter Notebook
