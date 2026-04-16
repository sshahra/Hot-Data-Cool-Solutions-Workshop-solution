# Hot-Data-Cool-Solutions-Workshop-solution

This repository contains the workshop notebook, trained XGBoost outputs, and post-modeling visualizations for the CHF prediction exercise.

## Repository Contents

```text
Hot-Data-Cool-Solutions-Workshop-solution/
├── Heat-workshop.ipynb
├── README.md
└── Solutions/
	├── best_xgboost_params.json
	├── learning_rate_sensitivity_xgb.jpg
	├── max_depth_sensitivity_xgb.jpg
	├── shap_beeswarm.jpg
	├── shap_global_importance_bar.jpg
	├── xgboost_feature_importance.jpg
	├── xgboost_metrics_summary.csv
	├── xgboost_predicted_vs_actual.jpg
	├── xgboost_residual_plot.jpg
	└── xgboost_test_predictions.csv
```

## File Reference

### Root

- `Heat-workshop.ipynb`: Main workshop notebook containing preprocessing, model training, and analysis workflow.
- `README.md`: Project overview and quick reference.

### Solutions

- `best_xgboost_params.json`: Best hyperparameters selected for the XGBoost model.
- `xgboost_metrics_summary.csv`: Summary performance metrics (RMSE, MAE, and R^2).
- `xgboost_test_predictions.csv`: Test-set predictions with actual values and residuals.

#### Sensitivity Plots

- `learning_rate_sensitivity_xgb.jpg`: Performance trend as learning rate changes.
- `max_depth_sensitivity_xgb.jpg`: Performance trend as tree max depth changes.

#### Model Interpretation

- `xgboost_feature_importance.jpg`: XGBoost-native feature importance chart.
- `shap_global_importance_bar.jpg`: SHAP global feature importance (bar chart).
- `shap_beeswarm.jpg`: SHAP beeswarm plot showing feature impact distribution.

#### Prediction Diagnostics

- `xgboost_predicted_vs_actual.jpg`: Predicted vs actual target values.
- `xgboost_residual_plot.jpg`: Residual distribution and error behavior.

## Quick Data Snapshot

- Best parameters include `n_estimators=1000`, `max_depth=7`, and `learning_rate=0.1`.
- Reported metrics are approximately `RMSE=207.20`, `MAE=139.08`, and `R^2=0.9253`.

## Notes

- All generated outputs are stored in the `Solutions/` directory.
- The notebook is the source of truth for reproducing these results.
