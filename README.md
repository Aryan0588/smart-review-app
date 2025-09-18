# Smart Review App

A **sentiment analysis web application** built with Flask that predicts whether a review is **Positive** or **Negative**. The app supports both **single text input** and **bulk predictions** via CSV files and also generates a **sentiment distribution graph** for bulk data.

---

## Features

- Predict sentiment for a single text input.  
- Bulk prediction using CSV files containing multiple reviews.  
- Visualize sentiment distribution with a pie chart.  
- Preprocessing includes: lowercasing, stopwords removal, and stemming.  
- Uses pre-trained **XGBoost** model with **CountVectorizer** and **Scaler**.

---

## Getting Started

Step 1: Clone the repository
```
git clone https://github.com/Aryan0588/smart-review-app.git
```

Step 2: Open the cloned repository and create a conda environment. Activate the new environment
```
conda create -n amazonreview python=3.10
```
```
conda activate amazonreview
```

Step 3: Install the requirements file
```
pip install -r requirements.txt
```

Step 4: Run the app
```
flask --app api.py run
```

Step 5: The app will run on port 5000. 
```
localhost:5000
```

