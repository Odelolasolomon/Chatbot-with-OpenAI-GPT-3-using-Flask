# Flask GPT-3 Chat Application

This Flask web application allows users to interact with OpenAI's GPT-3 engine. Users can submit queries to GPT-3, receive responses, and view their query history.

## Project Overview

- **Core Technologies**: Flask, SQLAlchemy, OpenAI API
- **Frontend**: HTML, Bootstrap
- **Backend**: Python, Flask, SQLAlchemy
- **Database**: SQLite (configured using Flask-SQLAlchemy)

## Features

- **Chat Interface**: Users can enter queries and receive responses from GPT-3.
- **Search History**: Users can view a history of their queries and responses.
- **Database Integration**: Stores all interactions with GPT-3 in a SQLite database.

## Installation

### Prerequisites

Ensure you have Python 3.6 or higher installed.

### Clone the Repository

```bash```
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
## Set Up the Environment

### Create a Virtual Environment (optional but recommended):

```bash```
python -m venv venv

## Activate the Virtual Environment:
- pip install -r requirements.txt
Set Up the Configuration
## Create a .env file in the root directory with the following content:

- OPENAI_API_KEY=your_openai_api_k
- flask run --host=0.0.0.0
## File Structure
- app.py: Core file that executes the Flask application.
- website/: Contains the main application code and templates.
- init.py: Configures the Flask application and database.
- models.py: Defines the database models.
- routes.py: Manages the routes and view functions.
- templates/: Contains HTML templates.
- base.html: Base template with navbar and layout.
- response_view.html: Displays responses from GPT-3.
- history.html: Displays the history of interactions.

## Contributing
- Feel free to open issues or submit pull requests. Contributions are welcome!

## License
- This project is licensed under the MIT License - see the LICENSE file for details.
  
## Acknowledgments
- Flask: A lightweight WSGI web application framework for Python.
- OpenAI: Provides the GPT-3 API for generating responses.
Bootstrap: Frontend framework used for styling.
