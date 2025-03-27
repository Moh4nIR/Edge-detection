# Edge-detection

<<<<<<< HEAD
# Edge-detection
=======
# Edge Detection Using Traditional and Deep Learning Methods

## Approach and Model Selection

This project explores edge detection using both traditional and deep learning-based methods. The traditional methods include Sobel and Canny edge detectors, while the deep learning approach leverages a pre-trained U-Net model for edge detection.

- **Traditional Methods**: Sobel and Canny operators were applied to detect edges based on gradients.
- **Deep Learning-Based Method**: A pre-trained U-Net model was used to learn and predict edge structures in images.
- **Dataset**: The BSDS500 dataset was used for evaluation, along with sample images for qualitative comparison.

## Results and Analysis

- **Traditional Methods**:
  - Sobel Edge Detection captures directional gradients but may be sensitive to noise.
  - Canny Edge Detection applies Gaussian smoothing and hysteresis thresholding, providing better-defined edges.
- **Deep Learning-Based Edge Detection**:
  - The U-Net model demonstrates superior edge detection capability, capturing finer details and reducing noise compared to traditional methods.
  - Performance is highly dependent on training data and model fine-tuning.

## Video Demonstration

A video is provided showcasing the edge detection outputs from all methods, comparing traditional methods with the U-Net model. The demo includes:

1. Input images
2. Sobel and Canny edge detection outputs
3. U-Net model predictions
4. Comparative analysis of results

## Running the Project

### Prerequisites

- Install dependencies from `requirements.txt`:
  ```bash
  pip install -r requirements.txt
  ```
- Ensure that `trained_unet.pth` is available in `models/pytorch_unet/unet/` from the pytorch repo
- Use the provided Jupyter notebooks to run traditional and deep learning edge detection methods.

### Running the Notebooks

Open and execute the following notebooks in Jupyter:

- `edge_detection_baseline.ipynb` - Traditional edge detection methods
- `edge_detection_deep_learning_based.ipynb` - U-Net based edge detection

### Expected Output

- Edge-detected images using Sobel, Canny, and U-Net.
- Qualitative comparison highlighting the advantages of deep learning methods.



>>>>>>> 7e97de8 (all the files required to run)
