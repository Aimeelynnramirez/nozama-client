# Nozama - Front End Client
Team Project By:
- Aimee L Ramirez
- Will J Britton
- Christian Mignacca
- Ash Trull

## Introduction

## Deployed Links

- Deployed Client:

- API Repo:

## User Stories

## Technologies Used
# Nozama - Front End Client
Normal Text

<p align="center">
  <b>Team Project By: </b><br>
  <a href="#">Aimee Ramirez</a> |
  <a href="#">Ash Trull</a> |
  <a href="#">Christian Migncca</a> |
  <a href="#">Christian Migncca</a>
  <br><br>
</p>

Normal text

## Introduction

Welcome to the Front End repository for our third project with GA, our team project.  We all learned quite a lot throught the process.  It was a great team effort and we look forward to continue working to really polish it up.

Our prompt was to build Nozama, a site similar to Amazon.  We decided to act as though we were amazon rolling our a new food shopping piece of their site since they accquired Whole Foods.  We named it Peach.

## Links

- Deployed Client:

- [API Repo](https://github.com/wdi-team-project/nozama-express-api)

## User Stories


- As a user I want to be able to log in, log out so that I can save my products to purchase later

- As a user I want to see what you’re selling so that I know what kind of website I’m at (e-commerce)

- As a user I want to add products to my cart so they can purchase them all at once

- As a user I want ways to navigate out of every page so that I’m never stuck/rat-trapped

- As a user I want to be able to actually purchase my products

- As a user I want my cart to show my products, quantities, costs

- As a user I want to be able to add multiple of one product to my cart or remove products from my cart

- As a user I want to be able to edit my cart so that I can add more or delete from my cart before I check out

- As a user I want to be able to contact customer service if I have any questions about the products or checkout process

- As user I want there to be uniformity in product listings so I can easily find the information I need


- As an admin I want users to only be able to add products to a cart when tehy’re logged in for simplicity of process

- As an admin I want orders to show up in an orders collection when customers purchase their cart


## Technologies Used

- HTML:
  - Used html to build skeleton of page.
- CSS:
  - Used classes/Id to style page.
- Sass:
  - Set Sass keys to keep a consisten color scheme, font, and more
- Bootstrap:
  - Used Grid system to organize the page.
- jQuery:
  - Managed event handlers for user actions as well as displaying information
- AJAX:
  - Make calls to the api
- JavaScript:
  - Multiple functions used for web ui/interaction

## Planning Process / Approach

- Download Browser Template -
- Create a github Repo
- Deploy to github pages
- Create file directory setup
- Create landing page
  - Header
  - Navbar
  - Auth box
  - Search bar
  - Structure for inventory
  - Add image anchors to product listings
  - Expand view/More details option
- Create My Cart page
  - Handlebars table for items stored in cart
- Login functionality
  - Signup (POST)
  - Signin (GET)
  - Signout (DELETE)
  - Change password (PATCH)
  - Click handlers
- Product interface
  - Add to cart (POST)
- Add functionality to My Cart
  - Show My Cart (GET)
  - Change quantity (PATCH)
  - Remove from cart (DELETE)
- Design
  - Design logo
  - Add header with logo
  - Color scheme
  - Add images to products

## Wireframe

![alt text](https://i.imgur.com/rpL2W4D.jpg "WireFrame V1")

## Data Model ERD

![alt text](https://i.imgur.com/rpL2W4D.jpg "WireFrame V1")

## Unsolved Issues

- Need to Integrate stripe
- Need smoother/cleaner user Interactions
- Function getProducts should be refactored and modularized btwn events.js api.js and ui.js. There is ui stuff in the api file
