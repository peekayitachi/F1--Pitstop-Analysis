# F1-Pit-Stop-Analysis
Project for Data Orchestration for Cloud Ecosystem

This project aims to develop a machine learning model to optimize pit stop strategies in
Formula 1 (F1) racing, utilizing historical and real-time telemetry data. Pit stops, critical
moments during a race, significantly influence race outcomes due to their impact on lap
times and overall strategy. Traditional pit stop decisions relied heavily on experience and
real-time judgments, but with advances in data analytics, machine learning offers a
promising approach to predicting optimal pit stop timings.
Using the fastf1 Python library, the study extracts telemetry data, such as lap times, tire wear,
weather conditions, and track data. The goal is to preprocess using Spark and engineer these
features to form a structured dataset suitable for machine learning. An XGBoost regressor
will be used to predict the ideal timing for pit stops based on various input features. This
model will be validated using historical race data, testing its accuracy and reliability across
different race conditions.
The study also explores the real-time application of the model, aiming to provide F1 teams
with predictive insights during live races. By leveraging machine learning to optimize pit
stop timing, the project seeks to improve team strategies, reduce time losses, and enhance
overall race performance. The findings have broader implications for predictive sports
analytics, demonstrating how telemetry data can be used to inform split-second decisions in
dynamic sports environments. Ultimately, this research aims to create a robust model that
assists F1 teams in making data-driven, real-time decisions, contributing to the ongoing
evolution of data-driven strategies in motorsports.
