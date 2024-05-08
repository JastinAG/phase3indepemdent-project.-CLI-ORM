
---
#PHASE 3 Independent project. CLI and ORM Application in Python

This is a Python CLI application built using SQLAlchemy ORM. It allows users to interact with a SQLite database through a command-line interface (CLI).

## Features

- **ORM Models:** The application defines two ORM models, `Parent` and `Child`, representing a one-to-many relationship between parents and their children.

- **CLI Commands:** Users can perform various operations on the database using CLI commands, including creating parent records, listing all parent records, and more.

- **Error Handling:** The application provides informative error messages for invalid user inputs and database operations.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/python-orm-cli.git
    ```

2. Navigate to the project directory:

    ```bash
    cd python-orm-cli
    ```

3. Install dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the CLI application using the following command:

    ```bash
    python cli.py
    ```

2. Follow the prompts to interact with the application.

3. Use the available commands to create parent records, list parents, and perform other database operations.

## Commands

- **create-parent:** Create a new parent record.
- **list-parents:** List all parent records in the database.

## Project Structure

- **cli.py:** Contains the CLI commands and entry point of the application.
- **database.py:** Defines the ORM models and database-related functions.
- **models.py:** Contains the ORM model definitions.
- **requirements.txt:** Lists the project dependencies.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
