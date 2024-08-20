# Django Poll Voting App

A Django-based web application that allows users to vote on polls. This project includes features for creating polls, viewing questions, casting votes, and viewing results.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Overview

This project is a poll voting application built with Django. Users can view questions, select choices, and see the results of their votes. The app uses Django's powerful ORM for data management and provides a user-friendly interface for interaction.

## Features
- **Create Polls**: Admins can add new polls and questions.
- **Vote on Polls**: Users can cast their votes on available questions.
- **View Results**: Users can view the results of each poll.
- **Admin Interface**: Built-in Django admin interface for managing polls and choices.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/django-poll-voting-app.git
    cd django-poll-voting-app
    ```

2. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Apply the migrations:**

    ```bash
    python manage.py migrate
    ```

4. **Create a superuser (optional, for accessing the admin interface):**

    ```bash
    python manage.py createsuperuser
    ```

5. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

## Usage

1. **Access the Application**: Open your browser and go to `http://127.0.0.1:8000/` to view the polls.

2. **Admin Interface**: Access the admin interface at `http://127.0.0.1:8000/admin/` to manage polls and choices.

3. **Vote on Polls**: Select a poll, choose an option, and submit your vote.

## Technologies Used

- **Django**: A high-level Python web framework for building web applications.
- **Python**: The programming language used for this project.
- **SQLite**: The default database for Django, used for development purposes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
