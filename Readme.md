# WebVerse: Full Stack Web Application

This repository contains a comprehensive web application built using Django and Flask. The project features user authentication, RESTful APIs, responsive design, and state management with Redux.

## Technology Used

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,django,html,css,postman,flask,mysql,pycharm" />
  </a>
</p>

## Features
- **User Authentication**: Secure login and registration system.
- **Responsive Design**: Mobile-first design to ensure compatibility with all devices.
- **RESTful APIs**: Structured API for interaction between frontend and backend.
- **State Management**: Maintaining application state.

## Installation

### Prerequisites
- Python 3.12

### Clone the repository:
```bash
git clone https://github.com/yourusername/webverse.git
cd webverse
```

### Install dependencies for backend (Django and Flask):
```bash
cd backend
pip install -r requirements.txt
```

### Create a .env file in the backend directory and add your environment variables:
```bash
SECRET_KEY=your_django_secret_key
DATABASE_URL=your_database_url
JWT_SECRET=your_secret
```

## Start the development servers
### Backend:
```bash
cd backend
python manage.py runserver
```
### Frontend:
```bash
cd frontend
npm start
```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Register a new user or log in with existing credentials.
3. Explore the features of the application.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

