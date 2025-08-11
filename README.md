 ## A full depth repo containing the azure app deployment 

 This repo will house the entire deployment for an app to Azure which will utilise:

 - Azure App Service
 - Azure Container Registry
 - SonarCloud
 - Azure FrontDoor
 - Github Actions

 Task Requierements:

- Containerise the app and push it to Azure Container Registry (ACR).
- Use a CI/CD pipeline (GitHub Actions, Azure DevOps, or another) to build, test, and push the container image.
## Deploy the app on Azure using Terraform:
- Azure Container Apps
- Expose the application via HTTPS using Azure Application Gateway or Azure Front Door.
- Ensure the app is available at:
`https://tm..co.uk or`
`https://tm.labs..co.uk`
- Add screenshots of the live app to the README.md.
- Include an architecture diagram of your infrastructure (Lucidchart, draw.io, or Mermaid).

## Directory Structure
- terraform/ - Terraform configuration for Azure resources. Use modules for reusable components.
- app/ - App code and Dockerfile.
- .github/workflows/ - CI/CD pipeline configuration (GitHub Actions). Or any other CI/CD tool you want to use.
- docs/ - Documentation for the project. Diagrams/Architectures.
- README.md - Project documentation.