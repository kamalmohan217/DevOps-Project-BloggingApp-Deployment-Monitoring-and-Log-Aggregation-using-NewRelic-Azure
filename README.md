# DevOps-Project-BloggingApp-Deployment-Monitoring-and-Log-Aggregation-using-NewRelic-Azure
![image](https://github.com/user-attachments/assets/c25ead7e-bc60-422b-bd69-a269324ec0a9)

This DevOps Project aims to create the infrastructure using Terraform and established the CICD set-up using Azure DevOps. For monitoring and Log Aggregation NewRelic had been used which was also shown in the screenshot attached above. The source code was present in the Azure Repos, which was deployed through the Azure DevOps Pipeline. SonarQube had been used for Code Analysis and Maven was used as the Build Tool, artifacts for this project were kept in the Azure Artifacts Feed. Trivy was used as the File Scan and Docker Image Scan which was also shown in the Architecture diagram shown above. The created Docker Image was kept in Azure Container Registries (ACR) which was deployed to Azure Kubernetes Services (AKS Cluster) using the Helm as shown in the Architecture diagram shown above.      

```
Source Code:- https://github.com/kamalmohan217/Blogging-App.git

Helm Chart:-  https://github.com/kamalmohan217/helm-repo-for-ArgoCD.git
```
