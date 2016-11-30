
#About

Recipe sharing site built with Drupal 7 as part of self study following Epicodus curriculum. Pair programmed with LawlietBlack

# Instructions:

1. Download Drupal version 7.51

2. Replace the sites folder with the enclosed sites folder

3. Import the Database Dump

  a. Open phpMyAdmin and click on the "Import" tab.

  b. Leave all the default settings and make sure the character set is "utf-8"

  c. Now click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file we included in our sites/db-backup folder. It's okay to leave it zipped.

  d. Then click the "Go" button on the bottom left.

4. Create the Database User (not needed if using Acquia Dev Desktop)

  a. Lastly, we must recreate the database username/password that Drupal uses to store things in the database. We do this the same way we did when we created the database.

  b. After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".

  c. Use the same username and password from before. (If we have forgotten what that was, we can always find that information in settings.php, or in the PDO Exception error message we saw displayed in the browser.)

  d. After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.


# User Stories:
    As a registered user I can comment on articles
    As a registered user I can share recipes
    As a registered user I can rate recipes
    As a anonymous user I can view recipes
    As a contributor, I can post articles
    As a contributor, I add Infographics
    As a moderator, I can delete comments

# To Do:



Description shorten to 3 -5 lines

Include formatting in help text
  time,
  tags

Take off ability to make url alias for recipes

add servings yield

Look for module to make clipped thumbnail


# Project Requirements:

    *Include basic pages, articles and blocks*
      Cooking Tips (articles)
      Food Recipes (page)
      Drink Recipes (page)
      Infographics (page)
      EC Gallery (page)
      Tips - Home page? (page)
        How to make a roux
        Common Substitutions
        Weight Conversions

    *Include two custom user roles with test accounts*
      Contributor role that can post articles
      Moderator role to moderate content and comments

    *Change the visibility settings on at least one of your blocks so that not all users can see it*
      Allow registered users to see recipe submission guidelines, but don't make it visible to anonymous user

    *Create at least 3 custom content types with a View showcasing each one, either as a page or a block.*
      Recipe Data types using views to showcase
        Food
          Breakfast
          Lunch
          Dinner
          Soups
          Desserts
        Drinks
          Alcoholic
          Coffee
          Tea
          Smoothies

      Infographics
        Pasta types
        Pizza/Beer Pairing
        Cutting Types (find one)
        Cuts of Meat
      Epicurean Creations

    *Work with at least 2 core modules and 4 contrib modules*
      Rating module to rate recipes (contrib)
      measurement (contrib)
      CSS Injector (contrib)
      View Module (contrib)
      Sweaver (contrib)
      Contact (core)


    *Include, enable and configure a theme.*
