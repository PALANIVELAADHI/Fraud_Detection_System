# Fraud Detection System

A machine learning-based web application to predict the likelihood of fraudulent transactions using real-time data inputs. Built with FastAPI, TensorFlow, and a Random Forest model, this system provides an intuitive interface for users to input transaction details and visualize fraud probability.

---

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features
- **Real-Time Fraud Prediction**: Enter transaction details to get instant fraud probability scores.
- **Interactive Visualization**: Bar chart displaying "Not Fraud" vs. "Fraud" probabilities.
- **User Authentication**: Secure login/logout functionality.
- **Responsive Design**: Clean, professional UI optimized for desktop and mobile.

---

## Technologies
- **Backend**: FastAPI (Python)
- **Machine Learning**: Random Forest (scikit-learn), TensorFlow
- **Frontend**: Jinja2 templates, HTML, CSS
- **Data Processing**: NumPy, joblib (scaler)
- **Dependencies**: Managed via `requirements.txt`

---

## Installation

### Prerequisites
- Python 3.8+
- Git
- Virtualenv (recommended)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/fraud-detection-system.git
   cd fraud-detection-system
2. **Create my_db using mysql**
3.   **uvicorn app:app --reload** 
