# Recipe Sharing - Data-Centric-Milestone-3


## Introduction
This project is developed with the intention for users to share their recipes with others. The main functions of this Recipe Sharing revolves around the 4 functionalities- Create, Read, Update, Delete.

Database was stored and retrieved from the backend (MongoDB).

I chose to do recipe sharing as I enjoy cooking and wish to share my personal recipes with others. Likewise, I am also interested in other people's recipes and I can also try them out on my own.

## Demo


## UX
| User Stories        | Description   |  
| :------------- |:-------------| 
| 1    | As someone who enjoys cooking, I want to share my recipes with like-minded people so that they can whips dishes that they also like.|
| 2    | As a person who does not know much about cooking, I want to have access to various recipes so that I have the steps for recipes that may interest me.|
| 3    | As a general user, I wish that there are such recipe sharing platforms so that I can use them whenever I need. |


The website will be designed based on the identified goals and hence allow users to do the following:

-add new recipes to the website where they can include the cuisines, the recipe name, the ingredients, and the cooking steps.

-edit any recipe on the website.

-view details of the individual recipes

-delete any recipe.

-search recipe by cuisines.


(i) Wireframes


## Project Skeleton - Features

**Existing Features**

-The Recipe Sharing logo on the top left side of the navbar links to the mainpage.

-The Search by Cuisine button allows users to search for recipes by cuisines where it is designed to be case insensitive.

-The All Recipes button allows users to see all the recipes available in the website that has been added by other users.

-The Add Recipe button allows users to add recipe to the website.

-Users can click on the edit button if they want to update or change details of specific recipes.

-Users can click on the delete button if they want to remove a specific recipe from the website.

-Users can click on the view button to see the details of the specific recipe where the ingredients will be returned as an unordered list and the cooking steps will be returned as an ordered list. Users will have to add semicolon after each steps to denote a separation of each step.



The navbar includes a brand-logo on the left, followed by search recipe by cuisine, all recipes, and add recipe, on the right side of the navbar.

The main/landing page shows all the recipes that are in the database where users can edit, delete, and view individual recipes.

The edit button will bring user to the edit recipe page where they can edit the recipe.

The delete button will delete the recipe that is 


**Feature(s) for Future Implementation**

Implement sign in feature for users such that only signed in users can share recipes and only delete their own recipes.

The ability to upload images for individual recipes.


## Testing (Manual)

(i) Mobile Responsiveness

The website has been tested on **Macbook Air/iPad Mini/iPad/iPhone XS/iPhone 6/ Sony Xperia** which covers various screen-size. The browsers used for testings are Google Chrome & Apple Safari.

During the testing process, I found out that:

-On devices such as iPhone X or smaller screen sizes, the brand logo 'Recipe Sharing' overspills to the next line. Hence I added media query such that from screen sizes of iPhone X and below, the font size will decrease.

-Search results will not be shown if I did not type in the exact cuisine name. Hence, the regular expression function has been used to make search function dynamic.

-Ordered list was unable to display properly in the view recipe page. Hence, I used split to solve the problem and the steps is now able to be displayed in an ordered list.



-The website is unable to work on the iPad Mini IOS9.3.5 and iPad IOS9.3.5.

-The website worked on iPhone 6 IOS12.1.2, iPhone XS IOS13.1.3, iPad  6th  generation IOS12.4.1, iPad Pro IOS13.1.3, and Sony Xperia Android 5.1.1 (Chrome).


(ii) Test Cases


## Technologies Used

* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)/[jQuery](https://jquery.com/download/)
* [Python3](https://www.python.org/)
* [Flask](https://pypi.org/project/Flask/)
* [NoSQL-MongoDB](https://www.mongodb.com/)
* [Materialize CSS- 0.100.2](http://archives.materializecss.com/0.100.2/)
* [Google Fonts](https://fonts.google.com/)
* [Heroku](https://www.heroku.com/)

## Deployment


## Credits
pexel

**This is for educational use only.**


