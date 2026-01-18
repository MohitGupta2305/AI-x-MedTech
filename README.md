# AI-x-MedTech
An interactive clinical intake and patient safety dashboard built using Gradio, Plotly, and Python.
This project demonstrates how AI-assisted workflows can support risk assessment, compliance checks, and patient monitoring in healthcare and pharmacovigilance contexts.
Disclaimer: This application uses synthetic data only and is intended for demo, academic, and prototyping purposes. It is not a medical device and should not be used for real clinical decision-making.
Overview

The MedTech Intake & Safety Dashboard simulates a modern medical safety intake system that:

Displays structured patient demographics and medical history

Presents unstructured clinical intake narratives

Highlights medication-related risks

Detects missing compliance information

Tracks patient vitals over time

Supports case workflow progression with clear auditability

This project focuses on explainability, usability, and safety-first design, aligned with regulated healthcare environments.

Key Features:
Patient Intake & Context

Patient name, status, demographics, and medical history

Unstructured intake narrative display

Current medication list with associated risk levels
Risk & Compliance Assessment

Rule-based risk score card

Transparent supporting risk factors

Automated detection of missing intake information:

Dose

Symptoms

Onset date

Vitals Monitoring

Interactive time-series visualization of:

Heart Rate

Systolic Blood Pressure

Diastolic Blood Pressure

Built using Plotly for unified hover and readability
Workflow & Case Tracking

Case lifecycle stages:

Initial Intake

Criteria Check

Initiate Follow-Up

Case Complete

Action buttons for follow-up and case closure
System Logging & Auditability

Expandable system logs

Designed to support explainability and traceability
Tech Stack

Python 3.9+

Gradio – Interactive UI framework

Plotly Express – Data visualization

Pandas – Data handling

NumPy – Synthetic data generation
Tech Stack

Python 3.9+

Gradio – Interactive UI framework

Plotly Express – Data visualization

Pandas – Data handling

NumPy – Synthetic data generation
Installation & Setup
Clone the Repository
git clone https://github.com/your-username/medtech-intake-safety-dashboard.git
cd medtech-intake-safety-dashboard
Install Dependencies
pip install gradio pandas numpy plotly
Run the Application
python app.py
The dashboard will launch locally in your browser.
Data Notes

All patient data is synthetically generated

Vitals are simulated using statistical distributions

No external APIs or EHR systems are connected

Safe for public demos, hackathons, and academic use
Use Cases

Healthcare AI demos

Pharmacovigilance workflows

Medical informatics projects

Academic research prototypes

Hackathons and innovation challenges
