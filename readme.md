# Code Fixer

## Description
Code Fixer is a Django web application that allows users to fix their code snippets using OpenAI's language models. Users can select a programming language, input their code, and receive corrected code output.

## Features
- Supports a wide range of programming languages, including:
  - C, C++, C#, CSS, Dart, Django, Go, HTML, Java, JavaScript, Markup, MATLAB, MongoDB, Objective-C, Perl, PHP, PowerShell, Python, R, Regex, Ruby, Rust, Sass, Scala, SQL, Swift, and YAML.
- Saves user's code and fixes in the database for future reference.
- Allows users to view their past code fixes.
- Provides user authentication and registration functionality.

## Installation

1. Clone the repository:

git clone https://github.com/mutukuk/AI-Django-Coder.git

2. Create and activate a virtual environment:

python -m venv env
source env/bin/activate


3. Install dependencies:

pip install -r requirements.txt


4. Apply migrations:

python manage.py migrate


5. Create a superuser:

python manage.py createsuperuser


6. Run the development server:

python manage.py runserver


The application should now be accessible at `http://127.0.0.1:8000/`.

## Usage

1. Register or log in to the application.
2. Select a programming language from the dropdown menu.
3. Paste your code in the provided text area.
4. Click the "Fix Code" button.
5. View the corrected code output.
6. Access past code fixes via the "Past Fixes" link.

## Dependencies

- Django
- OpenAI
- django-crispy-forms

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).