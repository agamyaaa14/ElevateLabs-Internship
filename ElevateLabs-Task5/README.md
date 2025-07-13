# ElevateLabs Internship 
## Task 5: Decision Trees and Random Forests

### 🔍 Objective:
To learn and apply tree-based models (Decision Trees and Random Forests) for classification tasks using Python and scikit-learn.

---

### 📌 What This Project Includes:

1. **Decision Tree Classifier**
   - Trained a basic decision tree model on the `heart.csv` dataset.
   - Visualized the tree using `plot_tree()` with `max_depth=3`.

2. **Overfitting Control**
   - Compared accuracy between an unpruned tree and a tree with controlled `max_depth=4`.

3. **Random Forest Classifier**
   - Trained a random forest model and compared its performance with the decision tree.

4. **Feature Importance**
   - Visualized which features contributed most to model predictions using a barplot.

5. **Cross-Validation**
   - Performed 5-fold cross-validation on the Random Forest for robust evaluation.

---

### 📊 Results Summary:

| Model                    | Accuracy |
|--------------------------|----------|
| Decision Tree (Default)  | 0.9854   |
| Pruned Tree (max_depth=4)| 0.8000   |
| Random Forest            | 0.9854   |
| Random Forest (CV avg)   | 0.9971   |

---

### 📘 Interpretation:
- Default Decision Tree and Random Forest have very high accuracy (~98.5%), but the random forest is more stable due to ensemble averaging.
- Pruned Tree shows how limiting depth can reduce overfitting but may also underfit.
- Cross-validation confirms the generalization strength of the Random Forest.

---

### 🛠 Tools Used:
- Python
- scikit-learn
- pandas
- matplotlib
- seaborn
