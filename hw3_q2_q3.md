# Moksha Kumar — Numerical Methods Assignment 3 (Q2 and Q4)

**Assessment scope:** Question 2 (32 marks) and Question 4 (76 marks) only.  
**Total assessed:** 108 marks.

## Question 2 — 30.5/32

| Part | Maximum | Awarded | Comments |
|---|---:|---:|---|
| Q2.1 Define `f(x)` | 2 | 2 | Correct implementation of \(f(x)=(x-1)^2(x-2)\). |
| Q2.2 Analytic derivative | 2 | 2 | Correct derivative, \(f'(x)=3x^2-8x+5\). |
| Q2.3 Define `w(x)=f(x)/f'(x)` | 2 | 2 | Correctly defines the ratio; the simplified expression is also used later. |
| Q2.4A Plot and show the same roots | 3 | 2.5 | Both functions and the relevant roots are shown. The plot connects across the singularity at x=5/3, although the issue is correctly explained in the following part. |
| Q2.4B Show the double root becomes simple | 2 | 2 | Correctly identifies the cancellation of one factor of (x−1). |
| Q2.5 Explain the apparent crossing at x=5/3 | 5 | 5 | Correctly simplifies \(w(x)=(x-1)(x-2)/(3x-5)\) and identifies x=5/3 as a pole rather than an additional root. |
| Q2.6 Implement Newton's method | 4 | 3 | Uses the required modified relative-step tolerance and analytic derivative. However, the routine does not safely handle a zero derivative or non-finite iterates, and it can return an iterate without explicitly reporting failure if the iteration limit is reached. |
| Q2.7 Find all roots of `f` | 4 | 4 | The tested initial guesses identify both roots, x=1 and x=2. |
| Q2.8 Find all roots of `w` | 4 | 4 | Correctly finds both roots, x=1 and x=2, from the tested initial guesses. |
| Q2.9 Compare convergence at x=1 | 4 | 4 | Correctly explains linear convergence for the double root of f and quadratic convergence for the simple root of w. The iteration counts support the comparison. |
| **Q2 total** | **32** | **30.5** | |

## Question 4 — 75/76

| Part | Maximum | Awarded | Comments |
|---|---:|---:|---|
| Q4.1 Load data using pandas | 2 | 2 | Correctly loads the supplied CSV using pandas. |
| Q4.2 Plot data and estimate A and C | 6 | 6 | Correct data plot and reasonable estimates based on the peak height and its location. |
| Q4.3 Choose initial parameters and plot model | 6 | 6 | Compares several B values and selects a reasonable initial parameter vector. |
| Q4.4 Implement first central difference | 6 | 6 | Correct central-difference formula. |
| Q4.5 Calculate sum of squared residuals | 6 | 6 | Correctly calculates the sum of squared residuals using the supplied data arrays. |
| Q4.6 Calculate gradient G | 8 | 8 | Correct central finite-difference calculation of all three gradient components. |
| Q4.7 Calculate Jacobian of G | 8 | 8 | Correct central finite-difference construction of the 3×3 Jacobian. |
| Q4.8 Implement multidimensional Newton solver | 12 | 12 | Correctly solves the Newton update system, checks the gradient norm, prints the required iteration diagnostics, and handles singular Jacobians and non-finite parameter updates. |
| Q4.9 Run solver and report solution | 8 | 8 | The main run converges in 7 updates. The final gradient norm is \(4.18\\times10^{-6}\), below the required \(10^{-5}\) tolerance. |
| Q4.10 Plot data, initial guess and best-fit model | 8 | 8 | Includes the data, initial model and converged best-fit model. |
| Q4.11 Test other initial guesses and discuss convergence | 6 | 5 | Tests three alternative initial guesses: one converges to the same solution, while the others fail to converge (iteration limit / singular Jacobian). The discussion identifies the sensitivity to initial guesses, but could describe the individual outcomes more explicitly. |
| **Q4 total** | **76** | **75** | |

## Overall

| Question | Maximum | Awarded |
|---|---:|---:|
| Q2 | 32 | 30.5 |
| Q4 | 76 | 75 |
| **Total** | **108** | **105.5** |

**Final score: 105.5/108**
