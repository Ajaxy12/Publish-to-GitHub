# Introduction to Linear Regression

## What is Linear Regression?

Linear regression is a statistical method that models the **linear relationship** between a dependent variable (response) and one or more independent variables (predictors).

### Key Concepts

- **Dependent Variable (Y)**: The outcome we're trying to predict
- **Independent Variable (X)**: The input or predictor variable(s)
- **Linear Relationship**: Variables follow a straight-line pattern
- **Best Fit Line**: The line that minimizes prediction errors

## Types of Linear Regression

### 1. Simple Linear Regression
- One independent variable (X) and one dependent variable (Y)
- Equation: **Y = a + bX**
  - `a` = intercept (where line crosses Y-axis)
  - `b` = slope (rate of change)

### 2. Multiple Linear Regression
- Multiple independent variables (X₁, X₂, ..., Xₙ) and one dependent variable (Y)
- Equation: **Y = a + b₁X₁ + b₂X₂ + ... + bₙXₙ**

## Why Use Linear Regression?

✓ **Interpretability** - Easy to understand relationships
✓ **Simplicity** - Straightforward to implement
✓ **Efficiency** - Fast computation
✓ **Foundation** - Basis for more complex models
✓ **Real-world applications** - Widely used in business, science, and engineering

## Common Applications

- **Economics**: Predicting GDP from various economic indicators
- **Real Estate**: House prices based on size, location, age
- **Healthcare**: Patient outcomes based on treatment variables
- **Marketing**: Sales prediction from advertising spend
- **Weather**: Temperature forecasts from atmospheric data

## When to Use Linear Regression

✓ Linear relationship exists between variables
✓ Continuous dependent variable
✓ Need interpretable results
✓ Sufficient data available

## When NOT to Use Linear Regression

✗ Non-linear relationships
✗ Categorical dependent variable (use logistic regression instead)
✗ Highly correlated independent variables (multicollinearity)
✗ Outliers severely affect the model

---

**Next**: Learn about the mathematical theory and derivations in [Theory & Concepts](./02-theory.md)
