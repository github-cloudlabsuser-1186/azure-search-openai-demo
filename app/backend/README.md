# Backend Application

The backend application is built using [Quart](https://pgjones.gitlab.io/quart/), a Python framework for asynchronous web applications. The backend code is stored in the `app/backend` folder.

## Structure

The backend application is structured as follows:

- `app/backend/main.py`: This is the entry point of the backend application. It initializes the application and sets up the necessary routes.

- `app/backend/approaches/`: This directory contains the classes powering the Chat and Ask tabs. Each class uses a different RAG (Retrieval Augmented Generation) approach to provide unique functionalities.
This command will discover and run all test cases in the tests directory.

Linting and Formatting
The project uses Fluff for linting and Black for formatting. The configuration for these tools is located in the pyproject.toml file. To run the linter and formatter, use the following commands:

Deployment
The backend application is designed to be deployed on an Azure App Service. For more details on how to deploy your application to Azure, refer to the Azure deployment guide.
```

## Running the Backend Locally

To run the backend application locally, follow these steps:

1. Navigate to the `app` directory in your terminal.
2. Run `./start.ps1` or `./start.sh` script, or use the "VS Code Task: Start App" to start the project locally.

## Customizing the Backend

Typically, the primary backend code you'll want to customize is the `app/backend/approaches` folder. For more details on how to customize these classes, refer to the [customization guide](./customization_guide.md).

## Testing

The backend application includes a suite of unit tests to ensure the reliability and stability of the application. To run these tests, use the following command:

```bash
pytest tests/

This command will discover and run all test cases in the tests directory.

Linting and Formatting
The project uses Fluff for linting and Black for formatting. The configuration for these tools is located in the pyproject.toml file. To run the linter and formatter, use the following commands:

Deployment
The backend application is designed to be deployed on an Azure App Service. For more details on how to deploy your application to Azure, refer to the Azure deployment guide.

```

# Backend Application

The backend application is built using [Quart](https://pgjones.gitlab.io/quart/), a Python framework for asynchronous web applications. The backend code is stored in the `app/backend` folder.

## Requirements

The backend application requires the following Python packages:

- azure-core-tracing-opentelemetry==1.0.0b11
- azure-identity==1.15.0
- azure-keyvault-secrets==4.8.0
- azure-monitor-opentelemetry==1.3.0
- azure-monitor-opentelemetry-exporter==1.0.0b23
- azure-search-documents==11.6.0b1
- azure-storage-blob==12.19.1
- azure-storage-file-datalake==12.14.0
- beautifulsoup4==4.12.3
- blinker==1.7.0

For a complete list of requirements, please refer to the [requirements.txt](app/backend/requirements.txt) file.

## Structure

...