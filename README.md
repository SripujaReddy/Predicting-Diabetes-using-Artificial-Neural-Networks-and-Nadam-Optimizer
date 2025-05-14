# Predicting Diabetes Using Artificial Neural Networks

## Author
**Sripuja Chennuri**  

## Project Overview
This project focuses on predicting the likelihood of diabetes in individuals using an **Artificial Neural Network (ANN)** model trained on real-world medical and lifestyle data. The approach leverages deep learning to identify complex patterns in health metrics and classify whether a person is at risk of diabetes.

## Model Highlights
- **Model Type:** Artificial Neural Network (ANN)
- **Optimizer Used:** Nadam (Nesterov-accelerated Adaptive Moment Estimation)
- **Final Accuracy:** ~96%
- **Final Loss:** ~11%

## Dataset
- **Source:** Kaggle (Pima Indians Diabetes dataset - extended version)
- **Features Used:**
  - Age
  - Gender
  - Smoking Habit
  - Body Mass Index (BMI)
  - Glucose Level
  - Hypertension
  - Heart Disease
  - HbA1c Level (3-month average blood sugar)

- **Target:** Binary classification (Diabetic: `1`, Non-diabetic: `0`)

##  Key Techniques
- Multiple dense layers for feature learning
- Dropout regularization to reduce overfitting
- Early stopping and validation for better generalization
- Learning rate tuning for performance improvement

## Implementation Notes
- Initial experiments were conducted using the Adam optimizer (~94% accuracy).
- Switching to Nadam with fine-tuned learning rate led to improved results (~96% accuracy, ~11% loss).
- The ANN was trained on a cleaned and pre-processed dataset to ensure robustness.

## Future Scope
- **Model Improvements:** Experiment with deeper or alternative architectures.
- **Enhanced Evaluation:** Include metrics like precision, recall, and F1-score.
- **Data Expansion:** Incorporate additional lifestyle factors such as diet, physical activity, and family history.
- **Explainability:** Use tools like SHAP or LIME to visualize feature importance.
- **Real-World Use:** Deploy the model in a user-friendly app for medical practitioners or individuals.

## Conclusion
This project successfully demonstrates how deep learning can be applied to medical data for early disease detection. With careful tuning and optimization, ANNs can deliver strong performance and help in real-life decision-making in healthcare.
