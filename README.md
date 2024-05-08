# FastAPI Project

This is a basic FastAPI application that incorporates user authentication features, allowing for user sign-up and secure authentication.

## Installation

To get started with this project, clone the repository and install the required dependencies.

### Cloning the Repository

```bash
git clone ...
cd your-repository
```

### Installing Dependencies
Ensure you have Python installed on your machine, then use pip to install the required packages:

```
pip install -r requirements.txt
```

### Running the Application
Run the application using Uvicorn, an ASGI server, with live auto-reload enabled. This is particularly useful for development as it allows the server to automatically restart upon code changes.

python3 -m uvicorn main:app --reload


## Features
- User Authentication: Securely manage user authentication.
- User Signup: New users can sign up.
- Secure Password Hashing: Uses bcrypt to securely hash passwords.


