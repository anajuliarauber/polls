# Polls Project

## Project Overview

The **Polls Project** is a web application that provides a platform for creating and managing polls. It is divided into two main components:

1. **Public Site:**
   - Users can view available polls.
   - Users can cast votes on polls.

2. **Admin Site:**
   - Administrators can manage polls, including adding, editing, and deleting polls.

## Technologies Used

- **Programming Language:** Python  
- **Framework:** Django  
- **Containerization:** Docker  
- **Database:** PostgreSQL  

## Setup Instructions

Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository:**
   Clone the project repository from GitHub:
   ```sh
   git clone git@github.com:anajuliarauber/polls.git
   ```

2. **Create a virtual environment:**
  Set up a Python virtual environment for dependency management:
    ```sh
    python -m venv .venv
    ```

3. **Activate the virtual environment:**

    ```sh
    source .venv/bin/activate
    ```

4. **Install the required dependencies:**
Install the necessary Python libraries from the requirements.txt file:
    ```sh
    pip install -r requirements.txt
    ```

5. **Add environment variables:**
   Set up environment variables as defined in the .env.example file. Update the .env file with your specific configuration.

6. **Start the application using Docker Compose:**
Launch the application with Docker Compose:
    ```sh
    docker compose up
    ```

## Running Tests

To run the tests, use the following command:
```sh
docker compose exec web python manage.py test polls