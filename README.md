**#Spam classifier using Multiple classifier models**

This project outlines the process of building a spam classifier using multiple classifier models. The steps involved are:

Train multiple classifier models such as Naive Bayes (NB), Support Vector Machine (SVM), k-Nearest Neighbors (KNN), Random Forest (RF), Voting, and Stacking.
Save the trained models as pickle files for later use.
For EC2 deployment:
a. Create a Flask app and load the saved model using the pickle file.
b. Deploy the Flask app and pickle files to an AWS EC2 instance using SSH or FTP clients.
For Streamlit deployment:
a. Create a Streamlit app named "streamlit_app.py" and load the saved model using the pickle file.
b. Push the code to GitHub and utilize Streamlit Cloud deployment for hosting the app.
    
