# Key Formulas in Data Analytics

## Formulas I Should Know

### Percentile Formulas [[statitical measure of how data is distributed]]

To find the k-th percentile of a dataset:

1. **Arrange the data** in ascending order.

2. **Calculate the rank (position)** of the k-th percentile using the formula:
   
   P_k = k/100 * (N + 1)
   
   where:
   - \( P_k \) is the k-th percentile.
   - \( k \) is the desired percentile (e.g., 50 for the 50th percentile).
   - \( N \) is the number of observations in the dataset.

3. **Determine the value** corresponding to the rank:
   - If the rank is an integer, the k-th percentile is the value at that position.
   - If the rank is not an integer, interpolate between the closest ranks.

### Standard Deviation

Standard deviation measures the amount of variation or dispersion in a set of values.

1. **Population Standard Deviation (\(\sigma\))**:
   \[
   \sigma = \sqrt{\frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2}
   \]
   where:
   - \( N \) is the total number of observations.
   - \( x_i \) represents each observation.
   - \( \mu \) is the mean of the observations.

2. **Sample Standard Deviation (s)**:
   \[
   s = \sqrt{\frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2}
   \]
   where:
   - \( n \) is the number of observations in the sample.
   - \( x_i \) represents each observation.
   - \( \bar{x} \) is the mean of the sample observations.
