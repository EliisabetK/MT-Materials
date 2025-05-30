# Metamorphic Testing Lab Package

This repository contains all of the relevant materials and code for developing a software testing lab as part of a bachelor's thesis at the University of Tartu. The lab introduces students to metamorphic testing using tasks involving scientific computation and machine learning models. 

## Contents

- **`Lab Materials/`**  
  Materials used during the original lab session held on April 8–9:
  - Student and TA instructions  
  - Lab session slides  
  - ZIP file provided to students

- **`Improved Materials/`**  
  Revised materials based on the feedback from the students and instructors. These are intended for use in future lab sessions:
  - Updated student instructions  
  - Updated TA instructions
 
- **`Feedback Lab 7`**
  Feedback form sent out to the students after the homework deadline.

### The following folders (Task1 and Task2) are not available for confidentiality reasons. They can be made available on request.

- **`Task1/`** — *Braking Distance Calculator (Java)*  
  - `src/main/java/` — Contains the braking distance calculator implementations, a CLI entry point, and the shared interface  
  - `src/test/java/` —  
    - Test suite template given to the students  
    - A completed test suite version as a reference

- **`Task2/`** — *Traffic Sign Classifier (Python)*  
  - `data/` — Includes the training and test datasets and label files  
  - `models/` — Four trained models for student evaluation  
  - `testing/` —  
    - `MT_testing.py` —  Metamorphic tests for all of the trained models  
    - `students_file.py` — Test suite template provided to the students  
    - `testing.py` — Computes F1 scores for the models  
  - `training/` — Python scripts used to train each model  
    - Each file includes a comment for which model it trains

## Author
Eliisabet Kaasik
University of Tartu, 2025
