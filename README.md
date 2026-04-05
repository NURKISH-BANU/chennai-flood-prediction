
# Flood-First Chennai: Using AI to Predict Floods and Save Lives

## Overview

Flood-First Chennai is an AI-driven system designed to predict urban flooding at a **ward level** and assist emergency teams in making **prioritized evacuation decisions**. Unlike traditional flood warning systems that provide city-wide alerts, this project focuses on **when, where, and who needs help first**.

## Problem Statement

Chennai experiences severe flooding during the Northeast monsoon season. Existing systems:
* Provide only **city-level alerts**
* Do not specify **which areas will flood first**
* Lack **prioritization for vulnerable populations**

This results in delayed and inefficient emergency response.

## Proposed Solution

Our system addresses these challenges by:

* Predicting **ward-level flooding timelines**
* Modeling **flood spread between regions**
* Prioritizing evacuation based on **dynamic vulnerability scores**

## Key Features

* Time-based Flood Prediction** (4–6 hours early warning)
* Ward-level Analysis** (200+ wards in Chennai)
* Flood Spread Modeling**
* Vulnerability-based Prioritization**
* Dynamic Scoring** (based on time of day, population, etc.)

## Methodology

* Used **LSTM (Long Short-Term Memory)** model for time-series prediction
* Trained on historical flood data (2015, 2021, 2023)
* Inputs include:

* Rainfall data
* Geographic and elevation data
* Population and infrastructure data

## Results

* ~70% accuracy in predicting flooded areas
* 4–6 hours early flood warning
* Effective identification of high-risk and vulnerable regions

## Evaluation

* Historical Validation**: Tested using past flood events
* Real-time Testing (Planned)**: Volunteer-based validation during live monsoon conditions

## Output Example

**URGENT - Evacuate Now:**

1. Saidapet Ward – floods in 3 hours, high elderly population
2. Velachery Ward – floods in 4 hours, contains schools

**Prepare to Evacuate:**
3. Mylapore Ward – floods in 7 hours

## Impact

* Improves **decision-making for emergency teams**
* Enables **faster and smarter evacuations**
* Helps reduce **loss of life during floods**

## Future Work

* Integration with **real-time IoT sensors**
* Mobile app for **public alerts**
* Expansion to other flood-prone cities

## Tech Stack

* Python
* TensorFlow / Keras
* Pandas, NumPy
* GIS Data Processing

## Conclusion

Flood-First Chennai transforms flood prediction into a **practical decision-support system**, bridging the gap between prediction and real-world action.
