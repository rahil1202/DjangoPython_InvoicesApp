
# Django Python Invoices App

## Overview

This Django Python Invoices App is a 🌐 web application designed to manage and generate invoices. The application is built using the 🐍 Django framework, providing a robust and scalable solution for handling invoicing needs.

## Features

- **Invoice Management:** Create, update, and delete invoices with ease.
- **Invoice Listing:** View a list of all invoices with essential details.
- **Invoice Details:** Access detailed information for each invoice, including items, quantities, and totals.
- **Testing:** Unit tests ensure the reliability of the application.

## Video Demo

Watch a demonstration of the application features [here](https://github.com/sharpsailor/Django_Python-Invoices-App/assets/119790479/bf6d7bac-5e54-42d0-b51c-46abd7790a6e) 🎥.

## Getting Started

Follow these steps to set up and run the Django Python Invoices App on your local machine:

1. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

2. Adjust the execution policy (for Windows):

    ```bash
    Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
    ```

3. Activate the virtual environment:

    ```bash
    .\venv\Scripts\Activate
    ```

4. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5. Apply database migrations:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. Run the development server:

    ```bash
    python manage.py runserver 8000
    ```

7. Run tests:

    ```bash
    python3 manage.py test invoices.tests.InvoiceTests
    ```

## Contributing

If you would like to contribute to the development of this project, please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and submit a pull request.

## License

This Django Python Invoices App is licensed under the [MIT License](LICENSE) 📄.

## Author

[Author](github.com/rahil1202) 🧑‍💻

Feel free to contact the author if you have any questions or concerns related to the application.

Happy coding! 🚀
