# Udacity-Project-Build-a-ML-Workflow-For-Scones-Unlimited-On-Amazon-SageMaker

Overview
This project aims to build a machine learning workflow for Scones Unlimited using Amazon SageMaker. It involves deploying and monitoring an image classification model using a sample CIFAR-100 dataset.

Features
Data Preprocessing: Includes data cleaning, transformation, and preparation of CIFAR-100 dataset.
Model Training: Utilizes Amazon SageMaker for training the image classification model.
Deployment: Deploys the trained model as an endpoint using AWS Lambda and Amazon API Gateway.
Monitoring: Sets up monitoring for the deployed endpoint to track model performance.
Technologies Used
Amazon SageMaker: Used for model training and deployment.
AWS Lambda: Invokes the SageMaker endpoint for inference.
Amazon API Gateway: Provides a RESTful API to access the model.
Git: Version control for project files.
Linux Terminal: Used for command-line operations and project management.
Installation
To replicate the project, follow these steps:

Clone the repository:
bash
Copy code
git clone <repository_url>
cd project_directory
Setup AWS credentials and configure the environment.
Install necessary dependencies.
Usage
Data Preparation: Prepare CIFAR-100 dataset for training.
Model Training: Train the image classification model using SageMaker.
Deployment: Deploy the trained model using AWS Lambda and API Gateway.
Monitoring: Monitor model performance and endpoint usage.
Contributing
Contributions are welcome. Please fork the repository and submit pull requests.

License
This project is licensed under the [Your License Name] License - see the LICENSE.md file for details.

Acknowledgements
Mention any acknowledgements or credits to individuals or organizations that contributed to the project.
