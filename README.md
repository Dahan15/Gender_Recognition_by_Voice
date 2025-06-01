# Gender Recognition by Voice 🎙️

A machine learning project that classifies the gender of a speaker (male or female) based on voice features using various regression and classification models.

## 📁 Project Structure

- `voice.csv`: The dataset containing extracted voice features.
- `Gender_Recognition_by_Voice.ipynb`: Main notebook with all steps from data processing to model evaluation.
- `README.md`: Project description file.

## 📊 Dataset Description

The dataset includes voice features such as:
- `meanfreq`, `sd`, `median`, `Q25`, `IQR`, `skew`, and others.
- A target column `label` indicating gender: `male` or `female`.

## 🚀 Project Workflow

1. **Importing Libraries and Data**
2. **Data Preprocessing**
   - Label encoding
   - Feature normalization
   - Train/test split
3. **Model Building**
   - Linear Regression
   - Polynomial Regression
   - Decision Tree Regressor
   - Logistic Regression
4. **Manual Logistic Regression from Scratch**
   - Implementing sigmoid, forward/backward propagation, cost function
   - Weight initialization and updates
5. **Model Evaluation**
   - Measuring classification accuracy

## 🧠 Models Used

| Model                        | Purpose                          | Result |
|-----------------------------|----------------------------------|--------|
| Linear Regression           | Basic modeling                   | --     |
| Polynomial Regression       | Capturing non-linear relations   | --     |
| Decision Tree Regressor     | Non-linear data segmentation     | --     |
| Logistic Regression (manual)| Gender classification task       | ✅     |

## 🖼️ Example Output

```python
cost after iteration 0: 0.693147
cost after iteration 10: 0.645388
cost after iteration 20: 0.601154
...

## 🧰 Requirements

Install dependencies:

pip install numpy pandas matplotlib scikit-learn

## 👨‍💻 About the Developer
This project was developed by Abdulaziz M. Dahan Ahmed. Thank you for your interest and time in reviewing this project.
