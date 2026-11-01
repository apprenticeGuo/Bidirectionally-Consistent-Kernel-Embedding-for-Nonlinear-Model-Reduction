# Bidirectionally-Consistent-Kernel-Embedding-for-Nonlinear-Model-Reduction

This work proposes a \emph{Bidirectionally Consistent Kernel Embedding} (BCKE) method to improve the accuracy of the nonlinear approximation in Parametric
Probabilistic Manifold Decomposition (PPMD) for parametric reduced order modeling. PPMD represents the part of the state not captured by its linear approximation using coordinates in the nonlinear low-dimensional space. These coordinates
are determined before the map that reconstructs this part is fitted. Consequently,
reconstruction errors and the geometry of the reconstructed states do not
directly guide their selection. BCKE retains the linear and nonlinear decomposition but optimizes these coordinates using reconstruction
accuracy and geometric consistency in both the reduction and reconstruction stages.
The resulting representation is used to predict states at new parameter
values, including extrapolation beyond the sampled interval. In addition, geometric consistency estimates and conditional bounds on state prediction errors are derived. Numerical experiments on flow past a cylinder and backward facing step flow compare BCKE with PPMD and proper orthogonal decomposition combined with radial basis function approximation (POD+RBF). The results show that BCKE achieves lower prediction errors than PPMD. BCKE thus provides a more accurate parametric reduced order model by determining nonlinear coordinates through a unified objective for reconstruction accuracy and bidirectional geometric consistency.
