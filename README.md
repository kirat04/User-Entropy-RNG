# User Entropy Random Number Generator

This project is a full-stack application that combines Django and React to create a Random Number Generator (RNG) with user input. The user provides an input (like a name, a phrase, or any kind of text), and the application uses this input to generate a random seed that can then be used to generate random numbers.

## Project Overview

### Frontend (React):
- User provides an input (e.g., a name, phrase, or any text).
- React sends this input to the Django backend.
- The backend uses this input to generate a random seed.
- The frontend displays random numbers generated from that seed.

### Backend (Django):
- Django receives the user input from the frontend.
- Using the input, it generates a random seed using Python’s random module.
- Django sends the generated random number(s) back to the frontend.

## Project Setup

### Prerequisites
- Python
- Node.js
- Django
- React
- pip (Python package installer)
- npm (Node package manager)

### Backend (Django) Setup
1. Navigate to the project directory:
    ```sh
    cd rng_project
    ```

2. Install Django and Django REST Framework:
    ```sh
    pip install django djangorestframework
    ```

3. Run database migrations:
    ```sh
    python manage.py migrate
    ```

4. Start the Django development server:
    ```sh
    python manage.py runserver
    ```

### Frontend (React) Setup
1. Navigate to the frontend directory:
    ```sh
    cd frontend
    ```

2. Install the required npm packages:
    ```sh
    npm install
    ```

3. Start the React development server:
    ```sh
    npm start
    ```

Now, your React app should be available at [http://localhost:3000](http://localhost:3000), and your Django backend at [http://localhost:8000](http://localhost:8000).


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```` ▋
