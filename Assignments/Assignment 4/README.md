# Comparison of Normal Distributions with Different Standard Deviations

## 1. Introduction

In probability theory and statistics, the Normal Distribution (also known as Gaussian Distribution) is one of the most fundamental continuous probability distributions. It plays a central role in statistical inference, hypothesis testing, quality control, economics, engineering, and data science.

A normal distribution is completely determined by two parameters:

- Mean (μ) — Measure of central tendency

- Standard Deviation (σ) — Measure of dispersion

In this assignment, we analyze and compare three normal distributions that share the same mean (μ = 55) but differ in standard deviation (σ = 4, 10, 15). The objective is to determine which distribution is more stable, consistent, and statistically preferable under different conditions.

## 2. Given Data

The statistical parameters provided are:

- Mean (μ) = 55

Standard Deviations:

- Case A: σ₁ = 4

- Case B: σ₂ = 10

- Case C: σ₃ = 15

All three distributions are centered at 55. Therefore, the peak of all curves occurs at x = 55. However, the variability around the mean differs significantly.

## 3. Theoretical Background

### 3.1 Definition of Normal Distribution

A normal distribution is a continuous probability distribution defined by the Probability Density Function (PDF):

$$
f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}
$$


Where:

- x = Random variable

- μ = Mean

- σ = Standard deviation

- π = 3.14159

- e = Euler’s constant

This function describes a symmetric bell-shaped curve.

### 3.2 Properties of Normal Distribution

1. The curve is symmetric about the mean.

2. Mean = Median = Mode.

3. Total area under the curve equals 1.

4. The curve is asymptotic to the x-axis.

5. Shape depends entirely on σ.

### 3.3 Mean (μ)

The mean represents the central value of the distribution.

In all three cases:

$$
\mu = 55
$$

Thus, the central tendency is identical across all distributions.

### 3.4 Standard Deviation (σ)

Standard deviation measures the average distance of observations from the mean.

$$
\sigma = \sqrt{\frac{1}{N} \sum (x - \mu)^2}
$$

It indicates how tightly or loosely the values cluster around the mean.

- Smaller σ → Less variability

- Larger σ → Greater variability

## 4. Analysis Using Empirical Rule (68–95–99.7 Rule)

The Empirical Rule states that in a normal distribution:

- 68% of values lie within ±1σ

- 95% lie within ±2σ

- 99.7% lie within ±3σ

### 4.1 Case A: σ = 4

### ±1σ Range

$$
55 \pm 4 = 51 \text{ to } 59
$$

### ±2σ Range

$$
55 \pm 8 = 47 \text{ to } 63
$$

### ±3σ Range

$$
55 \pm 12 = 43 \text{ to } 67
$$

#### Interpretation

- Very narrow interval.

- Data points are highly concentrated.

- Minimal deviation from mean.

- Highly predictable system.

This distribution represents maximum stability.

### 4.2 Case B: σ = 10

### ±1σ Range

$$
55 \pm 10 = 45 \text{ to } 65
$$

### ±2σ Range

$$
55 \pm 20 = 35 \text{ to } 75
$$

### ±3σ Range

$$
55 \pm 30 = 25 \text{ to } 85
$$


#### Interpretation

- Moderate spread.

- Balanced variability.

- Suitable for real-world situations where moderate variation exists.

### 4.3 Case C: σ = 15

### ±1σ Range

$$
55 \pm 15 = 40 \text{ to } 70
$$

### ±2σ Range

$$
55 \pm 30 = 25 \text{ to } 85
$$

### ±3σ Range

$$
55 \pm 45 = 10 \text{ to } 100
$$

#### Interpretation

- Very wide range.

- High dispersion.

- Less predictability.

- Higher uncertainty.

## 5. Graphical Interpretation

When plotted on a graph:

- σ = 4 produces a tall, narrow bell curve.

- σ = 10 produces a moderately wide curve.

- σ = 15 produces a flatter and broader curve.

As standard deviation increases:

- Peak height decreases.

- Spread increases.

- Probability density becomes more dispersed.

Although the mean remains constant, the shape of the curve changes significantly.

## 6. Statistical Comparison

| Case | Mean (μ) | Standard Deviation (σ) | Dispersion | Predictability | Stability |
|------|----------|------------------------|------------|----------------|------------|
| A    | 55       | 4                      | Very Low   | Very High      | Very High  |
| B    | 55       | 10                     | Moderate   | Moderate       | Moderate   |
| C    | 55       | 15                     | High       | Low            | Low        |

## 7. Variance Comparison

Variance is the square of standard deviation.

- Case A: σ² = 16

- Case B: σ² = 100

- Case C: σ² = 225

Higher variance indicates greater spread and instability.

## 8. Graphical Representation

#### Figure 1: Comparison of Normal Distributions with μ = 55 and different σ values (4, 10, 15).

<img width="576" height="455" alt="image" src="https://github.com/user-attachments/assets/68b99368-6343-475e-a812-b291c8ffe264" />

#### Interpretation of the Graph:

- The curve with σ = 4 is tall and narrow → highest stability.

- The curve with σ = 10 is moderately spread.

- The curve with σ = 15 is flat and wide → highest variability.

- As σ increases, spread increases and peak height decreases.

## 9. Practical Interpretation

If this distribution represents:

#### Example 1: Machine Output

Lower σ is preferred because consistency is important.

#### Example 2: Student Marks

Lower σ means students perform uniformly.

#### Example 3: Investment Returns

Higher σ means higher risk and uncertainty.

Thus, preference depends on context.

#### Which Distribution is Better?

If the objective is:

- High consistency

- Low risk

- Greater reliability

- Stable performance

Then:

#### σ = 4 is the best distribution​

Because it has the smallest variability.

However, in real-world data, moderate variation (σ = 10) may be more realistic.

## 10. Conclusion

This study compares three normal distributions with identical mean (μ = 55) but different standard deviations.

Key Findings:

- Standard deviation controls spread, not center.

- Smaller σ produces tighter clustering.

- Larger σ produces greater dispersion.

- Predictability decreases as σ increases.

Among the three distributions, σ = 4 represents the most stable and reliable distribution due to minimal variability.

Therefore, when stability and consistency are required, a smaller standard deviation is statistically preferable.
