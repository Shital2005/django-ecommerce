

<h3 align="center">Django Ecommerce Project</h3>

  <p align="center">
    A Django project from Codemy.com on Django Wednesdays. 
  

<!-- ABOUT THE PROJECT -->
## About The Project

A full-stack e-commerce app with product categories, shopping cart management, and checkout functionality.
Includes features to add products, update the cart, and manage orders from a simple homepage.


<img width="1270" height="1151" alt="screenshot" src="https://github.com/user-attachments/assets/84d67aec-5355-4c5e-a6e8-2d573ffbb969" />



### Built With

* [Django](https://www.djangoproject.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/)
* [JQuery](https://jquery.com/)


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### Installation


1.Prerequisites

   Python 3.8+ installed

   Git installed (if you want version control)


2. Navigate to the project directory

3. Create a virtual environment

4. Activate the virtual environment

5. Install dependencies

6. Create environment variables file
Create a .env file in the root directory (d:\django-ecommerce\.env) with the following content:

DJANGO_SECRET_KEY=your-secret-key-here

DEBUG=True

ALLOWED_HOSTS=localhost,127.0.0.1



7. Navigate to the Django project directory

8. Run database migrations

python manage.py makemigrations

python manage.py migrate


9. Create a superuser (admin account)

python manage.py createsuperuser


11. Run the development server

python manage.py runserver

12. Access the application


Main site: http://127.0.0.1:8000/

Admin panel: http://127.0.0.1:8000/admin/


<!-- CONTRIBUTING -->
## Contributing



If you have a suggestion that would make this better, please fork the repo and create a pull request. 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [John Elder from Codemy.com](https://codemy.com/)


