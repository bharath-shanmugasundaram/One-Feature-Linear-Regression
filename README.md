
# 📈 One Variable Linear Regression

This project implements a simple **one-feature linear regression** model using Python and NumPy. It demonstrates the full pipeline from loading the data, visualizing the relationship, applying the linear regression algorithm, computing the cost function, optimizing parameters using gradient descent, and finally making predictions.

---

## 🧠 What You’ll Learn

- How linear regression works with a single feature.
- Implementing the hypothesis function.
- Calculating cost function (Mean Squared Error).
- Using gradient descent to optimize parameters.
- Visualizing the results using Matplotlib.

---

## 📂 Project Structure

```
One-var-linear-regression.ipynb
README.md
data.csv (optional)
```

---

## 🧪 How to Run

### 🔧 Requirements

- Python 3.x
- NumPy
- Matplotlib
- Jupyter Notebook

### ▶️ Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/one-var-linear-regression.git
   cd one-var-linear-regression
   ```

2. Install dependencies (if using virtual environment):
   ```bash
   pip install numpy matplotlib
   ```

3. Run the notebook:
   ```bash
   jupyter notebook One-var-linear-regression.ipynb
   ```

---

## 📊 Example

Given a dataset of input-output pairs (X, Y), the model will fit a line:

```
y = w * x + b
```

and adjust `w` and `b` using gradient descent to minimize the mean squared error.

---

## 📌 Key Functions

- `compute_cost(X, y, w, b)`
- `gradient_descent(X, y, w, b, alpha, iterations)`
- `predict(X, w, b)`

---

## 📎 Dataset

You can use any CSV or hardcoded dataset with one feature and one target variable. Example:

```csv
X,y
1,2
2,3
3,4
...
```

---

## 📈 Output Visualization

The notebook plots:
- Original data points
- Fitted line after training
- Cost function reduction over iterations

---

## ✅ Status

✅ Fully working  
✅ Visual outputs included  
✅ Easy to modify for different datasets

---

## 🧑‍💻 Author

**Bharath**  
_Contact for suggestions or feedback_

---

## 📄 License

This project is licensed under the MIT License.
