Here's a concise README for your GitHub repository:

---

# Paychex Job Title Prediction

This project aims to predict job titles for Paychex employees based on available user data. The main objectives were to develop a model that accurately predicts job titles (OEWS codes) and to enhance our understanding of the dataset to identify effective approaches.

## Project Overview

Paychex provides human resources, payroll, and employee benefits outsourcing services. To improve its understanding of workforce data, we created a predictive model for job titles using existing employee and client data.

### Dataset

The data consists of four tables: Clients, Workers, Payments, and Products. Key features include:
- **Clients**: Information about clients/employers.
- **Workers**: Details about employees, including job titles.
- **Payments**: Payment details linked to workers.
- **Products**: Product information purchased from Paychex (not extensively used).

### Models and Approach

We explored various models, including Random Forest, Artificial Neural Networks (ANN), and K-Nearest Neighbors (KNN). The hierarchical classification approach, combining ANN and Random Forest, showed promising results. The hierarchical model achieved significant accuracy improvements compared to flat classification methods.

### Performance

- **Flat-Classification Neural Network**: Achieved around 23% accuracy.
- **Hierarchical Model**: Improved accuracy to 56% for major code classification and up to 89% for job title prediction within major codes.
- **Top-3 Job Title Prediction**: Accuracy ranged from 85% to 98% depending on major code. 

### Fairness Analysis

We performed fairness analysis related to gender and ethnicity. The model showed some bias, but the effect size was relatively small. Further investigation into biases and model adjustments is recommended.

## Repository Contents 

**Note**: Due to an agreement with Paychex, the code and data are not included in this repository, only the study that was produced as part of the capsotone project is available. For the full write-up and more details, please refer to the `PaychexCapstoneReport.pdf` in this repository.

