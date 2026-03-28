# LLM-Assisted Traffic Incident Analysis and Decision Support System

## Overview
This project presents a hybrid AI system that converts unstructured traffic incident descriptions into structured insights and actionable traffic management decisions.

## Problem
Traffic incident data is often unstructured (e.g., text reports, logs), making it difficult to quickly interpret and respond.

## Solution
This system uses:
- A Large Language Model (LLM) to classify incident types
- Rule-based logic to extract features (severity, lane blockage)
- A decision engine to recommend traffic control strategies

## System Pipeline
Text Input → LLM Classification → Feature Extraction → Decision Logic → Output

## Example

**Input:**
Accident blocking two lanes with heavy congestion

**Output:**
- Incident Type: accident  
- Severity: high  
- Lanes Blocked: 2  
- Decision: Reroute traffic + emergency response  

## Technologies Used
- Python
- HuggingFace Transformers
- Pandas

## Key Features
- Hybrid AI system (LLM + rule-based logic)
- Interpretable and structured outputs
- Extendable for real-world traffic systems

## Limitations
- Uses a small open-source model (limited accuracy)
- Can be improved with larger models or fine-tuning

## Future Work
- Integrate real-time traffic data
- Improve classification accuracy
- Build a dashboard (Streamlit)

## Author
Jaykumar Bagaria
