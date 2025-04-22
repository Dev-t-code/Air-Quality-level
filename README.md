# Air-Quality-level

# Air Quality Level Prediction

This project uses machine learning to predict the air quality level based on key environmental indicators such as PM2.5, NO2, and temperature.

## 📁 Files Included
- `air_quality_prediction.ipynb`: The main Jupyter notebook with the full code.
- `Air_Quality_Prediction_Report.docx`: A detailed project report in DOCX format.
- `Air_Quality_Prediction_Report.pdf`: A PDF version of the project report.
- `README.txt`: This file.

## 🛠️ Technologies Used
- **Python**
- **Pandas** for data manipulation
- **Scikit-learn** for machine learning models and metrics
- **Seaborn** and **Matplotlib** for visualization

## ⚙️ How It Works
1. Upload a CSV dataset containing the columns: `pm25`, `no2`, `temperature`, and `quality_level`.
2. The script encodes the target variable and splits the dataset into training and testing sets.
3. A Random Forest classifier is trained to predict the air quality level.
4. Performance is evaluated using accuracy, precision, recall, and a confusion matrix.
5. The script allows prediction based on user-input environmental data.

## 📊 Input Features
- `pm25`: PM2.5 concentration
- `no2`: Nitrogen dioxide level
- `temperature`: Temperature in degrees Celsius

## 🧪 Output
- Predicted air quality level (e.g., Good, Moderate, Poor, etc.)
- Performance metrics of the model
- A visual confusion matrix for evaluation

## 🚀 Run It Yourself
Make sure to install required libraries if running outside Google Colab:

```bash
pip install pandas scikit-learn seaborn matplotlib
```

Run the script in a Jupyter notebook or upload it to Google Colab and execute cell by cell.

## 👤 Author
- Name: [Your Name]
- Roll No: [Your Roll Number]

## 📄 License
This project is developed for educational purposes.
