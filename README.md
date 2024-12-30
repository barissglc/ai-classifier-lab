# Interactive Web App with Streamlit and Scikit-learn

Explore different datasets and classifiers interactively. This application uses Streamlit to provide an intuitive interface for experimenting with machine learning classifiers like KNN, SVM, and Random Forest.

Visit the official [Streamlit website](https://www.streamlit.io/) for more info on creating interactive Python apps.

---

## Features
- Interactive dataset selection (`Iris`, `Wine`, and `Breast Cancer` datasets).
- Adjustable classifier parameters through sidebar sliders.
- Visualizations: PCA scatter plot, correlation heatmap, and sinusoidal wave generator.

---

## Installation
Make sure you have Python installed on your system. Install the required dependencies:
```bash
pip install streamlit scikit-learn matplotlib seaborn
```

---

## Usage - Local
To run the application locally:
```bash
streamlit run main.py
```

---

## Usage - Docker
Build and run the application using Docker:
```bash
# Build a local Docker image
docker build -t mlimage .

# Run the Docker container
docker run -p 8501:8501 mlimage
```

Note: Ensure that Docker is installed and running on your system.

---

## Demo
Experience the live demo:
[Streamlit App Demo]([https://ai-classifier-lab-fz4fbdwdpmkibarzcmldpb.streamlit.app/])

---
