# Iris Flower Classification

This project involves classifying iris flowers into three species (Iris-setosa, Iris-versicolor, and Iris-virginica) based on their physical attributes using various classification algorithms. The dataset used contains 150 iris flowers with four features: Sepal Length, Sepal Width, Petal Length, and Petal Width.

## Steps

1. **Data Preprocessing:**
   - Loaded the Iris dataset.
   - Dropped the unnecessary `Id` column.
   - Checked for null values and obtained a statistical summary of the dataset.
   - Visualized data distribution using Seaborn's `countplot` and `pairplot`.
   - Generated a heatmap to visualize feature correlations.

2. **Feature Engineering:**
   - Separated the dataset into features (`X`) and target labels (`Y`).
   - Scaled feature variables using `StandardScaler`.
   - Encoded target labels using `LabelEncoder`.

3. **Modeling:**
   - Split the dataset into training (80%) and testing (20%) sets.
   - Trained and evaluated three classification models:
     - **Support Vector Machine (SVC):** Achieved 100% accuracy.
     - **Random Forest Classifier:** Achieved 97% accuracy.
     - **Naive Bayes Classifier:** Achieved 97% accuracy.

4. **Results:**
   - **Support Vector Machine:** 100% accuracy.
   - **Random Forest Classifier:** 97% accuracy.
   - **Naive Bayes Classifier:** 97% accuracy.
   - The Support Vector Machine was the best-performing algorithm.

## Libraries Used:
- `pandas`, `numpy` for data manipulation.
- `matplotlib`, `seaborn` for visualization.
- `scikit-learn` for preprocessing, model training, and evaluation.

## Conclusion:
The Support Vector Machine performed the best with 100% accuracy in classifying iris species. 
