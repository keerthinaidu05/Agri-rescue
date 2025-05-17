# Smart Farming Recommendation System

This project leverages machine learning to provide recommendations for crop selection, fertilizer usage, and plant disease detection. It is designed to assist farmers and agricultural professionals in making informed, data-driven decisions.

## Project Structure

```
Working Project Fram/
├── .gitignore
├── requirements.txt
├── app/
│   ├── app.py
│   ├── config.py
│   ├── Data/
│   ├── static/
│   ├── templates/
│   └── utils/
├── Data-processed/
│   ├── crop_recommendation.csv
│   └── fertilizer.csv
├── Data-raw/
│   ├── cpdata.csv
│   ├── Fertilizer.csv
│   ├── FertilizerData.csv
│   ├── MergeFileCrop.csv
│   └── raw_districtwise_yield_data.csv
├── models/
│   ├── DecisionTree.pkl
│   ├── NBClassifier.pkl
│   ├── plant_disease_model.pth
│   ├── RandomForest.pkl
│   ├── SVMClassifier.pkl
│   └── XGBoost.pkl
└── notebooks/
```

## Features

- **Crop Recommendation:** Suggests optimal crops based on soil and environmental data.
- **Fertilizer Recommendation:** Recommends fertilizers tailored to crop and soil needs.
- **Plant Disease Detection:** Identifies plant diseases from images using deep learning.
- **Web Application:** User-friendly interface for input and results.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip

### Installation

1. **Clone the repository:**
    ```sh
    git clone <repository-url>
    ```

2. **Install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the application:**
    ```sh
    cd "app"
    python app.py
    ```

4. **Access the app:**
    Open your browser and go to `http://localhost:5000`

## Data

- **Raw Data:** `Data-raw/`
- **Processed Data:** `Data-processed/`
- **Pre-trained Models:** `models/`


## Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

