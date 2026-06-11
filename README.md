# Movie Presentation Platform

Bilingual web platform for presenting and managing a movie catalog.

The project provides a simple public interface for browsing movies and a secured administration area for managing dynamic content.

## Overview

This project was developed for the `PROGRAMMATION_WEB2_FILM_PRESENTATION` module.

The application is built with PHP and SQLite. It supports French and English content, dynamic data loading with AJAX, and a responsive interface for desktop, tablet, and mobile devices.

## Features

* Bilingual interface: French and English
* Movie listing page
* Movie detail page
* About page
* Secured administration area
* Add, edit, and delete movies
* Dynamic data loading with AJAX
* Responsive layout
* Input validation
* SQL injection protection

## Pages

| Page          | Purpose                                                               |
| ------------- | --------------------------------------------------------------------- |
| Home          | Displays the available movies with title and short description        |
| Movie Details | Shows production year, director, language, and full movie information |
| About         | Presents the owner or author of the website                           |
| Admin         | Allows authenticated content management                               |

## Technical Stack

| Layer                   | Technology                 |
| ----------------------- | -------------------------- |
| Backend                 | PHP                        |
| Database                | SQLite                     |
| Dynamic requests        | AJAX                       |
| Frontend                | PHP, HTML, CSS, JavaScript |
| Development environment | Visual Studio Code         |

## Security

The project includes basic security measures for the administration interface:

* Form input validation
* Filtering of unauthorized characters
* Protection against SQL injection during admin operations
* Restricted access to content management features

## Demo Access

For demonstration environments, use dedicated demo credentials only.

```text
Email: demo-admin@example.com
Password: demo-password
```

Do not publish real administrator credentials in a public repository.

## Installation

Clone the project into a local web server environment such as XAMPP or WAMP.

```bash
git clone <repository-url>
```

Place the project inside the local server directory, for example:

```text
htdocs/
```

Check that the SQLite database is accessible by the application.

## Usage

Start the local server and open the application in a browser:

```text
http://localhost/projet_progWeb/index.php
```

Log in to the administration area to manage movies and dynamic content.

## Project Structure

```text
projet_progWeb/
├── index.php
├── admin/
├── assets/
├── includes/
├── database/
├── pages/
└── README.md
```

## Academic Context

Module: `PROGRAMMATION_WEB2_FILM_PRESENTATION`
Project type: Web programming project
Development environment: Visual Studio Code

## Author

Setayesh Ghamat
