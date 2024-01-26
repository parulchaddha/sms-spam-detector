# SMS Spam Detector

## Overview
This project implements a SMS spam detector using Machine Learning algorithms, primarily based on the Multinomial Naive Bayes algorithm. The detector is capable of analyzing text messages and determining whether they are spam or not. The project also includes vectorization using three different algorithms to optimize the output.

## Features
- Multinomial Naive Bayes algorithm with precision 1.
- Streamlit frontend for user-friendly interaction.
- Vectorization using three different algorithms for enhanced performance.

## Installation

### Dependencies
- Python 3.x
- pip (Python package installer)
- Required libraries: `numpy`, `scikit-learn`, `streamlit`

### Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sms-spam-detector.git
   cd sms-spam-detector
2. Install dependencies
   ```bash
   pip install -r requirements.txt

## Video sample
![SMS Spam Detector Demo](sms-spam.gif)

Click on the image to play the video

## Usage
1. Run the streamlit app:
   ```bash
   streamlit run app.py
2. Open your web browser and navigate to https://localhost:8501
3. Enter a random message into the provided input field and click the "Check" button to determine if it is spam or not.
