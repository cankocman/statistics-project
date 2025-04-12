# EC233 Homework 1 – Statistical & Economic Simulations in R

> **Course:** EC233 - Mathematical Statistics I  
> **Department:** Economics, Boğaziçi University  
> **Date:** November 1, 2024  
> **Instructor:** Ozan Hatipoğlu
> **Student:** Can Koçman

---

## 📘 About

This repository contains a statistical analysis and simulation project assigned as Homework 1 in the EC233 - Mathematical Statistics I course. The project explores a wide range of statistical, macroeconomic, and probabilistic topics using R Markdown. It demonstrates both theoretical understanding and coding practice through interactive plots, simulations, and comparative economic analysis.

---

## 📂 Contents

- `analysis.Rmd`: The full source file written in R Markdown
- `knitted_result.html`: The compiled and interactive report (knitted from `.Rmd`)
- `README.md`: This file

---

## 🧪 Topics Covered

### 🔹 Statistical Simulation

- Synthetic data generation
- Histogram comparison
- Descriptive statistics

### 🔹 Macroeconomic Analysis

- GDP per capita growth comparison across countries
- Turkey’s macroeconomic performance ranking among peer countries
- Use of Penn World Table v10.0 dataset

### 🔹 Stock Market Analysis

- Time series data from Yahoo Finance
- Weekly returns and volatility (rolling standard deviation)
- Risk comparison using Coefficient of Variation (CV)

### 🔹 Probability Simulations

- Birthday paradox for 2 to 5 people sharing a birthday
- Coin toss simulations with fair and unfair coins
- Election simulation and winner convergence under different vote distributions

---

## 🧰 How to Use

To reproduce the results:

1. **Clone the repo:**

   ```bash
   git clone https://github.com/yourusername/ec233-homework1.git
   cd ec233-homework1
   ```

2. **Open `analysis.Rmd` in RStudio** or render it via R:

   ```r
   rmarkdown::render("analysis.Rmd")
   ```

3. **Install required packages:**

   The script automatically installs these if not present:

   ```r
   devtools
   quantmod
   ggplot2
   dplyr
   zoo
   pwt10 (via GitHub)
   ```

---

## 📊 Sample Visuals

Here are some of the outputs you’ll see in the HTML report:

- GDP growth comparisons (Turkey vs Poland, Germany vs France)
- Histograms of normally distributed data
- Volatility vs return plots for MSFT and AAPL
- Birthday paradox probability graphs
- Probabilistic election simulations

---

## 📎 Note

- **Dataset sources:** All data is retrieved dynamically via R packages (no external files).
- **No sensitive or large datasets are versioned.** All outputs are reproducible with internet access.

---

## 🔗 GitHub Pages (Optional)

If you'd like to view the HTML output online, visit:

📎 [Live Report](https://cankocman.github.io/statistics-project/)

---

## 📬 License

This project is shared for educational and academic purposes only. All rights reserved to the student unless otherwise stated.
