# 10 Academy - KAIM - Week 3: End-to-End Insurance Risk Analytics & Predictive Modeling

## 🎯 Business Objective
[cite_start]This project aims to help AlphaCare Insurance Solutions (ACIS) [cite: 15] [cite_start]optimize its car insurance marketing strategy and discover **"low-risk" targets**[cite: 17]. [cite_start]The ultimate goal is to allow ACIS to reduce premiums for these segments to attract new clients, leveraging cutting-edge risk and predictive analytics[cite: 15, 17].

## 📅 Key Dates
* [cite_start]**Challenge Introduction:** Wednesday, 03 Dec 2025 (10:30 AM UTC) [cite: 130]
* [cite_start]**Interim Submission (Tasks 1 & 2):** Sunday, 07 Dec 2025 (8:00 PM UTC) [cite: 130]
* [cite_start]**Final Submission (All Tasks):** Tuesday, 09 Dec 2025 (8:00 PM UTC) [cite: 130]

## 🛠️ Project Setup and Dependencies

To run this project locally, follow these steps:

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/acis-insurance-risk-analytics.git](https://github.com/your-username/acis-insurance-risk-analytics.git)
    cd acis-insurance-risk-analytics
    ```

2.  **Create and Activate a Virtual Environment**
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Linux/macOS
    # .venv\Scripts\activate   # On Windows
    ```

3.  **Install Dependencies**
    The necessary libraries (pandas, scikit-learn, etc.) are listed in `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```

## 📂 Repository Structure
* `data/`: Contains the raw and processed datasets (tracked via DVC).
* `notebooks/`: For Exploratory Data Analysis (EDA) and initial model prototyping.
* [cite_start]`src/`: Modular and object-oriented Python code for statistical modeling and pipelines[cite: 117].
* `.github/workflows/`: Configuration files for GitHub Actions (CI/CD).
* `reports/`: Final report and presentation materials.

## 📈 Tasks Overview
| Task | Focus Area | Deliverables |
| :--- | :--- | :--- |
| **Task 1** | Git, GitHub, & EDA | [cite_start]Dev Environment Setup, Initial Risk/Profitability Patterns [cite: 135, 144] |
| **Task 2** | Data Version Control (DVC) | [cite_start]Auditable Data Pipeline Setup [cite: 184] |
| **Task 3** | A/B Hypothesis Testing | [cite_start]Statistical validation of risk drivers (e.g., provinces, gender) [cite: 220, 221] |
| **Task 4** | Statistical Modeling | [cite_start]Predictive models for Claim Severity and Premium Optimization [cite: 234, 239] |