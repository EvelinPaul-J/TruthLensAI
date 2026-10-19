# TruthLens AI — Multimodal Fake Content Detection

TruthLens AI is a **Multimodal Fake Content Detection System** designed to identify whether digital content is **Real or Fake** using Machine Learning and Deep Learning techniques.

The system analyzes text, images, audio, and video to help detect fake news, manipulated images, synthetic audio, and deepfake videos through a web-based application.

## Features

### 1. Text Fake News Detection
- Analyzes news articles and text content.
- Uses Natural Language Processing (NLP) and machine learning techniques.
- Predicts whether the given content is Real or Fake.

### 2. Image Manipulation Detection
- Uses deep learning techniques to analyze images.
- Helps identify manipulated or AI-generated images.

### 3. Audio Authenticity Detection
- Extracts audio features such as MFCC (Mel Frequency Cepstral Coefficients).
- Uses machine learning or deep learning models to classify audio as Real or Fake.

### 4. Video Deepfake Detection
- Analyzes video frames to identify potential manipulation.
- Supports deepfake detection depending on the availability of the trained video model.

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask

### Machine Learning and Deep Learning
- TensorFlow
- Keras
- Scikit-learn
- Joblib

### Audio Processing
- Librosa

### Image and Video Processing
- OpenCV
- NumPy

## Project Structure

```text
TruthLens-AI/
├── app.py
├── requirements.txt
├── README.md
├── assets/
├── templates/
│   ├── index.html
│   └── about.html
├── static/
│   └── css/
│       └── style.css
├── models/
├── training/
└── uploads/
```

> Note: The project structure above is a general example. Update it to match the actual files and folders in your repository.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/EvelinPaul-J/TruthLensAI.git
```

### 2. Navigate to the Project Directory

```bash
cd TruthLensAI
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Running the Application

Start the application using:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

The application will run locally if all required dependencies and model files are available.

## Usage

1. Open the TruthLens AI web application.
2. Select the type of content to analyze.
3. Enter text or upload an image, audio file, or video.
4. Run the detection process.
5. Review the model's prediction.

**Disclaimer:** Predictions are model-generated estimates and should not be treated as definitive proof that content is genuine or fake.

## Future Improvements

- Improve model accuracy and reliability.
- Enhance video deepfake detection.
- Add real-time content verification.
- Deploy the application to a cloud platform.
- Expand training datasets and support additional content formats.

## Author

**Evelin Paul**  
Artificial Intelligence & Machine Learning Enthusiast

GitHub: [@EvelinPaul-J](https://github.com/EvelinPaul-J)

## Acknowledgements

This project builds on machine learning and deep learning techniques for multimodal content analysis. Credit original contributors and datasets in accordance with their licences and usage terms.

