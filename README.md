# Evaluating infection-generating processes for infectious disease situational awareness

This repository contains the code, data, and manuscript for our research evaluating whether the inclusion of a renewal process in the latent generative model improves estimation of the effective reproduction number (Rt) and other situational awareness signals for infectious disease surveillance.

## Project overview

We systematically evaluate how different infection-generating processes perform across multiple epidemiological outcomes, explicitly examining the decoupling between generative processes and target measures. Our approach:

1. Develops a flexible framework (EpiAware) for Rt estimation that allows different latent infection models
2. Tests models across simulated scenarios with known outcomes
3. Compares performance across different epidemiological outcomes and settings
4. Assesses impact of generation interval misspecification
5. Provides evidence-based recommendations for model selection

## Repository structure

- **EpiAware**: Julia-based modelling framework with composable components
- **Pipeline**: Scripts for model fitting, forecasting, and performance evaluation
- **Manuscript**: Quarto document detailing findings and implications

## Paper

The full manuscript is available in `main.qmd`. We address a critical gap in understanding how different modelling approaches perform across various surveillance tasks, providing evidence-based recommendations for model selection in public health surveillance.

## Analysis code

The analysis code is organized in the `Rt-without-renewal` directory, which contains:
- Model definitions and components
- Simulation infrastructure
- Evaluation metrics and visualizations

## Citation

If you use this code or methodology, please cite:

```
@article{sampling_rt_vs_rt,
  title={Evaluating infection-generating processes for infectious disease situational awareness: Is the renewal process necessary?},
  author={Brand, Samuel P. C. and Abbott, Sam},
  year={2023},
  note={Manuscript in preparation}
}
```
