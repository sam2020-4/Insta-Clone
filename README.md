# Insta-Clone

### Description
##### Insta-Clone is a platform where users can display their photos for others to see, they can also see other peoples photos.They can like and comment on the post as well.
**** View [Live-Link](https://pics2020.herokuapp.com/)

### Author
matata samuel

### Screenshot
<img src="https://github.com/sam2020-4/Screenshot from 2020-10-20 13-58-38.png" width="1000">

### Requirements
##### These are the requirements you need to get the project running locally on your machine:
  - Text Editor e.g vscode or atom
  - Install python3+
  - Install and activate virtual
  - Setup Database
  - Install Django

### Installation Process
##### Download any text editor of your choice, either Sublime, Visual-Studio-Code or Atom.
##### Install your preferred version of python
  - ```sudo apt-get install python3.8```.
  - ```python --version``` to confirm that python has been installed.
##### Open the command-line and run the following command to open a directory:
  - ```cd your preferred directory``` => ```cd Desktop```
##### Git clone the project on your current directory by:
  - ```git clone https://github.com/sam2020-4/Insta-Clone``.
##### Open the project on your terminal:
  - ```atom . or code .``` , according to the type of your text editor.
##### Move to your project directory:
  - ```cd Insta-Clone```.
##### Install virtual environment using python:
  - ```python3.8 -m venv virtual```, check your project to confirm you have a folder called virtual,
  - then activate it by running ```source virtual/bin/activate```
##### To install the packages in the ```requirements.txt file```,
  - ```pip install -r requirements.txt```  That will install all packages including Django.
##### To open python shell:
  - ```python3.8``` ,
  - ```import django```
  - And lastly ```django.get_version()``` to see and confirm the version of django installed.
  - You can then ```ctrl z``` to get out of the shell,
##### After confirming you have all this
  - ```python3 manage.py runserver``` to run the project.
  - Then click the local host link given to open the project on a browser ```http://127.0.0.1:8000/```.


#### For more information read the following django and python documentation:
  - [DjangoDocumentation](https://docs.djangoproject.com/en/1.11/intro/install/)
  - [PythonDocumentation](https://www.python.org/doc/)


### User Stories
- As a user, I would like to view different photos that interest me.
- As a user, I would like to click on a single photo to expand it and also view the details of the photo.
- As a user, I would like to search for different categories of photos.
- As a user, I would like to POST a picture so to other users to see when they login.
- As a user, I would like to view photos and leave comments.

### Behavior Driven Development
- The application should display photos.
- When a user clicks on a photo, the photo should expand and the details of the photo to be displayed on a modal within the main page.
- When a user enters a search term on the search input and submits it, then they should be able to get a result of what they are looking for or if the term does not exist, they should get a message to inform them.
- When a user clicks on a picture, the picture displays separately from in another page whereby you can leave your comment there.

### Technologies Used
- Python
- Django Framework
- PostgreSQL
-HTML5
- Bootstrap

## Dependencies
- Postgresql

### Licence
[MIT](LICENSE)

### Contact
##### mattasamuel3@gmail.com
