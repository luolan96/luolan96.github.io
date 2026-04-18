# luolan96.github.io
Useful theorems about matrices 


Lemma (Weyl comparison inequality for products). Let $A= \left(a_{i j}\right)_{1 \leq i, j \leq n} \in M_n(\mathbb{C})$ have generalized eigenvalues $\lambda_1, \ldots, \lambda_n \in \mathbb{C}$, ordered so that $\left|\lambda_1\right| \leq \ldots \leq\left|\lambda_n\right|$, and singular values $\sigma_1(A) \geq \ldots \geq \sigma_n(A) \geq 0$. Then we have

$$
\prod_{j=1}^J\left|\lambda_j\right| \leq \prod_{j=1}^J \sigma_j(A)
$$

and

$$
\prod_{j=J}^n \sigma_j(A) \leq \prod_{j=J}^n\left|\lambda_j\right|
$$

for all $0 \leq J \leq n$.

Proof. It suffices to prove the former claim, as the latter then follows from (11). By arguing as in Lemma A. 2 we may assume that $A$ is upper triangular, so that the diagonal entries are some permutation of $\lambda_1, \ldots, \lambda_n$. Consider the symmetric minor $A^{\prime}$ of $A$ formed by the rows and columns corresponding to the entries $\lambda_1, \ldots, \lambda_J$. The determinant of this matrix is then $\lambda_1 \ldots \lambda_J$, and thus by (11) we have

$$
\prod_{j=1}^J \sigma_j\left(A^{\prime}\right)=\prod_{j=1}^J\left|\lambda_j\right| .
$$


The claim then follows from the Cauchy interlacing inequality. 
