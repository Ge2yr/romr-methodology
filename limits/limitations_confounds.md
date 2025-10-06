# Limitations and Confounds

This document summarizes typical limitations and potential confounds in experimental setups:

- **Data Distribution Drift**: Unexpected shifts in input data may invalidate assumptions.
- **Overfitting**: Models may overfit synthetic or small datasets; cross-validation is essential.
- **Confounded Variables**: Hidden correlations can produce misleading results.
- **Random Initialization**: Random seeds affect reproducibility; fix seeds and report them.
- **Environmental Noise**: Hardware variability or background processes can affect timing metrics.
