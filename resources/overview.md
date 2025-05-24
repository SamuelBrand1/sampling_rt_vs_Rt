# Sampling Rt vs Rt: Project Overview

## Aim
To evaluate whether the inclusion of a renewal process in the latent generative model improves estimation of the effective reproduction number (Rt) and other situational awareness signals for infectious disease surveillance.

## Approach
1. Develop a flexible framework (EpiAware) for Rt estimation that allows different latent infection models
2. Test models across simulated scenarios with known outcomes
3. Compare performance across different epidemiological outcomes and settings
4. Assess impact of generation interval misspecification
5. Provide evidence-based recommendations for model selection

## Components
- **EpiAware**: Julia-based modelling framework with composable components
- **Pipeline**: Scripts for model fitting, forecasting, and performance evaluation
- **Manuscript**: LaTeX document detailing findings and implications

## Status

### Completed
- Initial framework architecture
- Model component development
- Submodule integration with Rt-without-renewal
- Basic simulation scenarios

### In Progress
- Comprehensive model validation
- Prior predictive checks
- Full simulation study execution
- Performance evaluation metrics

### To Do
- Complete result analysis
- Finalize manuscript sections
- Generate publication-ready figures
- Prepare repository for public release
