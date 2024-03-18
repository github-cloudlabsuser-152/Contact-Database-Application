# Contact Database Application

This repository contains the source code and configuration files for the Contact Database Application.

## ARM Template (deploy.json)

The `deploy.json` file is an Azure Resource Manager (ARM) template used to define and deploy the infrastructure resources required for the Contact Database Application. It includes the definition of Azure resources such as virtual machines, storage accounts, and networking components. To deploy the application, follow the instructions below:

1. Clone this repository to your local machine.
2. Open the Azure Portal and sign in to your Azure account.
3. Navigate to the Azure Resource Manager (ARM) template deployment page.
4. Select the `deploy.json` file from the cloned repository.
5. Follow the on-screen instructions to customize the deployment parameters.
6. Click on the "Deploy" button to start the deployment process.
7. Monitor the deployment progress in the Azure Portal.

## GitHub Actions Workflow

The GitHub Actions workflow file in this repository is used to automate various tasks such as building, testing, and deploying the Contact Database Application. It is defined in the `.github/workflows` directory and is triggered by events such as pushes to the repository or pull requests. The workflow includes a series of steps that are executed in a specific order. To view and modify the workflow, follow the steps below:

1. Navigate to the `.github/workflows` directory in this repository.
2. Open the workflow file (e.g., `main.yml`) in a text editor or the GitHub web interface.
3. Review the workflow steps and customize them according to your requirements.
4. Commit and push the changes to trigger the updated workflow.

For more information on GitHub Actions and how to configure workflows, refer to the [GitHub Actions documentation](https://docs.github.com/en/actions).
