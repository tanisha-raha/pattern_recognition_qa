# Pattern Recognition Q&A System

This project implements a simple yet interactive **Pattern Recognition Q&A System**. It uses a neural network to classify geometric shapes (e.g., circles, squares, triangles) and provides predictions based on user queries. The system supports both single and batch predictions with confidence scores.

---

## Features

- **Shape Recognition**: Identifies geometric shapes in grayscale images (circle, square, triangle, etc.).
- **Interactive Q&A Interface**: Ask natural language questions like:
  - `"What shape is in image path/to/image.png?"`
  - `"Predict shapes for images path1.png, path2.png"`
- **Batch Predictions**: Provide multiple image paths to get predictions for all images.
- **Confidence Scores**: Outputs the confidence level for each prediction.
- **Error Handling**: Validates image paths and handles invalid inputs gracefully.
- **Expandable**: Easily add more shapes or integrate advanced models.

---

## Installation

### Prerequisites
Ensure you have Python installed on your system. This project requires Python 3.6 or higher.

### Required Libraries
Install the necessary Python libraries using pip:
```bash
pip install numpy scikit-learn opencv-python
