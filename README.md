
# Online Notes Sharing Platform

This project is a web-based application designed to allow users to share notes online. It is built using the Django framework and uses a SQLite database to store information.

## Features

- **User Registration/Login**: Allows users to register, log in, and manage their account.
- **Upload Notes**: Users can upload and share their notes in various formats (PDF, DOCX, etc.).
- **Search Notes**: A feature to search for specific notes or subjects.
- **Media Management**: Uploaded notes are managed in a media folder.
- **Database**: SQLite is used to store user data and metadata about the notes.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Online-Notes-Sharing.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Online-Notes-Sharing
    ```

3. Apply migrations:
    ```bash
    python manage.py migrate
    ```
4. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage

1. After starting the server, visit `http://127.0.0.1:8000/` in your browser.
2. Register a new account or log in with existing credentials.
3. Use the platform to upload notes or search for available notes.

## Project Structure

- **NotesSharingProject/**: Contains project settings, URL configurations, and WSGI/ASGI application configuration.
- **notes/**: The core app where the functionality related to note sharing is implemented.
- **media/**: Stores user-uploaded files like notes.
- **db.sqlite3**: SQLite database file to store user and note data.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes.

## License

This project is licensed under the MIT License.
