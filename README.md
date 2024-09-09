# Cour CPGE

This is a full-stack project that uses **Django** for the backend and **React (with Vite)** for the frontend.

## Prerequisites

Make sure you have the following installed on your machine:

- Python 3.x
- Node.js (with npm or yarn)
- Git

---

## Backend Setup (Django)

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/my-django-vite-project.git
cd my-django-vite-project
```

### 2. Set Up a Python Virtual Environment

It's best practice to use a Python virtual environment to isolate project dependencies.

#### Create a Virtual Environment

Run the following command to create a virtual environment in the root of your project directory:

```bash
# On Mac/Linux
python3 -m venv env

# On Windows
python -m venv env
```

#### Activate the Virtual Environment

To activate the virtual environment, run:

```bash
# On Mac/Linux
source env/bin/activate

# On Windows
env\Scripts\activate
```

After activation, your terminal prompt should show that you're inside the virtual environment (e.g., `(env)` at the beginning of the line).

### 3. Install Python Dependencies

Once the virtual environment is activated, install all necessary Python packages by running:

```bash
pip install -r requirements.txt
```

This will install all the dependencies listed in `requirements.txt`, including Django, Django Rest Framework, and any other required packages.

### 4. Run Django Development Server

After installing the dependencies, run the following commands to apply database migrations and start the development server:

```bash
python manage.py migrate
python manage.py runserver
```

Your Django backend will now be running at `http://127.0.0.1:8000`.

---

## Frontend Setup (Vite/React)

The frontend is built using React with Vite. Follow these steps to set up the frontend.

### 1. Navigate to the Frontend Folder

Move into the `frontend/` directory:

```bash
cd frontend
```

### 2. Install Node.js Dependencies

Install all the dependencies for the frontend using npm (or yarn):

```bash
# If you're using npm
npm install

# Or if you're using yarn
yarn install
```

### 3. Run the Vite Development Server

Start the Vite development server using the following command:

```bash
npm run dev
```

This will start the frontend server, and you can access it at `http://localhost:5173`.

---

## How to Stop the Virtual Environment

To deactivate the Python virtual environment when you're done working on the project, simply run:

```bash
deactivate
```

This will return your terminal to its normal state.

---

## Additional Notes

- Make sure to always activate the virtual environment before running Python-related commands.
- Whenever you install a new Python package, run `pip freeze > requirements.txt` to update the `requirements.txt` file, so others can easily install the necessary packages.
- You can push updates or collaborate with others through this repository.

---

### Contact

If you run into any issues, feel free to open an issue or contact me.

---

This `README.md` file provides step-by-step instructions for setting up both the Django backend and the React (Vite) frontend, ensuring the project is easy to clone, set up, and run locally.
