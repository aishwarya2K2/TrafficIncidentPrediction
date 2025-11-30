# TrafficIncidentPrediction

# Traffic Incident Prediction Using Machine Learning and Deep Learning Models  

---

## Project Overview

This project addresses **traffic incident prediction** through machine learning (ML) and deep learning (DL) models. Our system is designed around **four key research questions (RQs)** that cover different aspects of crash risk prediction, crash severity analysis, clustering of roadway segments, and time-series modeling.

### Research Questions:

- **RQ1:** Can we predict monthly crash counts using historical climate and traffic patterns with LSTM and ARIMA models?
- **RQ2:** Which environmental and structural factors most influence traffic crash severity, and how do different machine learning models compare in identifying and ranking these factors?
- **RQ3:** Can we group roadway segments into crash risk clusters using environmental, traffic, and structural features to support proactive safety interventions?
- **RQ4:** Can time-series deep learning models such as LSTM effectively predict traffic crash frequency based on historical incident data, climate conditions, and roadway performance characteristics?

---

## Repository Structure

The zip folder `AIT614-Sec002_Team8_sys` contains the full project files, organized as follows:

- **Datasets_before_preprocessing/**
  - Raw datasets collected from **FHWA InfoPave** before any cleaning or processing.

- **Datasets_for_RQs/**
  - Preprocessed and cleaned datasets, ready for use in the analysis for each research question.

- **Preprocessing codes/**
  - Python scripts used to preprocess and clean the raw datasets.
  - Corresponds to the data found in `Datasets_before_preprocessing/`.

- **RQS_Codes/**
  - Python notebooks and scripts that implement models and analyses for each research question (RQ1 to RQ4).
  - **Important:** Ensure that the dataset paths in the code point to the correct files in `Datasets_for_RQs/` before running.

- **Demonstration_video/**
  - A video walkthrough demonstrating the execution of each research question.
  - **Note:** RQ1 was executed on **Google Colab** (in Python), while RQ2–RQ4 were executed on **Databricks** (using PySpark).

- **HTML_files/**
  - HTML files generated after execution of each RQ code for easy viewing of the results and workflow.

---

## Execution Instructions

1. **Setup:**
   - Ensure you have access to **Google Colab** (for RQ1) and **Databricks** (for RQ2–RQ4).
   - Upload the necessary preprocessed datasets from the `Datasets_for_RQs/` folder.

2. **Running the Codes:**
   - Open the appropriate notebook/script from `RQS_Codes/`.
   - Update dataset paths if necessary.
   - Execute the cells sequentially to reproduce the results.

3. **Understanding the Work:**
   - Refer to the **Demonstration Video** for step-by-step execution guidance.
   - Alternatively, you can view the output results in the **HTML_files/** folder.

---

## Additional Processing Step

After preprocessing the raw datasets, we **combined and selected the required columns** across multiple datasets as needed.  
The datasets were **merged accordingly based on the specific requirements** of each research question and they are also uploaded in **Datasets_for_RQs** folder.
This step ensured that each model received the correct, clean, and relevant data for accurate training, clustering, and prediction.

---

## Tools and Platforms Used

- **RQ1:**
  - Implemented in **Python**.
  - Executed on **Google Colab**.
  - Models Used: **LSTM**, **ARIMA**.

- **RQ2, RQ3, RQ4:**
  - Implemented using **PySpark**.
  - Executed on **Databricks**.
  - Techniques: Machine Learning (classification and feature importance), Clustering (KMeans), and Deep Learning (LSTM for time-series prediction).

- **Additional Libraries and Tools:**
  - TensorFlow, Keras, PySpark MLlib, scikit-learn, Matplotlib, Seaborn, Pandas, NumPy

---

## Notes

- Always ensure the **dataset paths** are correctly updated in the code before execution.
- If encountering any errors, review the demonstration video for troubleshooting steps.
- For preprocessing any new raw datasets, use the scripts provided in the **Preprocessing codes/** folder.

---



- Aishwarya Jonnagiri


---
