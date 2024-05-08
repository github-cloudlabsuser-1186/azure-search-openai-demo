Backend Application
The backend application is built using Quart, a Python framework for asynchronous web applications. The backend code is stored in the app/backend folder.

Structure
The backend application is structured as follows:

app/backend/main.py: This is the entry point of the backend application.
app/backend/approaches/: This directory contains the classes powering the Chat and Ask tabs. Each class uses a different RAG (Retrieval Augmented Generation) approach.
Running the Backend
To run the backend application locally, follow these steps:

Navigate to the app directory.
Run ./start.ps1 or ./start.sh or run the "VS Code Task: Start App" to start the project locally.
Customizing the Backend
Typically, the primary backend code you'll want to customize is the app/backend/approaches folder. For more details, refer to the customization guide.

Testing
The backend application includes a suite of unit tests. To run these tests, use the following command:

This command will discover and run all test cases in the tests directory.

Linting and Formatting
The project uses ruff for linting and black for formatting. The configuration for these tools is located in the pyproject.toml file. To run the linter and formatter, use the following commands:

Deployment
The backend application is designed to be deployed on an Azure App Service. For more details, refer to the Azure deployment guide.github_cloudlabsuser_1186