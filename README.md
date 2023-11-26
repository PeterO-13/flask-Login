Features
User Authentication: Users can create accounts and log in securely.
Create Notes: Authenticated users can create new notes with a title and content.
View and Delete Notes: Users can view their notes and delete them as needed.
Data Storage: Uses SQLite as the backend database to store user information and notes.

Technologies Used
Flask: Web framework for building the application.
SQLAlchemy: ORM for interfacing with the database.
Flask-Login: User session management and authentication.
SQLite: Lightweight SQL database for data storage.

Getting Started
Prerequisites
Python: Ensure Python 3.x is installed on your system.
Dependencies: Install required packages listed in requirements.txt.

Installation

Clone the repository:
git clone https://github.com/your-username/flask-note-app.git
cd flask-note-app

Create a virtual environment:
python3 -m venv venv
source venv/bin/activate  # For Windows, use venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt
Usage

Run the application:
python run.py
Access the app in your browser at http://localhost:5000/.

Sign up, log in, and start managing your notes!

Contributing
Contributions are welcome! Feel free to open issues or pull requests for any enhancements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.
