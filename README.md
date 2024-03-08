## Face Detection Comparison

This repository provides code for comparing different face detection models: Haar Cascade, Mediapipe, and CNN with dlib library. The code evaluates the performance of each model in detecting faces in images and computes accuracy metrics.

### Prerequisites

Make sure you have the necessary dependencies installed:

- OpenCV (`cv2`)
- Mediapipe (`mediapipe`)
- Dlib (`dlib`)
- `os` module

### Dataset

The code assumes that the images are stored in a directory. You can use any dataset of your choice. For demonstration purposes, you can download a sample dataset from [this link](http://chenlab.ece.cornell.edu/people/Andy/ImagesOfGroups.html).

### Instructions

1. Download the dataset and organize it in a directory.
2. Update the `dataset_dir` variable in the code to point to the directory containing your dataset.
3. Run each section of the code corresponding to the face detection model you want to evaluate.

### Face Detection Models

1. **Haar Cascade Face Detector:**
   - This method utilizes the pre-trained Haar Cascade classifier for face detection.
   - The accuracy of detection is calculated and displayed.
   - Detected faces are outlined with rectangles in the output images.

2. **Mediapipe Face Detection:**
   - Requires installation of Mediapipe library (`pip install mediapipe`).
   - Utilizes Mediapipe's face detection model.
   - Accuracy of detection and visualizations are provided.

3. **CNN with dlib library:**
   - Requires installation of dlib library (`pip install dlib`).
   - Employs dlib's CNN-based face detection model.
   - Detection accuracy metrics are calculated.

### Results

- The total number of images processed.
- Total faces detected using each method.
- Accuracy of face detection for each model.

### Output

Detected faces in the images are outlined with green rectangles, and the results are saved in a specified directory.

Feel free to modify the code and parameters to suit your specific requirements.

For more information on face detection models, you can refer to [this comprehensive guide](https://faceonlive.com/face-detection-models-the-ultimate-guide-2023-unleash-the-power-of-ai-to-spot-faces-like-a-pro/).

Please note that this code assumes a basic understanding of Python and familiarity with the mentioned libraries. If you encounter any issues or have any questions, feel free to reach out.

Happy face detecting! 🚀


