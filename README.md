# Cookify
Personal project

# Aim
I want to create a recipe tool, that catalogs online recipes in a simple, personalised way, similar to saving songs to a custom playlist on spotify. Users should be able to share a chosen website link to Cookify, which can be imported and added straight into the app.
<br/>
# Tech Specs
* mobile-first design
<br>
# MVP
* As a user I'd see just the logo upon loading the app
<br>
### 1. HOME
* As a user I'd see the home page, which would have:
  * navigator bar which displays the logo, an add button(this adds a new recipe) and settings button(see Stretch)
  * A greeting (see Stretch)
  * A top section displaying thumbnails of recipe folders (see Stretch)
  * A bottom section displaying 'recently viewed' recipes, this will be a carousel that doesn't loop.
  * A dashboard on the bottom which displays 3 buttons: Home, Search(see Stretch), and Your Cookbook
 <br> 
### 2. ADD RECIPE
 * As a user I'd like to use the add button on the home page. This would take the user to a new page called 'Add recipe' which would see:
  * A navigator bar which displays a back arrow to go back to home page, the page header and a 'SAVE' button
  * A 'Title' text field to name the recipe
  * A 'Folder' drop-down menu which allows the user to select which recipe folder to save the recipe to
  * A 'Source' text field to paste in a web address the recipe originated from
  * The same dashboard on the bottom which displays 3 buttons: Home, Search(see Stretch), and Your Cookbook
 - - - - - - - - - - -
 *METHOD ONE - ADD A RECIPE:
 * User finds recipe on their internet browser and either selects the share icon which appears when tapping the url bar(chrome) or selecting the 'share' button in the menu. This brings up a window titled 'Share via' and you can select the app which will import the web address directly into the app. 
- - - - - - - - - - - 
 *METHOD TWO - ADD A RECIPE:
 * This method only works if the 'FIND RECIPE' tab is implemented(see Stretch). When the user searches a recipe/ingredient in the search bar, and the google results appear, when a user selects a link it will automatically import the recipe details. In this case it will import the url into the 'Source' input and the title into the 'Title' input.
- - - - - - - - - - -
* As a user, once all neccessary details have been added into the form, user can press 'SAVE' in the navigator and the user will be brought back to the home page.
<br>
### 3. YOUR COOKBOOK
* As a user I'd like to be able to select 'Your Cookbook' from the dashboard, and that would take the user to another page where the user would see:
    * the same navigator bar which displays the logo, an add button(this adds a new recipe) and settings button(see Stretch)
    * Two tabs(see Stretch), first one says 'Folders' which when selected, displays a '+ Create folder' button. 
    * The same dashboard on the bottom which displays 3 buttons: Home, Search(see Stretch), and Your Cookbook
- - - - - - - - - - -
*CREATING A NEW RECIPE FOLDER
* As a user I'd like to be able to select '+ Create folder' button which would take you to another page called 'Create folder' which the user would see:
  * A navigator bar which displays a back arrow to go back to YOUR COOKBOOK page, the page header and a 'SAVE' button
  * A 'Folder name' text field to name the recipe folder
  * An 'Add recipes' drop down menu which displays recipes in a checklist and allows the user to select which recipes to add to the recipe folder.
  * The same dashboard on the bottom which displays 3 buttons: Home, Search(see Stretch), and Your Cookbook
- - - - - - - - - - -
* As a user, once all neccessary details have been added, user can press 'SAVE' in the navigator and the user will be brought back to the 'YOUR COOKBOOK' page.
- - - - - - - - - - -
*NAVIGATING A RECIPE FOLDER
* Once the user has created at least one folder, this should now display as a thumbnail in the 'Folders' tab. Now the user can select the folder which would take the user to another page which the user should see:
  * the same navigator bar which displays the logo, an edit button(this edits the recipe folder) and a delete button(this deletes recipe folder)
   // IF EDIT SELECTED: If the user selects the edit button, this redirects the user to the 'Create folder' form (with the name and add recipe inputs). Once the changes have been made the user can select 'SAVE' and that will redirect back to the selected Recipe Folder.
   - - - - - - - - - - -
  // IF DELETE SELECTED: This deletes the recipe folder(see Stretch)
- - - - - - - - - - -
  * a list of recipes displayed in rows. Each row would have an image thumbnail and the recipe title next to it. When the user selects a row the app will navigate externally to the recipe source url (basically the button opens up a new internet browser tab).
  * if the user 'holds' a recipe, this will make two buttons appear - an edit icon, and a delete icon. 
  // IF EDIT SELECTED: If the user selects the edit button, this redirects the user to the 'ADD A RECIPE' form (with the Title, Source and Folder inputs). Once the changes have been made the user can select 'SAVE' and that will redirect back to the selected Recipe Folder.
  - - - - - - - - - - -
  // IF DELETE SELECTED: This deletes the recipe row(see Stretch)
<br>

# Stretch
1. HOME PAGE
* As a user, upon the first time using the app, I'd see a pop-up which is a quick tutorial on how to use the app. This would be a carousel with at least 2 slides. At the end of the carousel there would be 'get started' button.
* Navigator bar would have a settings button which contains a dropdown menu of all sorts
* Greeting on home page to be customised to whatever the time was on that user's device e.g. if it's before noon, greeting would say 'good morning' and before midnight it would say 'good evening'. Or maybe greeting can be customised in the settings by the user e.g. 'waddup foodie!'
* Top section on Home page would always display the recipe folders that are 'most used' by the user
* Search feature in the dashboard which allows user to search through their database of recipes based on an ingredient.

2. ADD RECIPE
* A 'FIND RECIPE' tab which contains a browser inside the window below. There is a search bar at the top which acts the same as a google search bar. 
* A 'Notes' text field for whatever reason e.g. 'swap butter for coconut oil'
* A 'PHOTOS' tab which allows you to select a button called '+ ADD PHOTO' and that has a drop down menu of 2 options: take photo or choose photo from gallery. You can also see thumbnails of all photos on display for that recipe. You can also hold down a thumbnail which would give a 'delete' option. 

3. YOUR COOKBOOK
* The second tab says 'A-Z' which displays all recipes that have been saved in the app in alphabetical order.
* For each recipe row or recipe folder, when the delete icon is selected, there should be a pop-up asking if the user is sure they want to delete the recipe.
* When the edit icon has been selected on a recipe row, the user is able to drag rows around to reorder the recipes.
