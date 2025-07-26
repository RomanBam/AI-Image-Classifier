# AI Image Classifier

A web-based AI image classification application built with Streamlit and TensorFlow. Upload images and get instant AI-powered predictions using the MobileNetV2 model pre-trained on ImageNet.

## Features

- **Upload images** in JPG or PNG format
- **AI-powered classification** using TensorFlow's MobileNetV2 model
- **Real-time predictions** with confidence scores
- **User-friendly interface** built with Streamlit
- **Pre-trained model** on ImageNet dataset (1000+ categories)

## Requirements

- **Python 3.9-3.12** (TensorFlow compatibility)
- **uv** (for dependency management)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RomanBam/AI-Image-Classifier.git
   cd AI-Image-Classifier
   ```

2. **Install dependencies using uv:**
   ```bash
   uv add streamlit tensorflow opencv-python
   ```
## Running the App

1. **Start the Streamlit app:**
   ```bash
   uv run streamlit run main.py
   ```

2. **Open your browser** and navigate to the URL shown in the terminal (typically `http://localhost:8501`)

3. **Upload an image** and click "Classify Image" to get AI predictions

## Usage

1. **Upload Image**: Click "Choose an image..." and select a JPG or PNG file
2. **Classify**: Click the "Classify Image" button
3. **View Results**: See the top 3 predictions with confidence scores
