# Milestone-Project-3
<p align="center"><strong>Milestone Project 3</strong>

<p align="center"><strong>Python and Data Centric Development</strong> 

<p align="center"><strong>Code Institute</strong>

<p align="center"><strong>Dolan's Good Books</strong> 

A Book review site where users can add a book to the site,edit a book a user has created and view other users comments and ratings.

The project has a couple of pages:

1:A homepage that allows users to search for a book, and view other books created by users with their comments and ratings.

2:A login page where users can either login or register for an account.

3:A page where a user can add a new book to the site.

4:Page where user can edit a book they have created on the site.

5:Page where the admin of the site can add or edit categories that is used for books.

[Link to website](https://milestone-project-3-book.herokuapp.com/) here to see the website.

![Website](static/images/dolans_good_books.png)

## Table of Contents
> - [UX](#ux)
> - [User Stories](#user-stories)
> - [Strategy](#strategy)
> - [Scope](#scope)
> - [Structure](#structure)
> - [Surface](#surface)
> - [Icons](#icons)
> - [Skeleton](#wireframes)
> - [Features](#features)
> - [Features Left to Implement](#features-left-to-implement)
> - [Technologies Used](#technologies-used)
> - [Libraries](#libraries)
> - [Version Control](#version-control)
> - [Other](#other)
> - [Testing](#testing)
> - [Deployment](#deployment)
> - [Credits](#credits)
> - [Acknowledgments](#acknowledgments)

## UX:

## User Stories:
As a User:

"I want to see all the books on this site that users have rated and commented on"

![Book List](static/images/show_books.png)

"If there is a book im interested in, i want to learn more about this book and where to go to buy it"

![Book Details](static/images/show_books.png)

"I want to either create an account or login to the site so that i can add my own book details"

![Register](static/images/register.png)

![Login](static/images/login.png)

"I want to fill out a form that will allow me to add a book to the site for other users to see"

![Add Book Link](static/images/add_book_link.png)

![Add Book](static/images/add_book.png)

"I want to fill out a form that will allow me to edit a book i have already created on the site"

![Edit Book Link](static/images/edit_book_link.png)

![Edit Book](static/images/edit_book.png)

As an Admin:

"I want to add a new book category to the site"

![Add Category Link](static/images/add_category_link.png)

![Add Category](static/images/add_category.png)

"I want to edit a book category on the site"

![Edit Category Link](static/images/edit_category_link.png)

![Edit Category](static/images/edit_category.png)

"I want to delete a category from the site"

![Delete Category Link](static/images/delete_category_link.png)

## Strategy:
I wanted to create a user friendly website that would have Create,Update,Read and Delete (CRUD) functionality.

## Scope:
I created a database for the website on MongoDB,see below schema

![Database Schema](static/images/database_schema.png)

## Structure:
I wanted users to see all the books on the site that have been rated and commented on.

I would then direct them to the Login/Register pages.

After the user has logged in they would now have the option of adding a book to the site.

If the admin has logged in they would now have the option of deleting/editing books,and adding/editing categories.

I also provided my profile links to GitHub and LinkedIn.

## Surface:
I used various text colors to make it stand out against the background.

The orange background footer and red background header was chosen to stand out on the site.

## Icons:
I used Font Awesome for the social media icons of GitHub and LinkedIn,as well as for various icons seen throughout the site.

## Wireframes:
I have included wireframes for each page on this website, click on the below page names to see these wireframes:

[Add Books](wireframes/Dolans_Good_Books_Add_Books.pdf)

[Add Category](wireframes/Dolans_Good_Books_Add_Category.pdf)

[Edit Books](wireframes/Dolans_Good_Books_Edit_Books.pdf)

[Edit Category](wireframes/Dolans_Good_Books_Edit_Category.pdf)

[Homepage](wireframes/Dolans_Good_Books_Homepage.pdf)

[Login](wireframes/Dolans_Good_Books_Login.pdf)

[Manage Categories](wireframes/Dolans_Good_Books_Manage_Categories.pdf)

[Admin Profile](wireframes/Dolans_Good_Books_Profile_Admin.pdf)

[Profile](wireframes/Dolans_Good_Books_Profile.pdf)

[Register](wireframes/Dolans_Good_Books_Register.pdf)
                               
## Features:

<p align="center"><strong>Existing Features:</strong>

## Features Left to Implement:

## Technologies Used:

[HTML](https://html.com/)
Used to create the structure of the web site.

[CSS](https://www.w3schools.com/css/css_intro.asp)
Used to style the website.

[Python](https://www.python.org/)
Used to create the CRUD functionality.

[Materialize](https://materializecss.com/about.html)
Used to design the site for mobile users and for other features.

[MongoDB](https://www.mongodb.com/)
Used to store the database used for the site.

[Heroku](https://id.heroku.com/login)
Used to host the site.

## Libraries:
[FontAwesome](https://fontawesome.com/)
Used frequently for icons used throughout the website.

[Balsamiq](https://balsamiq.com/wireframes/?gclid=EAIaIQobChMIn-_lgbiJ7QIVn4BQBh1X3Av6EAAYASAAEgL1XfD_BwE)
Used for the creation of wireframes.

[Python Flask](https://flask.palletsprojects.com/en/2.0.x/)
Used for the main development of the site.

## Version Control:
[Github](https://github.com/) - Used to store the code and use of Github Pages to deploy the website. 

[Gitpod](https://gitpod.io/) - Used as the primary version control IDE for development to further push and commit code to Gihub.

## Other:
[Code Institute Course Content](https://courses.codeinstitute.net/) - Primary source of learning code.

[W3Schools](https://www.w3schools.com/) - used as a general resource for CSS and coding tips.

[StackOverFlow](https://stackoverflow.com/) - used as a general resource for layout tips or questions.

[AmIResponsive](http://ami.responsivedesign.is/) - Used to check how the layout of the website looks across different devices. 

## Testing:
<p align="center"><strong>Manual Testing of the site</strong></p>

<p align="center"><strong>User Stories Testing</strong></p>

<p align="center"><strong>Site Responsiveness</strong></p>

<p align="center"><strong> HTML Validation</strong></p>

HTML - [W3C](https://validator.w3.org/) - Markup Validation.

![Add Book](static/images/add_book_validation.png)

![Add Category](static/images/add_category_validation.png)

![Base](static/images/base_validation.png)

![Books](static/images/books_validation.png)

![Categories](static/images/categories_validation.png)

![Edit Book](static/images/edit_book_validation.png)

![Edit Category](static/images/edit_category_validation.png)

![Login](static/images/login_validation.png)

![Profile](static/images/profile_validation.png)

![Register](static/images/register_validation.png)

<p align="center"><strong> CSS Validation</strong></p>

CSS - [W3C](https://jigsaw.w3.org/css-validator/) - CSS Validation.

[Validation Result](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fgithub.com%2FSeanD17%2FMilestone-Project-3%2Fblob%2Fmain%2Fstatic%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

<p align="center"><strong>Project Bugs and Solutions</strong></p>

<p align="center"><strong>Remaining bugs</strong></p>

## Deployment:

I did the following to deploy my site:

Removed all my hard-coded environment variables. 

These were placed in the Heroku Config Vars for production.

Ensured the applications requirements.txt is up-to-date with all the latest packages installed for my app being noted on this file.

The command to update requirements  is pip3 freeze > requirements.txt

Set up the Procfile - A Procfile is required by Heroku in order to tell the service worker what command to run for my application to start.

Set Flask's debugging to False.

Pushed all my latest production ready code to GitHub ready for deployment via Heroku's GitHub function where you can deploy from GitHub the production ready app.

Upon successful deployment Heroku will give you the URL that is hosted your app

If you want to create a copy of this site on GitHub,do the following:

To access the code, it can be run locally by either selecting "clone" which provides an URL one can use on their local machine or "download" which is where one can download the zip file on to their machine.

Install the projects requirements.txt using pip3 install -r requirements.txt

You will need to update a few environment variables before you can run the app.

app.config["MONGO_DBNAME"] = "cookbook_creation"
app.config["MONGO_URI"] = os.getenv("MONGO_URI", "monogodb://localhost")
app.config["SECRET_KEY"] = os.getenv("SECRET_KEY")

Once the above steps are complete you can try run the application using python3 main.py

## Credits:

## Content:
All text content in this website was written by me.

## Media:
The photos used in this site were obtained from:

Bookshelf background gotten on<a href="https://unsplash.com/s/photos/bookshelf?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"> Unsplash</a>
  
  
## Acknowledgments:
I received inspiration for this project from my mentor Nishant Kumar.

I also received inspiration from an Bootstrap mini project that was taught to us as part of our course.
