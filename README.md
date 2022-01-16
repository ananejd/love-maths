# LOVE MATHS
## JAVASCRIPT WALK THROUGH PROJECT WITH CODE INSTITUTE



The project is a maths game built using Javascript.
The project allows a user to practice their mental maths skills.

<hr>
Find a live version <a href="http://ami.responsivedesign.is/?url=https://jd-agritrade.herokuapp.com/">here</a>


## UX Design



##Scope
A MVP (minimum viable product) includes:

- landing page displaying a picture of a lovely looking chick 
- A search input area for looking for products
- An Area for accessing your account or setting up one.
- A basket button 
- A library button acting as a dropdown menu for various categories of products
- A shop now button that displays all products on offer.


### User stories

**ID** | **As a/an** | **I want to be able to...** | **So that I can**
--- | --- | --- | ---
1 | Site User | Register to the site | Log in to my account 
2 | Site User | Log In and Log Out | View my profile
3 | Site User | Receive email confirmation | Confirm successful registration
4 | Site User | Have a user profile | View my purchases, and be able to check my order history
5 | Potential customer | View some products | Select to purchase
6 | Potential customer | View details of products | See price and description
7 | Potential customer | Pay for the products i like | Buy
8 | Customer | View products in my bag | Check the cost to review
9 | Customer | Enter payment information and see that process is secure | Checkout without issues
11 | Administrator | Add new catergory of products | To make them visible to customer
12 | Administrator | Edit or update various categories | To change a pric and/or description 
13 | Administrator | Delete a category of products | To remove from a site

## Features

### home

The home page greets farmers with a picture of a beautiful chick with a SHOP NOW button. 
The SHOP NOW button invites farmers to take a look at the various products on offer.
Farmers are also informed of a delivery fee waiver over a specific amount.
Various icons in the header helps summarize the various products the site offers to the visitor of the website.

### SEARCH AREA 

the search area allows users of the website to directly search for their product of interest without combing through the site.

### MY ACCOUNT

The MY ACCOUNT icon allows users to setup an account on the website or accessing their existing account on the website.

### ALL PRODUCTS 

The ALL PRODUCTS icon when clicked on offers the site user a categorisation of the products on offer. 
ie by pricing, rating and a view of all products.

### POULTRY PRODUCTS 

This link allows the user of the website to assess specific poultry products being sold on the site.
ie Eggs, Dressed Chicken, Live Birds and Point of lay chicks.

### POULTRY FEED 

This links allows the users of the website to assess Poultry feeds sold on the website

### Basket

The basket button on the right side of the navigation bar is meant to hold a list of items 
that have been reviewed by the site user awaiting payment.

### Wireframes

- Home Page

    <details><summary>Desktop (click to view)</summary>

    ![](<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2F9eOMIaCWLS6u7WBXtREDNX%2Fcraftstore%3Fnode-id%3D1%253A27" allowfullscreen></iframe>)
    </details>
    
    
    ![](static/images/Wireframe.png)
    </details>
## Technologies Used

- HTML5
- CSS3
- JavaScript
- Python
- Bootstrap
- FontAwesome
- Google Fonts
- jQuery
- Django
- Git
- Heroku
- GitHub
- AWS S3 bucket

## Database Schema

Database contains 3 table:
- user
- categories
- products

I use Django default databases SQLite in gitpod environment and PostgreSQL database with Heroku as production enviroment.


### Security

All sensitive access keys are stored as `Config Vars` on Heroku cloud application platform.
Django allauth was used to meet security requirements.

## Deployment
This project was built using Python 3.8.6 and Django3.2.4
1. The project was deployed to Heroku with config vars:
1. created requirements.txt that Heroku knows which packages are required for the application to run and install them.
1. created Procfile that Heroku knows what kind of application this is.
1. project eventually deployed at 
<a href="https://jd-agritrade.herokuapp.com/">here</a>">

#### Challenges 

There was a difficulty in linking the database to the heroku app for which the developer continues to work on.

### project inspiration: 

1. inspiration for this project were largely drawn from video tutorials of the code institute on Full stack development with Django. 
1. Appreciation goes to the code institute student support team for being very supportive throughout my period
   study with the code institute
1. Im grateful to my Alexander of the student care team at the code institute for his time and help throught this project 