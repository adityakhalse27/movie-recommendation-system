# 🎬 Netflix Movie Success Prediction

## 📌 Project Overview

This project predicts whether a movie will be a **Hit or Flop** using Machine Learning techniques.
The model is trained on streaming platform data and movie attributes.

 🎯 Objective

To build an end-to-end machine learning model that can classify movies based on their success using features like release year and platform availability.

📊 Dataset

* Source: Movies on Streaming Platforms
* Total Records: ~9500
* Features Used:

  * Year
  * Netflix
  * Hulu
  * Prime Video
  * Disney+
  * Rotten Tomatoes (for target creation)

⚙️ Data Preprocessing

* Removed missing values and duplicates
* Cleaned inconsistent formats in Rotten Tomatoes column (%, 98/100)
* Converted ratings into numeric format

🧠 Feature Engineering

* Created a **target variable**:

  * `1 = Hit (>= 70%)`
  * `0 = Flop (< 70%)`

🤖 Models Used

* Random Forest Classifier ✅ (Best)
* Logistic Regression (for comparison)
* Decision Tree (optional)

 📈 Model Evaluation

* Accuracy Score used for evaluation
* Confusion Matrix to analyze performance


 📊 Results

* Random Forest Accuracy: **~78%**
* Logistic Regression Accuracy: Slightly lower
* Random Forest performed best

 🔍 Key Insights

* Release year has strong impact on predictions
* Platform availability (Netflix, Prime, etc.) influences success
* Data quality plays a crucial role in model performance

🚀 Future Improvements

* Add more features like genre, cast, director
* Use advanced models (XGBoost, Gradient Boosting)
* Deploy model using Streamlit

 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

 📌 Conclusion

This project demonstrates a complete machine learning pipeline including data cleaning, feature engineering, model building, and evaluation.
The model successfully predicts movie success with good accuracy.



🙋‍♂️ Author

Aditya Khalse
