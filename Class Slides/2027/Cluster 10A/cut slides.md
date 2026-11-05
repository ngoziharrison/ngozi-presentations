---
# What Does PCA Optimize?
	Let $X_c$ be a matrix of centered measurements: people in rows, measured variables in columns.

	PCA finds a direction $v$ that maximizes the variance of the projected data:
$$
\max_{\|v\|=1} \operatorname{Var}(X_c v)
$$

	Equivalently, if $S$ is the covariance matrix, PCA finds eigenvectors $v_k$ and eigenvalues $\lambda_k$:
$$
S v_k = \lambda_k v_k
$$

	The eigenvector gives the weights for a component. The eigenvalue tells us how much variation lies along it.

	This is an exact mathematical answer to a limited question: *Which directions have the most variation in these measurements?*

---
# From Measurements to “Types”
	A component score combines selected measurements into a single number:
$$z_{ik} = (x_i - \bar{x})^T v_k$$

	The score can then be treated as if it measures a real, underlying quality of person $i$.
	That interpretation is a further choice. PCA identifies a pattern in recorded variables; it does not establish that the pattern is a natural human type, an inherited trait, or a measure of worth.
