Resume Category Prediction



This Streamlit application predicts the job category of uploaded resumes. Users can upload resumes in PDF, DOCX, or TXT formats, and the app will extract the text and predict the job category using a pre-trained Support Vector Classifier (SVC) model.

![image](https://github.com/user-attachments/assets/291f00a6-298f-432d-ad7c-650793be2087)
Features:
Upload resumes in PDF, DOCX, or TXT formats.
Text extraction from uploaded files.
Text preprocessing to clean and normalize the resume content.
Predict the job category of the resume.
Display the predicted category to the user.

Installation"
Clone the repository:
git clone https://github.com/yourusername/resume-category-prediction.git
cd resume-category-prediction
Install the required packages:

bash
pip install -r requirements.txt


Ensure you have the following packages installed:
streamlit
pickle
python-docx
PyPDF2
re

Place the models: Ensure the following model files are in the project directory:
clf.pkl
tfidf.pkl
encoder.pkl

Usage
Run the Streamlit app:

bash
streamlit run app.py
Upload a resume:

Click on the "Upload a Resume" button and select a PDF, DOCX, or TXT file.

Predicted Category:
The predicted job category of the uploaded resume will be displayed on the screen.

Show Extracted Text (Optional):

