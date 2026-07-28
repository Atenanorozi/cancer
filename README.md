# 🫁 Lung Cancer Prediction using CRISP-DM

> پروژه داده‌کاوی سرطان ریه با استفاده از متدولوژی **CRISP-DM** و الگوریتم‌های **Machine Learning**

---

# 📌 Project Overview | معرفی پروژه

این پروژه با هدف **تحلیل داده‌های سرطان ریه (Lung Cancer Dataset)** و پیش‌بینی سطح بیماری با استفاده از تکنیک‌های **Data Mining** و **Machine Learning** انجام شده است.

در این پروژه تمام مراحل استاندارد **CRISP-DM (Cross Industry Standard Process for Data Mining)** به ترتیب پیاده‌سازی شده‌اند تا از شناخت مسئله تا ساخت و ارزیابی مدل، یک فرآیند استاندارد داده‌کاوی ارائه شود.

---

# 🎯 Project Objectives | اهداف پروژه

اهداف اصلی این پروژه عبارت‌اند از:

* بررسی و تحلیل دیتاست سرطان ریه
* شناسایی مهم‌ترین عوامل مؤثر بر سرطان ریه
* آماده‌سازی داده‌ها برای مدل‌سازی
* ساخت مدل‌های یادگیری ماشین
* مقایسه عملکرد مدل‌ها
* انتخاب بهترین مدل برای پیش‌بینی

---

# 📂 Project Structure | ساختار پروژه

```text
cancer/
│
├── data/
│   └── cancer_dataset.csv
│
├── notebooks/
│   ├── BusinessUnderstanding.ipynb
│   ├── DataUnderstanding.ipynb
│   ├── DataPreparation.ipynb
│   ├── Modeling.ipynb
│   ├── Evaluation.ipynb
│   └── Deployment.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── images/
│
├── requirements.txt
└── README.md
```

---

# 📊 Dataset | معرفی دیتاست

این دیتاست شامل اطلاعات پزشکی، سبک زندگی و عوامل محیطی بیماران است که برای پیش‌بینی سطح سرطان ریه مورد استفاده قرار می‌گیرد.

### Features

* Patient Id
* Age
* Gender
* Air Pollution
* Alcohol Use
* Dust Allergy
* Occupational Hazards
* Genetic Risk
* Chronic Lung Disease
* Balanced Diet
* Obesity
* Smoking
* Passive Smoker
* Chest Pain
* Coughing of Blood
* Fatigue
* Weight Loss
* Shortness of Breath
* Wheezing
* Swallowing Difficulty
* Clubbing of Finger Nails
* Frequent Cold
* Dry Cough
* Snoring

### 🎯 Target Variable

**Level**

این ستون نشان‌دهنده سطح (Severity) بیماری سرطان ریه است که هدف اصلی مدل‌های یادگیری ماشین پیش‌بینی آن می‌باشد.

---

# 🧩 CRISP-DM Methodology

## 1️⃣ Business Understanding

در این مرحله مسئله کسب‌وکار تعریف شده و اهداف پروژه مشخص می‌شوند.

✔ تعریف مسئله

✔ هدف داده‌کاوی

✔ شناخت نیازمندی‌ها

✔ تعیین معیارهای موفقیت

---

## 2️⃣ Data Understanding

در این بخش داده‌ها مورد بررسی اولیه قرار می‌گیرند.

موارد انجام‌شده:

* بررسی ابعاد دیتاست
* مشاهده داده‌ها
* بررسی نوع داده‌ها
* تحلیل آماری
* بررسی Missing Values
* بررسی Duplicate ها
* تحلیل توزیع داده‌ها
* Correlation Analysis
* Visualization

---

## 3️⃣ Data Preparation

در این مرحله داده‌ها برای مدل‌سازی آماده می‌شوند.

عملیات انجام‌شده:

* Data Cleaning
* حذف داده‌های تکراری
* مدیریت داده‌های گمشده
* Feature Selection
* حذف ویژگی‌های کم‌اهمیت
* Encoding
* Feature Scaling
* Train/Test Split

---

## 4️⃣ Modeling

در این مرحله مدل‌های مختلف یادگیری ماشین آموزش داده می‌شوند.

الگوریتم‌های مورد استفاده:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* XGBoost *(در صورت استفاده)*

---

## 5️⃣ Evaluation

مدل‌ها با استفاده از معیارهای زیر ارزیابی می‌شوند:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

در پایان بهترین مدل بر اساس عملکرد انتخاب می‌شود.

---

## 6️⃣ Deployment

پس از انتخاب بهترین مدل، امکان استقرار (Deployment) آن در قالب‌های زیر وجود دارد:

* Flask API
* FastAPI
* Streamlit
* Docker
* Cloud Deployment

---

# 📈 Exploratory Data Analysis (EDA)

در این پروژه تحلیل اکتشافی داده‌ها شامل موارد زیر است:

* Dataset Overview
* Summary Statistics
* Correlation Heatmap
* Feature Distribution
* Class Distribution
* Outlier Detection
* Feature Importance

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Joblib

---

# 🚀 Future Improvements

در نسخه‌های بعدی پروژه موارد زیر قابل اضافه شدن هستند:

* Hyperparameter Tuning
* Ensemble Learning
* Deep Learning Models
* Explainable AI (SHAP & LIME)
* Streamlit Dashboard
* REST API
* Docker Deployment

---

# 📊 Results

در این بخش پس از تکمیل پروژه نتایج زیر قرار خواهد گرفت:

* بهترین مدل (Best Model)
* Accuracy هر مدل
* Confusion Matrix
* ROC Curve
* Feature Importance
* Classification Report

---

# ▶️ How to Run

```bash
git clone https://github.com/Atenanorozi/cancer.git

cd cancer

pip install -r requirements.txt

jupyter notebook
```

سپس Notebookها را به ترتیب زیر اجرا کنید:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

---

# 📜 License

این پروژه صرفاً با اهداف **آموزشی و پژوهشی** توسعه داده شده است.

---

# 👩‍💻 Author

**Atena**

Data Mining | Machine Learning | Healthcare Analytics

⭐ اگر این پروژه برای شما مفید بود، لطفاً به آن یک **Star** در GitHub بدهید.
