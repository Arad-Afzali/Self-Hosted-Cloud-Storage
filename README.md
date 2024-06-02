# Self-Hosted Cloud Storage Management System

This is a self-hosted cloud storage management system built using Django. The system allows users to upload, manage, and share files securely within their own infrastructure.

## Features

- User authentication
- File upload, download, and management
- Responsive design for desktop and mobile devices

## Installation

Follow these steps to set up the project on your local machine.

### Prerequisites

- Python 3.12 or higher
- Django 4.x
- Virtual environment (optional but recommended)

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Arad-Afzali/.git
    cd AES-File-Encryptor-Decryptor
    ```

2. **Create and activate a virtual environment** (recommended):
    
    **On macOS/Linux:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

    **On Windows:**
    ```cmd
    python3 -m venv venv
    venv\Scripts\activate
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Set Up the Database

Run the following commands to apply migrations and set up the database.

```bash
python manage.py makemigrations
python manage.py migrate
```

### Run the Server

Start the development server.

```bash
python manage.py runserver
```

Open your browser and navigate to `http://127.0.0.1:8000` to see the application in action.

## Usage

### File Management

- Log in with your account.
- Upload files using the file upload interface.
- Manage your files through the dashboard, including downloading, deleting, and sharing files.


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Open a pull request and describe the changes you have made.
