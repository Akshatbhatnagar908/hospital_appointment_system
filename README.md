🏥 AI Healthcare Assistant
This project is an AI-driven healthcare assistant designed to improve hospital workflows and patient outcomes. It provides automated solutions for tasks like disease identification, consultation time prediction, appointment scheduling, discharge management, and billing notifications.

📂 Project Structure
ai_chat bot.ipynb – Interactive chatbot interface for healthcare use-cases.

identify_for_disease.ipynb – Machine learning model for disease detection from patient data.

data.csv / patients.xlsx / processed_patient_data.xlsx – Patient datasets for training and evaluation.

Presentation1.pptx – Summary of key features and workflow overview.

Untitled*.ipynb – Supporting notebooks for experiments or model development.

🚀 Features
Disease Identification: Predict diseases based on patient symptoms and health history.

Consultation Time Prediction: Estimate consultation duration using historical data.

Automated Billing Notifications: Notify patients regarding their billing status automatically.

Turnaround Time Measurement: Analyze and reduce hospital service delays.

Patient Appointment Scheduling: Automate and optimize patient bookings.

Discharge Mechanism: Suggest timely discharge for improved bed utilization.

🧠 Tech Stack
Python (Jupyter Notebooks)

Pandas, NumPy, Scikit-learn

Matplotlib, Seaborn (for visualization)

OpenAI GPT (for chatbot interface)

Excel/CSV for data management

📊 Datasets
patients.xlsx & data.csv: Raw and structured patient data.

processed_patient_data.xlsx: Cleaned and preprocessed data ready for model training.

📌 Getting Started
1. Clone the repo

git clone https://github.com/Akshatbhatnagar908/ai-healthcare-assistant.git
cd ai-healthcare-assistant
2. Install requirements

pip install -r requirements.txt
(Create a requirements.txt with the necessary libraries like pandas, scikit-learn, openai, etc.)

3. Run the notebooks
Launch Jupyter:


jupyter notebook
Then open and run the notebooks in order:

identify_for_disease.ipynb

ai_chat bot.ipynb

Other experimental notebooks as needed

📝 Future Improvements
Integrate real-time EHR systems.

Deploy models using Flask or FastAPI.

Add secure user authentication.

Improve model accuracy with larger datasets.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.


