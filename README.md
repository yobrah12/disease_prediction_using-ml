# disease_prediction_using-ml
# Disease Prediction System

A web-based application that leverages Machine Learning to predict diseases based on user-provided symptoms. Built with Django as the backend framework, PostgreSQL for database management, and Machine Learning models to provide accurate predictions.

---

## Features

- **User-friendly Interface**: Simple and intuitive design for users to input symptoms.
- **Machine Learning Integration**: Predict diseases using trained ML models.
- **Django Backend**: Robust and scalable backend for handling requests and managing user data.
- **PostgreSQL Database**: Reliable and efficient storage for user data and model configurations.
- **Data Security**: Implements best practices to ensure data privacy and security.

---

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (optional frameworks like Bootstrap for responsiveness).
- **Backend**: Django (Python-based web framework).
- **Database**: PostgreSQL.
- **Machine Learning**: Scikit-learn for training and deploying the disease prediction model.

---

## Installation

Follow these steps to set up the project on your local machine:

### Prerequisites
- Python 3.8+
- PostgreSQL 13+
- Git

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your_username/disease-prediction.git
   cd disease-prediction
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/MacOS
   venv\Scripts\activate    # For Windows
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up PostgreSQL Database**:
   - Create a new database (e.g., `disease_prediction`).
   - Update the `DATABASES` configuration in the `settings.py` file:
     ```python
     DATABASES = {
         'default': {
             'ENGINE': 'django.db.backends.postgresql',
             'NAME': 'disease_prediction',
             'USER': 'your_postgres_user',
             'PASSWORD': 'your_postgres_password',
             'HOST': 'localhost',
             'PORT': '5432',
         }
     }
     ```

5. **Apply Migrations**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```
   Visit `http://127.0.0.1:8000/` in your browser to access the application.

---

## Usage

1. Navigate to the web app in your browser.
2. Enter your symptoms in the input form.
3. Submit the form to get disease predictions.
4. View the results along with suggestions for further action.

---

## Machine Learning Model

- **Algorithm**: The ML model is built using Scikit-learn.
- **Dataset**: Trained on a dataset of diseases and symptoms (e.g., publicly available healthcare datasets or custom-built datasets).
- **Training**: Pre-trained and integrated with the Django backend.

---

## Future Enhancements

- **Integration with APIs**: Fetch real-time medical data.
- **Improved ML Models**: Use deep learning for more accurate predictions.
- **Mobile App**: Develop a mobile version for better accessibility.
- **Multi-language Support**: Localize the application for non-English users.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -m "Description of changes"`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a pull request.

---

## License

This project is licensed under the GPL 3.0 License. See the `LICENSE` file for more details.

---

## Contact

- **Author**: Yegon Brian
- **Email**: yegonbrian9290@gmail.com
- **GitHub**: [https://github.com/yobrah12]
