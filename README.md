# Simple-Linear-Regression-Implementation-from-Scratch
Implemented Linear Regression without using any ML library and have visualized scatterplot of dataset,Regression plot and Cost function.
I have find out weights and biased manually using formula of cost function.Made a simple model prepare to predict perfectly.



# 📈 Simple Linear Regression — From Scratch

A clean implementation of **Linear Regression without any ML library**, built entirely with Python using mathematical derivations of the cost function. Includes full data visualization for the dataset, regression fit, and cost function curve.

---

## 🚀 Overview

This project demonstrates how linear regression works **under the hood** — no `scikit-learn`, no shortcuts. The weight and bias are computed manually using the **Mean Squared Error (MSE)** cost function and its analytical solution.

---

## ✨ Features

- ✅ Linear Regression implemented from scratch (no ML libraries)
- ✅ Weight and bias calculated manually using cost function formulas
- ✅ Trained and evaluated on a **real-world CSV dataset**
- ✅ Three visualizations:
  - 📊 **Scatter plot** of the raw dataset
  - 📉 **Regression line** plotted over the data
  - 📐 **Cost function curve** to show model convergence


Visit Link : [Visit Notebook](https://colab.research.google.com/drive/1gEiJamqQQNNovzjaJiVINAiVNACUUfox?usp=sharing)


## 🧮 Math Behind It

The model predicts:

$$\hat{y} = w \cdot x + b$$

The **cost function** (Mean Squared Error):

$$J(w, b) = \frac{1}{n} \sum_{i=1}^{n} (\hat{y}_i - y_i)^2$$

Weight and bias are derived analytically:

$$w = \frac{\sum (x_i - \bar{x})(y_i - \bar{y})}{\sum (x_i - \bar{x})^2}, \quad b = \bar{y} - w\bar{x}$$

---

## 📊 Visualizations

| Plot | Description |
|------|-------------|
| Scatter Plot | Raw data points from the CSV dataset |
| Regression Line | Best-fit line overlaid on the scatter plot |
| Cost Function Curve | How MSE changes with varying weights |

---
<img width="588" height="457" alt="image" src="https://github.com/user-attachments/assets/2367ff7a-4928-4ac1-a5f5-06326504a44a" />
<img width="646" height="541" alt="image" src="https://github.com/user-attachments/assets/8a5eb3c7-557c-4082-bdf0-5249d7eef51a" />
<img width="651" height="520" alt="image" src="https://github.com/user-attachments/assets/f8135c32-b20d-4399-b60e-bc8ca0b383e3" />

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Pandas | Loading and handling the CSV dataset |

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Simple-Linear-Regression-From-Scratch.git
   cd Simple-Linear-Regression-From-Scratch
   ```

2. **Install dependencies**
   ```bash
   pip install numpy matplotlib pandas
   ```

3. **Run the project**
   ```bash
   python main.py
   ```

---

## 📌 Key Concepts Covered

- Understanding the cost/loss function
- Deriving weights and bias analytically (closed-form solution)
- Visualizing model performance
- Building an ML model without any ML framework

---

## 🙌 Author

**Azmain**
CSE Student | Jagannath University, Bangladesh
Passionate about ML, Data Science, and building things from scratch.

> *"The best way to understand an algorithm is to build it yourself."*
