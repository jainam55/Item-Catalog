# Item-Catalog
Item Catalog Application project is a part of Udacity full-stack web development nano-degree.

# About
The Item Catalog application is an RESTful web application developed using the Python framework Flask along with implementing third-party OAuth authentication.
This application provides a list of items within a variety of categories as well as provides a user registration and authentication system. 
Registered users will have the ability to post, edit and delete their own items.

# Skills Used
- Python
- Flask
- CSS
- HTML
- JavaScript
- Bootstrap
- ORM - SQLAlchemy
- OAuth
- SQLite

# Requirements
- Python
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)
- [VagrantFile](https://github.com/udacity/fullstack-nanodegree-vm)

# Initial Setup
- Download or clone the VagrantFile repo given in the link.
- Clone this repo where the vagrantfile is or place the vagrant file where you downloaded or cloned this repository.
- Navigate through the directory on your local machine.
- Execute in commange line
```
vagrant up
vagrant ssh 
```
              
- Navigate through the virtual env by typing ```cd /vagrant```
- Setup the database by ```python database_db.py```
- Once the database has been setup execute at command following code to run the program , ```python project.py```
- Open Browser and run the url http://localhost:5000
