# ML-Assignment-1-Code-

Why Use Min-Max Scaling?
Min-max scaling is used to normalize data into a standard range [0, 1] for several reasons:

1. Consistent Scale: It ensures that all features contribute equally to the distance calculations or gradients in algorithms that are sensitive to feature scales, such as k-nearest neighbors or gradient-based algorithms.

2. Improves Convergence: For optimization algorithms, such as gradient descent, having features on a similar scale can help in faster and more stable convergence.

3. Enhanced Performance: Some machine learning models assume features are normally distributed or on a similar scale. Normalizing features can help improve model performance and interpretation.

4. Compatibility: Many machine learning algorithms (like support vector machines or neural networks) assume input features are within a certain range. Normalization ensures that these assumptions are met.
