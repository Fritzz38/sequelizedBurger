# sequelizedBurger

Burger 2: The Sequel


Overview

In this assignment, you're going to Sequelize the Burger app you made last week. We've split this exercise into three different tiers, all with different tasks and expectations. Finish whichever tier will provide you with the most reasonable challenge.


Before you Begin


Create a new folder called sequelizedBurger

Copy the contents of your completed assignment from last week.


Remove the older git connection with rm -R .git. 
Then connect this folder with a new github repo.


Run sequelize init to create the necessary files.
Note: If for any reason you don't have a finished assignment for last week, no problem. Message the instructor, who will provide you will a skeleton file to work of for this week.



Instructions

Put in your best efforts to complete one of the three available challenge tiers. Remember to deploy your assignment to Heroku once complete.


Tier 1: Sequelized! (Basic to Moderate)


Remove all references to your vanilla MySQL queries and replace them with Sequelize queries.

That means:


Replacing your MySQL Burger model with a Sequelized equivalent.
Don't forget to edit the model and initial migration file to make the burger's devoured field carry a default value of false -- otherwise you might encounter bugs.


There's no option to include that default in the command line, so you'll need to open up Sublime to make this change. 


Don't forget to sync the models!
Edit your new config.json file to include your database configurations. Place your JawsDB details in the production property of your json file; the details of your local database go in the developer property.
Remove your old ORM file, as well as any references to it in burgers_controller.js. Replace those references with Sequelize's ORM methods.
