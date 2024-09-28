### DVWA Installation and SQL Injection Testing Guide ###

This repository contains the necessary files and instructions for setting up the Damn Vulnerable Web Application (DVWA) using Docker. The included PDF report provides detailed steps for installation, usage, and executing SQL injection tests across various security levels.

## Prerequisites

Git: Ensure you have Git installed for cloning the repository.
Docker: Docker is required to run DVWA in a containerized environment.

## Installation Steps

1. Clone the Repository
Begin by cloning the repository to your local machine:

bash

git clone https://github.com/eystsen/pentestlab.git

2. Navigate to the Repository

Change your directory to the cloned repository:

bash

cd pentestlab

3. Install Docker

If Docker is not installed on your system, you can install it using the following command:

```sudo apt install docker.io```

4. Start DVWA

Use the provided script to launch the DVWA application:

```./pentestlab.sh start dvwa```

5. Access the DVWA Web Interface

Once DVWA is running, access the web interface via your browser at:

http://dvwa

Default Credentials:

 Username: admin
 Password: password
