# Synthetic Multivariate Time-Series Data Generation and Anomaly Detection

## Task Overview
- Generate 1 GB of synthetic multivariate time-series data.
- Simulate system metrics:
  - **CPU Temperature**
  - **CPU Usage**
  - **CPU Load**
  - **Memory Usage**
  - **CPU Power**

## Data Characteristics
- Metrics exhibit realistic behavior with slight randomness to mimic normal operations.
- Inject random anomalies, such as:
  - Spikes (e.g., sudden high temperature or usage).
  - Dips (e.g., unexpected drops in performance).

## Anomaly Detection
- Apply **Isolation Forest** as the anomaly detection algorithm.
- Identify irregular patterns that deviate from normal behavior.

## Visualization
- Create zoomed-in plots for each metric:
  - Plot normal data in blue.
  - Highlight detected anomalies in red.
- Provide a clear and intuitive representation of anomalies across all metrics.

## Purpose
- Evaluate anomaly detection performance on large, realistic datasets.
- Analyze and interpret anomalies for potential system failure diagnosis.
