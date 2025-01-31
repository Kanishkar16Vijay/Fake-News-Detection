# Fake News Detection

## Overview
This project aims to detect fake news using machine learning techniques. The model is trained on a dataset containing both fake and real news articles and classifies news articles accordingly.

## Project Tasks

### 1. **Exploratory Data Analysis (EDA)**
- Perform EDA on the dataset to uncover trends, patterns, and actionable insights.
- Deliverables:
  - Python code (Jupyter Notebook)
  - PDF report summarizing 5 key insights.

### 2. **Fake News Classification Model**
- Build a machine learning model to classify news as real or fake.
- Deliverables:
  - Trained model file.
  - Python code (Jupyter Notebook) for model development.
  - Performance evaluation metrics report.

### 3. **Web Interface (Optional)**
- Develop a simple web interface to allow users to check news authenticity.
- Deliverables:
  - Flask/Django web app.
  - Deployment guide.

---

## Dataset
The project uses a dataset containing:

1. **News Content**:
   - `Title`: Headline of the news article.
   - `Text`: Full content of the news article.
   - `Label`: Classification label (Fake or Real).

---

## Repository Structure
```
├── data/
│   ├── fake_news_dataset.csv
├── notebooks/
│   ├── EDA.ipynb
│   ├── Model_Training.ipynb
├── reports/
│   ├── EDA_Report.pdf
│   ├── Model_Performance.pdf
├── webapp/
│   ├── app.py
│   ├── templates/
├── README.md
```

---

## Getting Started

### Prerequisites
- Python 3.7+
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - nltk
  - Flask/Django (if deploying a web app)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/fake-news-detection.git
   cd fake-news-detection
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Upload the dataset to the `data/` directory.

---

## Usage

### Run EDA:
1. Navigate to the `notebooks/` directory.
2. Open and execute the `EDA.ipynb` notebook to perform EDA and generate insights.

### Train Fake News Detection Model:
1. Open and execute the `Model_Training.ipynb` notebook.
2. Review the model performance report in `reports/`.

### Deploy Web Interface (Optional):
1. Navigate to the `webapp/` directory.
2. Run the web application:
   ```bash
   python app.py
   ```

---

## Results
- **EDA:** Identified key trends in fake and real news articles.
- **Model:** Achieved high accuracy in classifying fake news.
- **Web Interface (Optional):** Allows users to check news authenticity in real-time.

---

## Author
Kanishkar V  
kanishvijay2005@gmail.com  
www.linkedin.com/in/kanishkar-v-3471782a2/

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

