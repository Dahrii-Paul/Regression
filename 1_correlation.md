##  Correlation
* Defines the relationship between two variables that is how the two variables are linked with each other
* **Correlation test** is used to evaluate the association between two or more variables.

## Methods for corelation analysis
* **Pearson correlation** (r), which measures a linear dependence between two variables (x and y). It’s also known as a parametric correlation test because it depends to the distribution of the data. It can be used only when x and y are from normal distribution. The plot of y = f(x) is named the linear regression curve.
* Kendall tau and Spearman rho, which are rank-based correlation coefficients (non-parametric)

## Formula
**Pearson:**
$$r = \frac{\sum\limits_{i=1}^{n}(x_i - \overline{x})(y_i - \overline{y})}{\sqrt{\sum\limits_{i=1}^{n}(x_i - \overline{x})^2 \sum\limits_{i=1}^{n}(y_i - \overline{y})^2}}$$
 
* $r$ is the correlation coefficient
* $n$ is the number of data points
* $x_i$ and $y_i$ are the individual data values
* $\bar{x}$ and $\bar{y}$ are the sample means of $X$ and $Y$, respectively

**Spearmen:**
$$rho = \frac{\sum\limits_{i=1}^{n} (x' - {x_i'}) (y' - {y_i'})}{\sqrt{\sum\limits_{i=1}^{n} (x' - {x_i'})^2 \sum\limits_{i=1}^{n} (y' - {y_i'})^2}}$$
Where  𝑥′=𝑟𝑎𝑛𝑘(𝑥) and  𝑦′=𝑟𝑎𝑛𝑘(𝑦)

## Correlation R
[Correlation Kaggle](https://www.kaggle.com/code/patthoo/correlation-test-between-two-variables-in-r)














