# Quotes Web App

This is a simple web application built using **React.js** for the frontend and **Django REST Framework** for the backend. The app allows users to create and submit quotes, which will be displayed on the same page after submission.

## Features
- Users can add new quotes using a form.
- Submitted quotes are displayed in real-time.
- Quotes are stored and managed via the Django backend with API endpoints.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Django REST Framework
- **Database**: SQLite (default, can be replaced with any preferred database)

## Getting Started

### Prerequisites
Make sure you have the following installed on your machine:
- Node.js
- Python 3.x
- Django
- Django REST Framework

  ---
  # Video

https://github.com/user-attachments/assets/a936f9eb-ddb5-442a-9b67-c80860cc9e77


  
### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quotes-webapp.git
   cd quotes-webapp

Here's a sample `README.md` file for your web app project:

markdown

Copy code

`# Quotes Web App

This is a simple web application built using **React.js** for the frontend and **Django REST Framework** for the backend. The app allows users to create and submit quotes, which will be displayed on the same page after submission.

## Features
- Users can add new quotes using a form.
- Submitted quotes are displayed in real-time.
- Quotes are stored and managed via the Django backend with API endpoints.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Django REST Framework
- **Database**: SQLite (default, can be replaced with any preferred database)

## Getting Started

### Prerequisites
Make sure you have the following installed on your machine:
- Node.js
- Python 3.x
- Django
- Django REST Framework

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quotes-webapp.git
   cd quotes-webapp `

1.  **Backend Setup** (Django REST Framework):

    -   Navigate to the `backend/` directory:

        bash

        Copy code

        `cd backend`

    -   Create a virtual environment and activate it:

        bash

        Copy code

        `python -m venv env
        source env/bin/activate  # On Windows: env\Scripts\activate`

    -   Install the required dependencies:

        bash

        Copy code

        `pip install -r requirements.txt`

    -   Run migrations to set up the database:

        bash

        Copy code

        `python manage.py migrate`

    -   Start the Django server:

        bash

        Copy code

        `python manage.py runserver`

2.  **Frontend Setup** (React.js):

    -   Navigate to the `frontend/` directory:

        bash

        Copy code

        `cd ../frontend`

    -   Install the required packages:

        bash

        Copy code

        `npm install`

    -   Start the React development server:

        bash

        Copy code

        `npm start`

3.  Access the app: Open a browser and go to `http://localhost:3000` to view the web application.
