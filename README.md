# CorporationX

This repository contains the entire project and uses git submodule to include all other services

# How to Start the Database and Other Tools Locally?

Follow the instructions in the README under the infra section. This is a separate repository that contains all infrastructure components, including the database, Redis, Docker Compose, and more.

# How to Develop?

Each folder in this repository is a separate subrepository, which also exists on GitHub. For example, user_service is an independent Git repository that is included in the main CorporationX repository as a submodule.

The CorporationX repository exists primarily for convenience: you can clone all necessary services with a single command (git clone as mentioned above).

Each subrepository represents an independent service (a Java application) within the CorporationX ecosystem. For instance:

user_service handles user-related logic.
project_service manages project-related logic.
Depending on the specific task, development will take place in the corresponding service. Essentially, you will write code in that service as you would in a regular project using IntelliJ IDEA.

Development Workflow
Clone the entire CorporationX project using the command above.
Identify the relevant service based on the Jira task.
Open the folder for that service in IntelliJ IDEA.
Start coding!
