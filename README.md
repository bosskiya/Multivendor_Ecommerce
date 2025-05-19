## Multivendor Ecommerce Website
===========================================
An Ecommerce website with multivendor

# Features
------------------------------------------
-   Website
    -   Home Page
        -   Header
        -   Latest Projects
        -   Popular categories (According to product download count)
        -   Popular projects (According to product download count)
        -   Popular sellers (According to product download count)
        -   Footer
    -   All category list
    -   All product list according to category
        -   Sort according to price, latest, alphabet, views
    -   Product detail
    -   Checkout Page
        -   PayPal
        -   RazorPay
        -   Stripe
    -   Order Success Page
    -   Order Failure Page
    -   Multilingual
=================================================================
-   Customer Panel
    -   Register
    -   Login
    -   Forgot password
    -   Dashboard
        -   Orders
            -   Downloads Scripts
        -   Profile
        -   Change password
=================================================================
-   Seller Panel
    -   Register
    -   Login
    -   Forgot password
    -   Dashboard
        -   Manage Categories
        -   Manage Products
        -   Orders
        -   Customers
        -   Profile
        -   Change Password
==================================================================
-   Admin Panel
    -   Manage Sellers
    -   Manage Categories
    -   Manage Products
    -   Manage Customers
    -   Manage Orders

# Setup Projects and Creating Database Model
------------------------------------------
1.  Python
2.  Install Virtual Environment 
    -   pip install virtualenv
3.  Create Virtual Environment 
    -   python3 -m venv env (Unix or MacOS)
    -   py -m venv env (Windows)
4.  Activate Virtual Environment 
    -   source env/bin/activate (Unix or MacOS) 
    -   .\env\Scripts\activate (Windows)
5.  Install Django
    -   pip install django
6.  Creating New Django Projects
    -   django-admin startproject backend
7.  Run Django Project
    -   python3 manage.py runservers
8.  Install PostgreSQL
    -   https://www.postgresql.org/docs/
9.  Install pgAdmin4
    -   https://www.pgadmin.org/
10. Install Python library for PostgreSQL
    -   pip install psycopg2-binary
11. Install Django Rest Framework
    -   pip install djangorestframework