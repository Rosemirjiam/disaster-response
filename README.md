# disaster-response

# Project Overview

This project is about building a **Disaster Response Decision Support System (DSS)** that helps organizations like the Red Cross respond more effectively during emergencies. When disasters happen, many people need help at the same time, but resources are limited. This system helps prioritize requests so that the most critical cases are handled first.



# Objectives

To create a system where affected people can request help
  To prioritize requests based on urgency and need
  To allocate limited resources efficiently
  To reduce delays and improve fairness in disaster response
 To support decision-makers with data-driven insights



# Tools and Technologies

  Python 
  Pandas 
  Streamlit 
  NumPy 
  Matplotlib 



# =Project Structure

The system is divided into three main parts:

1. Input Layer

    Users submit requests (location, severity, urgency, etc.)

2. Processing Layer

    Data is cleaned and analyzed
    Priority scores are calculated

3. Output Layer

   Results are displayed
    Requests are ranked based on urgency


# Data Processing

* A dataset with over 6,000 entries was created
* Data includes:

  Severity
    Vulnerability
   Urgency
  Data was cleaned to remove errors and ensure consistency
 Values were standardized to make calculations easier



# Exploratory Data Analysis (EDA)

EDA was used to understand the dataset before building the model:

Checked distribution of severity and urgency levels
  Identified patterns in high-risk cases
  Compared different factors affecting priority
 Helped confirm that severity should have the highest weight



# Machine Learning / Decision Model

Instead of a complex ML model, a **weighted scoring model** was used:

Priority Score = (0.5 × Severity) + (0.3 × Vulnerability) + (0.2 × Urgency)

Why this approach:

Simple and easy to understand
   Transparent decision-making
  Works well for real-time systems



# Results

* The system successfully ranks requests based on priority
* High-risk cases are identified quickly
* Decision-making becomes faster and more consistent
* Reduces human bias in resource allocation

---

# Key Insights

Severity is the most important factor in disaster response
 Combining multiple factors gives better decisions than using one
 Simple models can still be very effective
 DSS can significantly improve emergency response efficiency



# Future Improvements

 Use **real-world disaster data
  Add **machine learning models (e.g., predictive analytics)
  Integrate **GPS tracking for location accuracy
   Develop a **mobile app version*
Connect directly with organizations like NGOs



# Contributors
Ivyn Bipa
Rose Mirgin
Allan



#Conclusion

This project shows how a simple Decision Support System can make a big difference in disaster response. By using data and structured decision-making, the system ensures that help is given to those who need it most. Even though it is a basic model, it provides a strong foundation for building more advanced and real-world solutions in the future.

 
