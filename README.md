 PCOS360 Project- a safe haven for PCOS warriors

PCOS360 is a web application designed to help individuals manage and monitor Polycystic Ovary Syndrome (PCOS). It offers a range of features including risk assessments, symptom tracking, personalized fitness and diet plans, mental health support, and much more.

 Features Implemented:

 1. PCOS Risk Assessment Quiz
   - A quiz that evaluates the user's risk of PCOS based on common symptoms like irregular periods, weight gain, anxiety, etc.
   - The quiz uses a machine learning model (`pcos_model.pkl`) to predict the likelihood of a user having a high or low risk of PCOS, based on their responses.
   - Symptoms such as irregular periods, acne, weight gain, hair loss, cramps, and others are rated to calculate the risk score.

 2. Symptom Tracker
   - Allows users to log and track PCOS symptoms such as menstrual irregularities, weight changes, mood swings, etc.
   - Provides a simple interface for daily symptom tracking, enabling users to understand patterns over time.
   - Includes data visualization to graphically represent logged symptoms.

 3. BMI Calculator
   - Users can input their weight and height to calculate their Body Mass Index (BMI).
   - The calculator determines whether the user is underweight, normal weight, overweight, or obese based on BMI.

 4. Personalized Diet and Fitness Plan
   - The app generates customized fitness and diet plans based on user inputs like age, weight, height, and BMI.
   - Offers basic guidelines for fitness and diet, with additional sources linked based on the user's results.

 5. Chatbot for Mental Health and Emergency Contacts
   - A chatbot powered by OpenAI's GPT-3.5 provides support for mental health concerns related to PCOS.
   - It offers relevant advice, emergency contacts, and mental health resources, as well as nearby health services like ambulance numbers and suicide helplines.

 6. Diet and Fitness Plan with Links
   - Based on the user's BMI and fitness goals, the app provides a basic diet and fitness plan.
   - Links to external resources are dynamically displayed based on the user's results (e.g., additional workout videos, PCOS-friendly diet plans).

 7. Web Application Structure**
   - Developed using **Flask** as the backend framework.
   - Frontend templates are rendered using **Jinja2**, and the web app provides a responsive interface with HTML forms for user input.
   - The app uses **pickle** for loading a trained machine learning model for PCOS prediction and **scikit-learn** for data scaling.


Requirements

- Python 3.x
- Flask
- scikit-learn
- OpenAI API (for the chatbot functionality)
- pickle (for loading the ML model and scaler)
