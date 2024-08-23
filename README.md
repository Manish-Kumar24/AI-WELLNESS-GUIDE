# AI-WELLNESS-GUIDE
![Project Logo](assets/logo.png)
Overview
This project is a web application that predicts potential diseases based on the symptoms entered by the user. The app leverages Flask for the backend and a Decision Tree Classifier model for the predictions. It provides users with an intuitive platform to input their symptoms and receive accurate health-related insights instantly.

Features
- Symptom Input: Users can enter their symptoms via a user-friendly interface.
- Disease Prediction: A pre-trained Decision Tree Classifier model predicts potential diseases based on the symptoms provided.
- Comprehensive Information: The app provides descriptions, precautions, medications, dietary advice, and workout tips for the predicted disease.
- Educational Content: Includes informative blog posts about various health topics.

Prerequisites
- Flask==3.0.3
- numpy==1.24.3
- scikit-learn==1.2.2
- pandas==2.2.2

Setup
- 1. Clone the repository:
      git clone https://github.com/yourusername/symptom-disease-diagnosis.git
      cd symptom-disease-diagnosis
- 2. Create a virtual environment:
      python -m venv venv
      source venv/bin/activate  # On Windows use `venv\Scripts\activate`
- 3. Install the required dependencies:
      pip install -r requirements.txt
- 4. Run the Flask application:
      flask run
- 5. Navigate to http://127.0.0.1:5000/ in your web browser to use the application.

Usage
1. Enter your symptoms in the provided input fields.
2. Click on the "Predict" button to get the disease prediction.
3. Explore the additional information provided, such as disease descriptions, precautions, medications, diet suggestions, and workout tips.

Technologies Used
- Backend: Flask
- Frontend: HTML, CSS, Bootstrap
- Machine Learning: Scikit-learn (Decision Tree Classifier)
- Data Handling: Pandas, Numpy
