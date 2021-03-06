Original App Design Project - README Template
===

# Recipe App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Use API to get food recipes that will be stored in the application and users can access to try the recipes for themselves. Users will also be able to create their own recipes that they can save.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Productivity
- **Mobile:** Yes
- **Story:** 
- **Market:** Anyone interested in cooking/meal prepping
- **Habit:**  Depends on user
- **Scope:** 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**
* [x]User can register for an account
* []User can login and logout
* []Get a collection of recipes to add to your cooking and also add your own recipes. 

**Optional Nice-to-have Stories**

* [fill in your required user stories here]
* ...

### 2. Screen Archetypes

* Login
   * Registration - user can either sign in with existing account or sign up

* Main Recipe Page - screen where user can view different recipes
   * user can scroll through different types of recipes 
   
* Recipe Search
   * user can saerch specific recipes 
   
* recipe information
   * [] in detail information about the recipe(ingredients, instructions, etc.)
### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Main Recipe Page (Home Page)
* Recipe Search
* Profile

**Flow Navigation** (Screen to Screen)

* Forced Log-in -> Either register or log in user if no information is available
* Main recipe page -> Upon pressing recipe information page shows up 

## Wireframes
[Add picture of your hand sketched wireframes in this section]
![image](https://user-images.githubusercontent.com/69220191/161365957-80031979-4cee-4c2e-b2d1-541dd9b547f1.png)


### [BONUS] Digital Wireframes & Mockups

<img width="910" alt="Screen Shot 2022-04-02 at 12 08 24 PM" src="https://user-images.githubusercontent.com/69220191/161397765-f2fe7696-ab03-46c6-a77e-3fb093bb2faa.png">

# User Stories (Login)

<img width="250" alt="Screen Shot 2022-04-02 at 12 08 24 PM" src="http://g.recordit.co/Nqr7s0aRhf.gif">

### [BONUS] Interactive Prototype


https://user-images.githubusercontent.com/69220191/161397829-7b711503-3aee-4f17-bf2c-47a1c6055be7.mov


## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
   | Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | objectId      | String   | unique id for the user entry |
   | username      | String   | username for user to login |
   | password      | String   | password for user to login |
   | name        | Pointer to User|  name of the user |
   | image         | File     | image for recipe |
   | recipe        | string   | name of recipe |
   | instruction   | String   | recipe instructions by author |
   | ingredients   | String   | total list of ingredients |

### Networking
- [Add list of network requests by screen ]
- Login Screen / User Profile
    - Validate user with username and password
    - (Read/GET) Display users made recipes
- User Recipes
    - (Create/POST) Create a recipe 
- Home Screen
    - (Read/GET) Get Recipes from api
- Recipe Search
    - Use input param to search api for recipes
   

- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
