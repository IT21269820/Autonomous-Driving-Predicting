# Autonomous-Driving-Predicting
# Driver Behavior Classification Using Mobile Sensors and CARLA Simulation

## Overview

This project introduces a **cost-effective, scalable, and non-invasive system** to classify driver behavior using machine learning techniques. The solution leverages **mobile phone sensors (accelerometer, GPS)** and the **CARLA simulator** to collect both real-world and simulated driving data, enabling the training of robust classification models.

By integrating mobile and simulated data, the project aims to address key challenges in driver behavior analysis—such as affordability, accessibility, and data diversity—while maintaining high model accuracy and practical usability.

## Table of Contents

- [Features](#features)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [System Requirements](#system-requirements)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Commercialization Potential](#commercialization-potential)
- [Contributors](#contributors)

## Features

- Real-time driver behavior classification (Aggressive, Moderate, Cautious)
- Data collection from mobile sensors (Accelerometer, GPS)
- Simulation of diverse driving scenarios via CARLA
- Machine Learning models: Decision Tree, SVM
- Dashboard with analytics and behavior reports
- Support for fleet operators, individual drivers, and insurers

## Objectives

### Main Objective
Develop a scalable and affordable system for classifying driver behavior using accessible mobile sensor data and CARLA-based simulations.

### Specific Objectives
- Build ML models to classify driver behavior
- Use mobile sensors for real-world data collection
- Generate synthetic data using CARLA for diversity
- Enable real-time analysis and feedback
- Provide visual behavior reports and alerts

## Methodology

1. **Data Collection**
   - Real-world driving data from mobile sensors
   - Simulated data from CARLA representing various driving styles

2. **Data Preprocessing**
   - Cleaning, normalization, feature extraction
   - Labeling data by driving style

3. **Model Training**
   - Supervised learning (Decision Trees, SVM)
   - Model validation with test datasets

4. **System Implementation**
   - Python backend with SQL database
   - Web interface for visual insights

5. **Evaluation**
   - Performance metrics: Accuracy, Precision, Recall, F1-score

## System Requirements

### Hardware
- Smartphone with accelerometer and GPS
- Edge computing unit (optional)

### Software
- Python 3.x
- CARLA Simulator
- SQLite
- Scikit-learn, Pandas, Matplotlib

## Technologies Used

- **CARLA Simulator** – Simulate realistic driving scenarios
- **Python** – Backend and ML model development
- **Scikit-learn** – ML algorithms
- **SQLite** – Data storage
- **Matplotlib / Pandas** – Data visualization and processing
- **Jupyter Notebook** – Prototyping and experimentation

## Usage

1. Collect driving data via smartphone app.
2. Simulate additional driving behaviors in CARLA.
3. Train and test ML models.
4. Deploy system to analyze and classify new driving sessions.
5. Visualize analytics on the web dashboard.

## Commercialization Potential

- **Fleet Management**: Monitor driver behavior at scale
- **Insurance Telematics**: Adjust premiums based on actual driving behavior
- **Automotive R&D**: Inform design improvements
- **Consumer App**: Feedback and coaching for individual drivers

Revenue streams include B2B licensing, freemium consumer models, and data analytics services.

## Contributors

- **Munasinghe M.M.A.D.** – Developer, Researcher  
- **Supervisor**: Mr. H. M. Samadhi Chathuranga Rathnayake  
- **Co-Supervisor**: Ms. Supipi Karunathilaka

---

© 2025 Sri Lanka Institute of Information Technology
