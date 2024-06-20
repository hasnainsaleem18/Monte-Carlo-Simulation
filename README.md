# Project Title: Monte Carlo Integration and Analytical Comparison

## Task 1: Estimating the Area under \( f(x) = \sqrt{\sin^2(x) + 1} \) from \( x = 0 \) to \( x = 2 \)

### Part a: Plot the Function
**Description:** Plot the function \( f(x) = \sqrt{\sin^2(x) + 1} \) from \( x = 0 \) to \( x = 2 \).

**Visualization Steps:**
1. Create a range of x-values from 0 to 2.
2. Compute the corresponding y-values using the function \( f(x) \).
3. Plot the curve using a plotting library (e.g., matplotlib).

### Part b: Monte Carlo Estimate Function
**Description:** Use the Monte Carlo technique to estimate the area under the curve.

**Steps:**
1. Define the range for x-values (0 to 2).
2. Determine the maximum y-value over the range to set the bounds for the Monte Carlo simulation.
3. Randomly generate points (darts) within the defined rectangle.
4. Count the number of points that fall below the curve.
5. Calculate the area as a fraction of points below the curve times the total area of the rectangle.

### Part c: Statistical Analysis of Monte Carlo Estimates
**Description:** Define a function that calls the Monte Carlo estimate function 1000 times and computes the mean and standard deviation of the results.

**Steps:**
1. Initialize an empty list to store the results.
2. Run the Monte Carlo simulation 1000 times, storing each result.
3. Compute the mean and standard deviation of the results using statistical methods.

### Part d: Analytical Integration
**Description:** Calculate the exact area under the curve using analytical integration.

**Steps:**
1. Set up the integral \( \int_{0}^{2} \sqrt{\sin^2(x) + 1} \, dx \).
2. Evaluate the integral using an integration tool or technique (e.g., symbolic computation).

### Part e: Percentage Error Calculation
**Description:** Find the percentage error between the analytical solution and the mean value from the Monte Carlo method.

**Steps:**
1. Compute the percentage error using the formula:
   \[
   \text{Percentage Error} = \left| \frac{\text{Analytical Solution} - \text{Monte Carlo Mean}}{\text{Analytical Solution}} \right| \times 100
   \]

---

## Task 2: Estimating the Area under \( f(x) = x^3 \) from \( x = 2 \) to \( x = 3 \)

### Part a: Plot the Function
**Description:** Plot the function \( f(x) = x^3 \) from \( x = 2 \) to \( x = 3 \).

**Visualization Steps:**
1. Create a range of x-values from 2 to 3.
2. Compute the corresponding y-values using the function \( f(x) \).
3. Plot the curve using a plotting library.

### Part b: Monte Carlo Estimate Function
**Description:** Use the Monte Carlo technique to estimate the area under the curve.

**Steps:**
1. Define the range for x-values (2 to 3).
2. Determine the maximum y-value over the range to set the bounds for the Monte Carlo simulation.
3. Randomly generate points (darts) within the defined rectangle.
4. Count the number of points that fall below the curve.
5. Calculate the area as a fraction of points below the curve times the total area of the rectangle.

### Part c: Statistical Analysis of Monte Carlo Estimates
**Description:** Define a function that calls the Monte Carlo estimate function 1000 times and computes the mean and standard deviation of the results.

**Steps:**
1. Initialize an empty list to store the results.
2. Run the Monte Carlo simulation 1000 times, storing each result.
3. Compute the mean and standard deviation of the results using statistical methods.

### Part d: Analytical Integration
**Description:** Calculate the exact area under the curve using analytical integration.

**Steps:**
1. Set up the integral \( \int_{2}^{3} x^3 \, dx \).
2. Evaluate the integral using an integration tool or technique (e.g., symbolic computation).

### Part e: Percentage Error Calculation
**Description:** Find the percentage error between the analytical solution and the mean value from the Monte Carlo method.

**Steps:**
1. Compute the percentage error using the formula:
   \[
   \text{Percentage Error} = \left| \frac{\text{Analytical Solution} - \text{Monte Carlo Mean}}{\text{Analytical Solution}} \right| \times 100
   \]

---

## Task 3: Estimating \( \int_{2}^{3} \cos(x^2) \, dx \)

### Part a: Plot the Function
**Description:** Plot the function \( f(x) = \cos(x^2) \) from \( x = 2 \) to \( x = 3 \).

**Visualization Steps:**
1. Create a range of x-values from 2 to 3.
2. Compute the corresponding y-values using the function \( f(x) \).
3. Plot the curve using a plotting library.

### Part b: Monte Carlo Estimate Function
**Description:** Use the Monte Carlo technique to estimate the integral.

**Steps:**
1. Define the range for x-values (2 to 3).
2. Determine the range of y-values to set the bounds for the Monte Carlo simulation, considering both positive and negative values.
3. Randomly generate points (darts) within the defined rectangle.
4. Count the number of points that fall above and below the curve separately.
5. Calculate the integral by considering the areas above and below the x-axis appropriately.

### Part c: Statistical Analysis of Monte Carlo Estimates
**Description:** Define a function that calls the Monte Carlo estimate function 1000 times and computes the mean and standard deviation of the results.

**Steps:**
1. Initialize an empty list to store the results.
2. Run the Monte Carlo simulation 1000 times, storing each result.
3. Compute the mean and standard deviation of the results using statistical methods.

### Part d: Analytical Integration
**Description:** Calculate the exact integral using analytical integration.

**Steps:**
1. Set up the integral \( \int_{2}^{3} \cos(x^2) \, dx \).
2. Evaluate the integral using an integration tool or technique (e.g., symbolic computation).

### Part e: Percentage Error Calculation
**Description:** Find the percentage error between the analytical solution and the mean value from the Monte Carlo method.

**Steps:**
1. Compute the percentage error using the formula:
   \[
   \text{Percentage Error} = \left| \frac{\text{Analytical Solution} - \text{Monte Carlo Mean}}{\text{Analytical Solution}} \right| \times 100
   \]
