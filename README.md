# fe_lab_clinicas_api

This project is an API for a healthcare clinic management system.

## Prerequisites

Before starting, make sure you have the following installed on your machine:

- Node.js
- npm (Node Package Manager)

## Project Setup

Follow the steps below to configure and start the project:

### 1. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/stephaneantonieto/fe_lab_clinicas_api.git
```

### 2. Navigate to the Project Directory

Enter the project directory:

```bash
cd fe_lab_clinicas_api
```

### 3. Install Dependencies

Install the project dependencies using:

```bash
dart pub global activate json_rest_server
```

### 4. Configure Variables

Open the `config.yaml` file and edit your settings.


### 5. Start the Development Server

In the project’s root directory, start the development server with the following command:

```bash
jrs run
```

The server should be running at `http://localhost:8080` (or another specified port).

## Using the JSON REST Server Plugin

The JSON REST Server plugin is used to simulate RESTful endpoints and test the API without requiring a full backend. It allows defining routes, HTTP methods, and responses directly within your project.

For more information, check the [plugin documentation](https://pub.dev/packages/json_rest_server).