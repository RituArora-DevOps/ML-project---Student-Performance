Student Performance Prediction using Machine Learning

This project explores the use of machine learning models to predict student academic performance based on various personal, social, and academic factors. The goal is to identify key contributors to performance and help in early interventions.

Features:

Data preprocessing and exploratory data analysis (EDA)

Feature engineering and selection

Model training using algorithms like:

Logistic Regression

Decision Trees

Random Forest

XGBoost (optional)

Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix

Visualizations for insights and model interpretation

Dataset:

Used the Student Performance Data Set
 from the UCI Machine Learning Repository. It includes features like:

Demographic information

Parental education

Study time

Previous grades

Absences, etc.

Results:

Achieved up to XX% accuracy in predicting student performance categories (pass/fail or grade range, depending on your target variable). Also performed feature importance analysis.


docker build -t student-performance-app .
docker login
docker tag student-performance-app dockerhubusername/student-performance-app:latest
docker push dockerhubusername/student-performance-app:latest

docker run -p 5000:5000 student-performance-app

sudo apt-get update -y
sudo apt-get upgrade

curl -fssl https://get.docker.com -o get-docker.sh
sudo sh get-docker .sh
sudo usermod -aG docker ubuntu
newgrp docker

AWS Deployment