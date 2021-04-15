![Welcome](https://s3.eu-central-1.amazonaws.com/food-delivery-app/static/images/sushi.jpg)

## Travis CI Build status

[![Build Status](https://travis-ci.org/nikl881/food-delivery-app.svg?branch=master)](https://travis-ci.org/nikl881/food-delivery-app)


## Sushi Delivery Express 

The Sushi Delivery Express project is a 'take-away' webapp to select sushi from the menu and order dishes using customer adres- and payment information (creditcard). The general purpose of this website is to search, select and purchase sushi dishes.
The chosen design and layoutstyle is a typical asian order delivery webapp with a clear function and usability. It is logical for the user to create an account  and then use the offered services.
This data-driven website has a dynamic setup. This means that the user can create an account, update account settings, order food en checkout using the orderlist cart and checkout function.
The user also can search for dishes based on name criterea inside the order page. The website is fitted for mobile, tablet and desktop (fully responsive). 


Niels de Klerk (May, 2019)


## Features

Existing Features (week 17 - 2019) 

* Landing page with a slideshow of example sushi dish images and a clear navigation bar. 
* Register page, so a new customer can create an account. 
* Login/Logout page, a clear and simpel page that will login a user with a single mouse click.
* Sushi menu page, overview of all available sushi dishes, including images, price information and quantitiy information.
* Order/Cart page, a short overview page with a summary of the total costs of the order.
* Checkout page, includes billing and adres information to complete the order, incuding verification on on completed fields.


Features Left to Implement 

* Customer rating/upvotes of individual dishes.
* Geographical page of delivery location (maps). 


## Usage of Django and Stripe

The webapp has been build with Django. Stripe, which is a tool for e-commerce that allows both private individuals and businesses to accept payments, is implementet and has been integrated into this Django app. Amazon Web Services is a subsidiary of amazon.com that provides on-demand cloud computing platforms to individuals and companies.
The  AWS cloud storage service (S3) has been used into this Django project. On S3 all static and media files are saved in the AWS backend.


## Technologies Used

In this section all of the languages, frameworks, libraries, and other tools that have been used are mentioned. 

*	HTML 5 <br/>
    The website uses HTML5 as a fundamental basis for building the website.

*	CSS3 <br/>
    The website uses CSS3 with regard to the styling of all elements within the website. For this a separate layout has been created within the page structure. 
    CSS is used for all content, including: images, layout of color and background, etc.

*	Bootstrap 3.7.6. <br/>
    The open-source Bootstrap framework has been used to implement some basic templates for forms, buttons and navigation. 
    Bootstrap has also been used to stand with a responsive design of the web page.

*	Cloud9 <br/>
    AWS (Amazon) Cloud9, a cloud-based integrated development environment (IDE) that has been used to write, run, and debug the code used for the website. 
 
*	GitHub <br/>
    GitHub has been used for version control of the code by using Git. 
    During the realization of the project, Git was daily used.

*	Core JavaScript<br/>
    Core Javascript has been used to use the event handling functionality's on specific buttons. 

*	Jquery libraries<br/>
    Jquery has been used for most interactive parts. 

*	Fontawesome<br/>
    Fontawesome as a toolkit has been used to the UX/UI, especialy for icon styling. 

*   Heroku <br/>
    In this project data is actually transported between frontend and backend, GitHub pages are no longer sufficient as a project deploy location on its own. 
    That is why Heroku has been used to facilitate this functions of the application.
    During the realization of the project, Git deployment was daily used.

*   Python / Flask <br/> 
    An important aspect of this project is the dynamic generation, modification and adaptation of data. 
    This is made possible by different routes between pages and data. 

*   Postgres Database <br/>
    Database is used to load products and to store the user input. 
    The project connects to a Postgres database using Django’s ORM.

*   AWS Amazon webservices </br>
    Used to host the project (using S3).

*   Travis CI <br/>
    Used for testing and continuous integration of the development of the webapp. 

*   Stripe <br/>
    Stripe provides APIs that are used to integrate payment processing into the application (Django checkout app). 

## UX perspective 

The documents of the preparation phase are included in a separate project location, which can be found at in the link below. 
This includes wireframes and mockups and basic images for the branddesign. Link to the external project documentation: https://drive.google.com/drive/folders/1j0HzRKoam8EjZAPFfb7HS6ehQz7dCioG?usp=sharing

## Database schema and initial design

In order to make a good and deliberate start with this project, careful consideration was given first to the exact data flows that will become part of the (dynamic) content of the website.
I have decided to use a postgres database.This because it is quite straightforward to link individual data.

## Work method 

During the development of this project Trello (Trello.com) is used as a simple project management tool to develop in a controlled project environment. I have used the 'trello-board' for all the 
actions within the project; initializing the project until the completion. The trello-board has been used for: 

* preperation actions / conceptualization
* building functionalities (mini sprints)
* testwork 
* debugging / issue tracking

Below a screenshot of the projectmanagement board of Trello taken during the development of this project.

![Trello](https://food-delivery-app.s3.eu-central-1.amazonaws.com/media/images/screenshot+trello.png)


## Testing

Various methods have been used to test the code of the website. During development, there has been continuously tested on the quality of the code. 
This has been done by checking the correct functionality of the code on different screensizes, different resolutions,
different devices (mobile, tablet, desktop). This approach is used from the start to the end of the realization of the project.Separate test scripts have been created to test views.py, forms.py (checkout) and models.py.

PEP8 was used to check the quality of the python code. This is an online validator to check whether the code complies with the PEP8 directive.
Besides, flake8 is used for additional Python style validation.


The code has been tested on the following devices and is fitted for purpose on a laptop, desktop or large desktop: 

    * Macbook 13" 
    * Windows 10 desktop 27" 
    * Iphone 10
    * Huawei mate 20 lite
    * Huawei P30 pro
    
Site viewed and tested in the following browsers:

    * Firefox
    * Chrome
    * Safari 
    * Internet Explorer    
    
Mockups and sketches were also used to continuously build and deliver in accordance to the initial plan and design of the website.
In the final phase of the project, the opinion of a number of people was asked. I asked programmers and non professionals to see iff the site functions properly from a certain perspective. 
In order to be able to check whether the code functions as it was conceived during the design phase, we tested the functions on a basis of different scenarios.
Below the main features described that are basic functions as currently available on the site.

* Main navigation and information - 
    * Navigate back and forth using the main navigation function (menu).
    * Try to navigate on different devices with different screenresolutions within the main navigation. 
    * Use specific navigation buttons, i.e. 'cart' or 'checkout'. 
  
* Use of the order page - 
    * Select a single and multiple sushi dishes. 
    * increase the number of selected dishes.
    * deselect a dish.
 
* Use of the cart page - 
    * Change the amout of selected dishes.

* Use of the create account page - 
    * Try to make a new useraccount and login.
    * Try to reset password

* Use of the checkout page - 
    * Enter false payment details.
    * Enter correct payment details (and checkout).



## Issuelist 

| Issue number    | Description     | Implemented Solution  |
| ------------- |:-------------:| -----:|
| 1	| Django /checkout/ app won't load | Rebuilding urls.py and settings.py until configuration loaded succesfully  |
| 2	| Images are uploaded in AWS backend but wont show to live project |  re-studied the theory and learned more about using 'collectstatic'  |
| 3	| Failure of Travis CI builds  | Removing unnecessary requirements in requirements.txt and adjusting the version of certain dependencies.  |
| 4 | Failure of Travis CI builds II  | Build failure because 'import env' was still included in the general settings.py of the web app. Removed this |
| 5 | Failure of Travis CI builds III  | Removed incompliant test database fields from env.py |
| 6 | custom CSS won't load | Changed the hierarchy and order of loading files. |
| 7 | Heroku could not deploy  (git staging had no issues) | Changed Procfile to similair procfile on Heroku dashboard  |
| 8 | Filter route wont show result of selected filter options | Changed the route from base.html   |
| 9 | Security variable / PORT settings - give a authentification error | Followed the lessons again to link the database to the working environment in cloud9. Reconfigured and resolved the issue.  |


## Deployment

The website is made in the AWS Cloud9 environment. To give a good idea of the development progress, short deliveries are always placed at the workspace on Heroku and GitHub. 
During the development period a upload was made to GitHub after every 3 to 4 hours of development work or after a relative bigger change to the code. The way the Git process is used is as follows:

1. Builded the site on a local environment.
2. Staged the files in the stage area.
3. Perform push to Heroku (workspace / remote app)
4. Perform push to Github (Git directory / repository) in comments section.
5. After a inspection (validation) merged comments section to master branch.


Because this project has a dynamic and data-driven design, it was decided to use Heroku to host this python project. The following method has been used to achieve a good deployment:

1. Set up the initial app.
2. Link the local Git repository to Heroku.
3. Create a requirements.txt file, which contains a list of the project dependencies.
4. And finally, created a Procfile, the file that tells Heroku how to run the project.


*   The live version of the project is available at the following link: https://akitos-sushi-express.herokuapp.com/

## Credits

This README file is based on the Code Institute template.

## Media

*  The used recipe images/photo's are downloaded from the Shutterstock database (https://www.shutterstock.com), from Istockphoto (https://www.istockphoto.com/nl), and from Adobe Images (used Adobe Pro).

