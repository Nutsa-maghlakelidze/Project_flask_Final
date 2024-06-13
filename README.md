# Project_flask_sqlite3

This is a Flask project that allows users to manage meals in a restaurant. Users can register, log in, add, edit, and delete meals from the database. You can also view the menu, get information about us, and send feedback too.

## Installation

1. Clone the repository to your local machine:
   git clone https://github.com/Nutsa-maghlakelidze/Project_final.git

2. Install Flask:
in pycharm console write: pip install Flask

3. Install database navigator:
Go to Settings > Plugins > Database Navigator in PyCharm.
Install the Database Navigator plugin.

4. Initialize the database:
Run init_db.py to set up the SQLite database.

5. Launch SQLite and connect to the database:
Right-click database.db in PyCharm, copy its absolute path.
Open a SQLite database management tool (DB Browser).
Click on + 
Choose SQLite as the database type, and select "Custom" connection type.
Paste the absolute path (e.g., jdbc:sqlite:/path/to/your/database.db) and connect.
