# CampusFit - Campus Placement Prediction System

CampusFit is a web-based application that helps students assess their placement readiness and predict their chances of placement in companies using machine learning algorithms. The system provides technical assessments, communication assessments, and personalized predictions based on student profiles.

## Features

- **User Authentication System**
  - User registration and login
  - Password recovery functionality
  - Secure session management

- **Assessment Modules**
  - Technical Skills Assessment
  - Communication Skills Assessment
  - Aptitude Questions
  - Timed test environment

- **ML-Based Predictions**
  - Placement probability prediction
  - Company fit analysis
  - Score prediction
  - Resume analysis capabilities

- **Interactive Dashboard**
  - User profile management
  - Assessment results visualization
  - Progress tracking
  - Performance analytics

## Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: Scikit-learn (Pre-trained models)
- **Data Storage**: CSV-based data management
- **Static Assets**: Custom CSS animations and styling

## Project Structure

```
CampusFit/
├── app.py                 # Main Flask application
├── ml_predictor.py        # ML prediction logic
├── score_predictor.py     # Score prediction module
├── test_predictor.py      # Test assessment logic
├── train_model.py         # ML model training script
├── data/                  # Dataset directory
├── models/               # Trained ML models
├── static/               # Static assets (CSS, JS, images)
└── templates/            # HTML templates
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/CampusFit.git
cd CampusFit
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```

4. Access the application at `http://localhost:5000`

## Models

The system uses several pre-trained machine learning models:
- `placement_model.pkl`: Predicts placement probability
- `company_fit_model.pkl`: Analyzes company fit
- `scaler.pkl`: Feature scaling for predictions

## Data Files

- `Apquestions.csv`: Aptitude questions database
- `CommunicationAssess.csv`: Communication assessment questions
- `TechnicalQuestions.csv`: Technical assessment questions
- `placement_data.csv`: Training data for ML models
- `loginUsers.csv`: User authentication data

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgments

- Thanks to all contributors who have helped with the development
- Special thanks to the ML community for model training resources
- Appreciation to the Flask community for web framework support