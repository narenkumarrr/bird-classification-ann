# Bird Classification using Artificial Neural Network

## Overview
This project demonstrates the implementation of a deep neural network (ANN) for classifying bird species. The entire model was built from scratch, line by line, showcasing a comprehensive understanding of neural network architecture, data preprocessing, training, and evaluation processes.

## Technologies Used
- **Python**: Primary programming language
- **TensorFlow/Keras**: For building and training the neural network
- **NumPy**: For numerical computations
- **Pandas**: For data manipulation and analysis
- **Scikit-learn**: For data preprocessing, model evaluation, and metrics
- **Matplotlib & Seaborn**: For data visualization and plotting results

## Project Structure
- `notebooks/dnnpractical2.ipynb`: Jupyter notebook containing the complete implementation
- `models/bird_ann_model.h5`: Trained ANN model saved in HDF5 format
- `requirements.txt`: List of required Python packages

## Key Features
- Custom ANN architecture designed for multi-class classification
- Comprehensive data preprocessing including scaling and encoding
- Model training with validation and performance monitoring
- Evaluation using confusion matrix and classification reports
- Visualization of training history and results

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open the Jupyter notebook: `jupyter notebook notebooks/dnnpractical2.ipynb`
3. Run the cells sequentially to reproduce the results

## Results
The model achieved a training accuracy of 76.67% and a test accuracy of 73.49%. The classification report shows a weighted average F1-score of 0.73, with macro average F1-score of 0.54 across 6 bird species classes.

## Learning Outcomes
This project highlights expertise in:
- Deep learning model development
- Data science workflows
- Python programming for machine learning
- Model serialization and deployment basics


