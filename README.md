# AI-Driven Employee Relocation Optimization System


## Overview

This project aims to intelligently predict employee suitability for relocation and optimize the assignment of suitable employees to available job locations. Using machine learning and optimization algorithms, the system enhances decision-making in human resource management by automating the relocation process based on key performance and preference indicators.

---

## Objective

The primary goal is to build a predictive and optimization framework that:

* Identifies employees who are likely suitable for relocation.
* Optimally assigns them to available locations considering performance, satisfaction, and location priority.
* Improves workforce allocation while minimizing employee dissatisfaction and operational cost.

---

## Key Features

* **Synthetic Employee Dataset Generation**: Creates realistic employee data including attributes like age, department, years at company, performance rating, job satisfaction, and willingness to relocate.
* **Relocation Suitability Prediction**: Trains a machine learning model to predict whether an employee is suitable for relocation.
* **Label Encoding**: Encodes categorical department data for model training.
* **Relocation Location Simulation**: Generates hypothetical job locations with priority levels.
* **Optimization Engine**: Implements the Hungarian Algorithm to match suitable employees with optimal job locations based on a custom cost function.
* **Reporting**: Displays a classification report and final relocation assignments.

---

## Technologies Used

* Python
* pandas
* numpy
* scikit-learn
* scipy
* Jupyter Notebook / Python Script

---

## Use Cases

* **Human Resource Management**: Automated assistance for HR departments in making relocation decisions.
* **Workforce Planning**: Efficient employee-to-location matching for project-based or expanding businesses.
* **Employee Retention**: Relocating unsatisfied but high-performing employees to new opportunities.
* **Decision Support**: Provides data-driven insights to management for internal mobility and resource optimization.
