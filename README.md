# MLOps Bootcamp

Learning repository following the [Complete MLOps Bootcamp](https://cisco.udemy.com/course/complete-mlops-bootcamp-with-10-end-to-end-ml-projects/) by Krish Naik.

## Course Overview

End-to-End MLOps Bootcamp covering building, deploying, and automating ML pipelines with real-world data science projects.

## Topics Covered

- **Version Control**: Git & GitHub for ML projects
- **Containerization**: Docker for scalable ML deployment
- **Experiment Tracking**: MLflow for tracking experiments and model management
- **Data Versioning**: DVC for dataset and model versioning
- **Collaborative MLOps**: DagsHub integration
- **Workflow Orchestration**: Apache Airflow with Astronomer
- **CI/CD**: GitHub Actions for automated testing and deployment
- **ETL Pipelines**: Building data pipelines with Airflow
- **Cloud Deployment**: AWS SageMaker for model deployment
- **NLP Projects**: Huggingface transformers deployment
- **Generative AI**: AWS cloud infrastructure for Gen AI
- **Monitoring**: Grafana & PostgreSQL for real-time insights

## Setup

```bash
# Create virtual environment
python3.12 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Start MLflow server
mlflow server --host 127.0.0.1 --port 5001
```

## Project Structure

```
├── intro/              # Getting started notebooks
├── requirements.txt    # Python dependencies
└── README.md
```

## Resources

- [Course Link](https://cisco.udemy.com/course/complete-mlops-bootcamp-with-10-end-to-end-ml-projects/)
- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [DVC Documentation](https://dvc.org/doc)
