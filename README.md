# Data Pipeline deployment on AKS

This document serves as a template for deploying a data pipeline on Azure Kubernetes Services.

## Project Description

This document outlines a blueprint for deploying a data pipeline, constructed with Dagster as the primary ETL orchestration tool, onto Azure Kubernetes Services. The containerized pipeline resides within the GitLab container registry. However, to ensure secure storage of credentials and other variables, the secret for image retrieval and related data can be stored in Azure Key Vault.