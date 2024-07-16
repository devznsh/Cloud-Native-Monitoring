# Cloud-Native-Monitoring

For this project, I used Flask to build a Python monitoring application that I hosted on Kubernetes. To put it briefly, I began designing the application, using Docker to containerise it, created the image, and then launched the container locally. Next, I used the Python Boto3 package to establish an Elastic Container Registry (ECR). I pushed the Docker image into ECR. The deployment phase was the next step, during which I set up an Elastic Kubernetes Cluster (EKS) using nodes and installed the application on K8s.

