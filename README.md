# Clustering-and-Classification-Image-Compression

## Project Overview
This project demonstrates two fundamental machine learning techniques: clustering and classification. The project is divided into two parts:

1. **Image Compression**: Using K-Means clustering to compress an image by reducing the number of colors.
2. **Classification**: Implementing SVM-based classification models to analyze and classify data with decision boundary visualization.

---

## Problem Statements

### Problem 1: Image Compression
The goal is to reduce the number of colors in an image by clustering similar pixels together.
- Implemented a custom K-Means algorithm from scratch.
- Compared the results with the `sklearn` KMeans implementation.
- Visualized compressed images for different numbers of clusters.

### Problem 2: Classification Tasks
#### Task 1: Binary Classification with Linear SVM
- Used the Iris dataset to classify two classes based on petal length and width.
- Visualized decision boundaries for both training and testing datasets.

#### Task 2: SVM with Kernel Methods
- Generated a synthetic dataset using the `make_moons` function.
- Trained SVM models with linear, polynomial, and RBF kernels.
- Optimized hyperparameters for the RBF kernel using `GridSearchCV`.
- Visualized decision boundaries and evaluated model accuracy.

---

## Project Structure
- **`main.py`**: Contains the implementation of clustering and classification tasks.
- **`test.png`**: Input image used for the image compression task.
- **`README.md`**: Project documentation.

---

## Requirements

Install the required Python libraries:
```bash
pip install numpy opencv-python matplotlib scikit-learn
```

---

## How to Run the Code

1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Place an input image (e.g., `test.png`) in the project directory.

3. Run the script:
```bash
python main.py
```

4. Follow the output visualizations for compressed images and decision boundaries.

---

## Results

### Problem 1: Image Compression
Compressed images were generated for various cluster values. Both custom and `sklearn` implementations of K-Means produced visually similar results, demonstrating effective clustering of pixel colors.

### Problem 2: Classification Tasks
- Linear SVM models successfully classified data with clear decision boundaries.
- Polynomial and RBF kernels captured non-linear patterns in the synthetic dataset.
- Hyperparameter tuning improved the performance of the RBF kernel model, achieving high accuracy on test data.

---

## Key Learnings
- Understanding and implementing K-Means clustering.
- Visualizing clustering and classification results.
- Training SVMs with different kernels and optimizing hyperparameters.

---

## License
This project is licensed under the MIT License. Feel free to use and modify the code as needed.

---

## Acknowledgments
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [OpenCV Documentation](https://docs.opencv.org/master/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
