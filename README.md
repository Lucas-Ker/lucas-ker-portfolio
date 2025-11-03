Read this README in [Português 🇧🇷](README.pt.md).

# Data Science Portfolio — Lucas Ker

Hello! This is my portfolio hub, showcasing client-ready deliverables and linking to full, in-depth technical projects. My work focuses on building reproducible analytics pipelines that turn raw data into clear business actions.

---

## 1. Client-Ready Deliverables

These are concise, polished assets ready for review.

* **`reports/Olist_Executive_Summary.pdf`**
    A 1-page, non-technical PDF report summarizing the key findings and actionable recommendations from the Olist project.

* **`notebooks/Olist_Client_Highlights.ipynb`**
    A clean Jupyter Notebook that demonstrates the project's top 3 insights (Logistics, RFM, and Predictive Model) in a 2-minute, runnable format.

* **`notebooks/Stats_for_Business_Client.ipynb`**
    A practical guide demonstrating how to use statistical tests (T-test, ANOVA, Chi-Square) to answer common business questions.

---

## 2. How to Run These Notebooks

You can run the "Client-Ready" notebooks locally.

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/Lucas-Ker/lucas-ker-portfolio.git
    cd lucas-ker-portfolio
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Download the Processed Data:**
    * The Olist notebook runs on processed `.parquet` files.
    * **[Click here to download the data (3 files, ~30 MB) from Google Drive](https://drive.google.com/drive/folders/1UexfcZOujLVO8-RzY0O__pdOaewW9uVI?usp=drive_link)** 
    * Create a `data/` folder in the root of this project.
    * Place the 3 downloaded `.parquet` files inside the `data/` folder.

5.  **Run Jupyter:**
    ```bash
    jupyter lab
    ```
    Now you can open and run the notebooks in the `notebooks/` folder.

---

## 3. Deep-Dive Technical Projects

These are the complete, multi-notebook repositories where the technical work was performed.

### Full Project: E-commerce Analysis (Olist)
* **Repository: [https://github.com/Lucas-Ker/olist-data-analysis-project](https://github.com/Lucas-Ker/olist-data-analysis-project)**

* **What it is:** The complete 5-notebook pipeline, from raw data ingestion and ETL to statistical testing, RFM/K-Means segmentation, and predictive modeling (Random Forest & Prophet).

* **Key Result:** A prototype model that flags orders with high risk of negative reviews, achieving **68% recall** on the test set.

### Practical Guide: Statistics for Data Science

* **Repository: [https://github.com/Lucas-Ker/stats_for_data_science](https://github.com/Lucas-Ker/stats_for_data_science)**

* **What it is:** A hands-on guide to statistical concepts, from foundational theory to practical application in Python.

---

## 4. Contact / Hire Me

* **Upwork:**[Upwork link]()

* **LinkedIn:** [https://www.linkedin.com/in/lucas-ker/](https://www.linkedin.com/in/lucas-ker/)

* **Email:** [lucasker0107@gmail.com](mailto:lucasker0107@gmail.com)
