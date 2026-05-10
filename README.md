# A New f(R) Model of Gravity

## Overview
This repository contains the theoretical framework and numerical analysis for a modified theory of gravity. The project proposes an $f(R)$ extension to the Einstein-Hilbert action to explain the accelerated expansion of the universe without the need for a cosmological constant ($\Lambda$).

## The Model
The proposed model modifies the Ricci scalar $R$ as follows:

$$f(R) = R - \frac{\alpha}{\pi}R_{c} \cot^{-1}\left(\frac{R_{c}^{2}}{R^{2}}\right) - \beta R_{c}(1 - e^{-R/R_{c}})$$

### Key Features:
- **Inverse Cotangent Correction**: Handles high-curvature regimes.
- **Exponential Suppression**: Ensures stability and General Relativity recovery at $R \to 0$.

## Mathematical Results
- **Modified Field Equations**: Derived via action variation in the Jordan frame.
- **Scalaron Mass**: Analytical derivation of the scalar degree of freedom's mass ($m_{\phi}^2$), which governs the range of the "fifth force."

## Analysis
The repository includes scripts/data for:
- Variation of scalaron mass with background curvature ($R_0$).
- Effects of dimensionless parameters $\alpha$ and $\beta$ on model stability.

## Future Work
- Testing under solar system and gravitational wave constraints.
- Formalizing the model in the Einstein frame.

## References
- Starobinsky, A. A. (2007). "Disappearing cosmological constant in f(r) gravity."
- Hu, W., & Sawicki, I. (2007). "Models of f(r) cosmic acceleration that evade solar system tests."
- Sotiriou, T. P., & Faraoni, V. (2010). "f(r) theories of gravity."