# Moksha Kumar

## Question 1 — GitHub and submission (3 marks)

| Section | Marks | Comment |
|---|---:|---|
| Q1 | 2/3 | |

## Question 2 — Binary and IEEE floating-point representation (24 marks)

| Section | Marks | Comment |
|---|---:|---|
| Q2.1 — Decimal integer to binary | 3.5/5 | The conversion logic works for the hard-coded positive integer, but the solution does not define a reusable function that accepts a user-given integer as required. |
| Q2.2 — Decimal to IEEE double representation | 6.5/10 | The function handles several special cases, including signed zero, infinities, NaN and subnormal numbers. However, normal mantissa bits are truncated instead of rounded to the nearest representable value, and overflow is not handled robustly. |
| Q2.3 — IEEE representation to decimal | 5/5 | |
| Q2.4 — Verification using 200.0, π, +∞ and −∞ | 4/4 | |
| **Q2 Total** | **19/24** | |

## Question 3 — Floating-point error accumulation (16 marks)

| Section | Marks | Comment |
|---|---:|---|
| Q3.1(a) — Grid generation using method1 | 2/2 | |
| Q3.1(b) — Grid generation using method2 | 1.5/2 | The recurrence method is implemented correctly, but the function does not explicitly ensure that the final grid point is exactly equal to b, as required. |
| Q3.2(a) — Analytical average | 1/2 | The reported value is correct, but the calculation numerically sums all grid points instead of using the analytical expression for the average. |
| Q3.2(b) — Average using method1 | 2/2 | |
| Q3.2(c) — Average using method2 | 2/2 | |
| Q3.3 — Error calculation and plotting | 1/4 | The errors are calculated, but the plot only shows the method 2 error and does not correctly present both error curves. The claim that the method 2 errors are identically zero contradicts the computed values. The required \(n=10^8\) case is also missing. |
| Q3.4 — Comparison of accuracy | 0/2 | No explanation comparing the accuracy of the two methods is provided. |
| **Q3 Total** | **9.5/16** | |

## Final

- **Q1:** 2/3
- **Q2:** 19/24
- **Q3:** 9.5/16
- **Overall:** **30.5/43**
