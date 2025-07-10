# ML-Random_Forest_Regression

The Jupyter notebook titled poly_linear Regression.ipynb appears to implement both linear regression and polynomial regression on a small dataset of job positions and their corresponding salaries.

---

📌 1. Importing Libraries

These are standard libraries used for numerical operations (numpy), data handling (pandas), and visualization (matplotlib).


---

📁 2. Loading the Dataset 

The dataset Position_Salaries.csv contains three columns:

Position: Job title (e.g., CEO, Manager).

Level: Numeric representation of hierarchy (1 to 10).

Salary: Corresponding salary values.


Here’s a sample of the data:

Position	Level	Salary

Business Analyst	1	45000
Junior Consultant	2	50000
...	...	...
CEO	10	1000000

---

📊 3. Feature and Target Variable Selection


x: Independent variable (Level).

y: Dependent variable (Salary).

---

I'll now analyze the rest of the notebook to describe how the linear and polynomial regression models are built, trained, and visualized.

📈 4. Initial Visualization

A scatter plot of Level vs Salary is shown to visualize the non-linear relationship between them.

---

🔧 5. Polynomial Regression Model fitting

Transforms the x values into polynomial features up to degree 5.

For example, x = 3 becomes [1, 3, 9, 27, 81, 243].

---

🧠 6. Training the Model

A LinearRegression model is fit using the polynomial-transformed features.

The model now captures non-linear patterns.

---

📉 7. Visualization of the Polynomial Curve

Overlays the polynomial regression curve (in red) on the scatter plot.

This helps visualize how well the model fits the data.

---

🔮 8. Prediction for a New Value (Manual Entry)

Predicts the salary for Level 11 using the trained model.

---

🧑‍💻 9. User Input for Prediction

Accepts user input via the console, transforms it, and prints the predicted salary.

---

✅ Summary

This notebook performs:

Data visualization

Polynomial feature engineering (degree 5)

Polynomial regression model training

Graphical evaluation of fit

Predictions for both hardcoded and user-provided inputs

