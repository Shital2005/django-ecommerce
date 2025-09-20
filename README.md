<div align="center">
  <h3 align="center">Django E-commerce Project</h3>
  <p align="center">A Django project from Codemy.com on Django Wednesdays.</p>
</div>

---

## About The Project

A full-stack e-commerce app with product categories, shopping cart management, and checkout functionality. It includes features to add products, update the cart, and manage orders from a simple homepage.

<img width="1270" height="1151" alt="screenshot" src="https://github.com/user-attachments/assets/84d67aec-5355-4c5e-a6e8-2d573ffbb969" />

### Built With

* [Django](https://www.djangoproject.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/)
* [JQuery](https://jquery.com/)

---

## Getting Started

This section provides instructions on how to set up and run this project locally.

### Installation

1.  **Prerequisites:**
    * Python 3.8+ installed
    * Git installed (if you want version control)

2.  **Navigate to the project directory:**
    * Open your terminal or command prompt and change your current directory to where you want to clone the project.

3.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```

4.  **Activate the virtual environment:**
    * **Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    * **macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

5.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

6.  **Create environment variables file:**
    * Create a `.env` file in the root directory of your project (e.g., `d:\django-ecommerce\.env`) with the following content:
        ```
        DJANGO_SECRET_KEY=your-secret-key-here
        DEBUG=True
        ALLOWED_HOSTS=localhost,127.0.0.1
        ```
    * **Note:** Replace `your-secret-key-here` with a strong, unique key for production environments.

7.  **Navigate to the Django project directory:**
    * Ensure you are in the directory containing `manage.py`.

8.  **Run database migrations:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

9.  **Create a superuser (admin account):**
    ```bash
    python manage.py createsuperuser
    ```
    * Follow the prompts to create your admin username, email, and password.

10. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

11. **Access the application:**
    * **Main site:** `http://127.0.0.1:8000/`
    * **Admin panel:** `http://127.0.0.1:8000/admin/`

---

## Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request.

1.  Fork the Project
2.  Create your Feature Branch 
3.  Commit your Changes 
4.  Push to the Branch 
5.  Open a Pull Request

---

## Acknowledgments

* [John Elder from Codemy.com](https://codemy.com/)
