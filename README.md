# 🌟 Gradient Boosting Regressor - Step-by-Step Implementation

This project demonstrates a step-by-step implementation of the **Gradient Boosting Regressor** from scratch using a simple quadratic dataset. It helps visualize how boosting works by sequentially reducing residual errors using decision tree regressors.

## 📌 Project Highlights

- 🔢 Synthetic data generation using a quadratic relationship
- 🧠 Manual boosting through:
  - Initial prediction using mean (M1)
  - Residual calculation
  - Fitting trees to residuals (M2, M3)
- 📊 Visualization of predictions after each boosting step
- 📈 Demonstrates boosting using a learning rate = 1 for simplicity

## 🛠️ Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `sklearn.tree.DecisionTreeRegressor`

## 📈 Visual Workflow

1. **Data Generation**
   - A quadratic dataset is created with some added noise.

2. **Step 1 - Initial Model (M1)**
   - Uses the mean of the target values as a baseline prediction.
   - Residuals (`res1`) are calculated.

3. **Step 2 - First Tree (M2)**
   - A decision tree regressor is fit to `res1`.
   - Updated predictions are generated.

4. **Step 3 - Second Tree (M3)**
   - Another decision tree is fit on new residuals (`res2`) from M2.
   - Final predictions are the sum of all models.

## ✅ Conclusion

This project helps understand the **intuition behind Gradient Boosting** by manually constructing a sequence of models that learn from previous errors. It’s ideal for those starting with ensemble methods and wanting to learn beyond the scikit-learn abstraction.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

