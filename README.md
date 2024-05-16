# Online Voting Application

## Requirements

- Python 3.11 or higher
- Django
- Any other dependencies listed in `requirements.txt`

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Installation

1. **Clone the repository's master folder:**

    ```sh
    git clone https://github.com/Yrk-Yashraj/Online_Voting-Django/master.git
    ```

2. **Create and activate a virtual environment (optional but recommended):**

    ```sh
    python -m venv venv
    source venv/bin/activate
    # On Windows use `venv\Scripts\activate`
    ```

3. **Install the requirements:**

    ```sh
    pip install -r requirements.txt
    ```

### Database Setup

4. **Make database migrations:**

    ```sh
    python manage.py makemigrations
    ```

5. **Apply the migrations:**

    ```sh
    python manage.py migrate
    ```

### Running the Application

6. **Run the development server:**

    ```sh
    python manage.py runserver
    ```

### Creating a Superuser

7. **Create a superuser for admin access:**

    ```sh
    python manage.py createsuperuser
    ```

    Follow the prompts to set up your admin account.

## Usage

- Access the application at `http://127.0.0.1:8000/`.
- Access the admin panel at `http://127.0.0.1:8000/admin/` with the superuser credentials.

