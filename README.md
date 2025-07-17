# NileMart Supply Chain Optimization
A serverless AI platform for e-commerce supply chain management, using AWS Kinesis, Lambda, S3, SageMaker, Redshift, and QuickSight to predict demand, optimize routes, and detect anomalies.

## Features
- Real-time sales and logistics data processing.
- ML-driven demand forecasting and anomaly detection.
- Scalable cloud architecture with MLOps.
- Interactive QuickSight dashboard.

## Architecture
![Architecture Diagram](docs/architecture-diagram.png)

## Tech Stack
- **AWS Kinesis**: Data streaming
- **AWS Lambda**: Serverless processing
- **S3**: Data storage
- **SageMaker**: ML models
- **Redshift**: Analytics
- **QuickSight**: Visualization
- **MLflow**: Model management
- **Docker**: Containerization

## Setup
1. Deploy: `sam deploy --guided`.
2. Simulate data: Run `scripts/simulate_sales_data.py`.
3. Train models in SageMaker.
4. Visualize in QuickSight.

## Demo
[Watch Video](link-to-loom-video)
