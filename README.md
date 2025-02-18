# Plagiarism Checker Web App

The **Plagiarism Checker** web app is designed to detect text similarities, using **Flask**, **Python**, and **scikit-learn**. Users can input two text samples, and the application will compare them, displaying a percentage score to indicate their similarity.

## Key Features
- Compare two text samples to detect plagiarism.
- Implements **TF-IDF Vectorizer** and **Cosine Similarity** for accurate similarity comparison.
- Displays the similarity score as a percentage.
- Fully responsive for both desktop and mobile users.

## Technologies
- **Flask**: Python web framework used to build the app.
- **scikit-learn**: Machine learning library for **TF-IDF** and **Cosine Similarity** calculations.
- **HTML/CSS/JavaScript**: For creating the front-end interface.
- **Python**: Handles back-end processing.

## Setup Guide

### Prerequisites
- **Python** (version 3.6 or higher)
- **Flask** and **scikit-learn** (installation steps below)

### Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Data-Master10/Plagiarism-checker-Python-Web.git
   cd /lagiarism-checker-Python-Web
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   If the `requirements.txt` file is not available, manually install the necessary libraries:
   ```bash
   pip install flask scikit-learn
   ```

4. Start the Flask application:
   ```bash
   python app.py
   ```
   The app will be accessible at `http://127.0.0.1:5000/` in your browser.

### How to Use

1. Open a browser and go to `http://127.0.0.1:5000/`.
2. Enter two text samples in the provided text boxes.
3. Click the "Check Similarity" button.
4. The application will calculate and display the similarity score as a percentage.

### Example

**Input 1**:  
The quick brown fox jumps over the lazy dog.

**Input 2**:  
A fast brown fox leaps over a lazy dog.

**Output**:  
Plagiarism Similarity: 72.34%

## Folder Structure
```
/plagiarism-checker
    /static
        styles.css
        script.js
    /templates
        index.html
    app.py
    requirements.txt
    README.md
```
