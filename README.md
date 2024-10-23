# Smart Home Energy Consumption Optimization

## Overview
This project focuses on optimizing household energy consumption through predictive analytics and intelligent device management. By analyzing energy consumption patterns of household appliances and leveraging machine learning techniques, we achieved potential energy bill savings of up to **17%**.

## Dataset Features
The analysis uses a comprehensive dataset including:
- Energy consumption metrics for various appliances
- Weather data (temperature, humidity, visibility, etc.)
- Time-series data with 1-minute intervals
- Solar power generation data

## Data Analysis
The dataset includes detailed energy consumption data from various household appliances along with comprehensive weather information. Our analysis pipeline includes:
- Correlation analysis between different variables
- Anomaly detection using **SMA** (Simple Moving Average) and **EMA** (Exponential Moving Average)
- Predictive modeling using multiple algorithms:
  - **LSTM** (Long Short-Term Memory)
  - **SVM** (Support Vector Machine)
  - **Random Forest Regressor**

## Crisis Management Framework
We developed a crisis management framework focusing on peak energy consumption periods. The framework categorizes household appliances into three classes based on flexibility in operation timing and performance adjustments:

1. **Flexible Appliances**
   - Can be rescheduled without significant impact on user convenience
   - Operating times can be shifted to off-peak hours
   - Example: Lawn mower

2. **Semi-Flexible Appliances**
   - Operating time cannot be changed, but performance can be adjusted
   - Can switch to eco-mode during peak consumption periods
   - Example: Washing machine (can run in economy mode)

3. **Inflexible Appliances**
   - No flexibility in either timing or performance
   - Critical for immediate use or continuous operation
   - Examples: Iron, refrigerator

## Implementation Approaches
The system can be implemented as either:
- An automated control system
- A recommendation system

## Results
Our hour-by-hour analysis demonstrates potential energy bill reductions of **17%** through intelligent scheduling and management of appliance usage.

## Models Comparison
We compared multiple machine learning models to achieve the most accurate predictions:
- **LSTM** for sequence prediction
- **SVM** for pattern recognition
- **Random Forest Regressor** for consumption forecasting

## Note
The appliance classification system was developed assuming prior consultation with homeowners to ensure practical applicability and user acceptance.

## Future Work
- Real-time implementation of the optimization system
- Integration with smart home platforms
- Enhanced user interface for monitoring and control
- Expansion of the appliance classification system
