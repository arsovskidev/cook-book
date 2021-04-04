# Cook Book

#### _Task 1_ ✅

```
Using the cookbook.js file:
Use the createCard method to draw all recipes on screen.
Hint: it’s simplest to iterate over all recipes and invoke createCard for each of them.
```

#### _Task 2_ ❌

```
Create a “Router”
Create logic into handleRoute function
If the hash is empty, render the “home” screen
(cardContainerelement, use display = ‘flex’, otherwise display=‘none’)
Besure that reloading the page should keep the
last shown container visible
```

#### _Task 3_ ❌

```
Clicking on the “Open Recipe” button should show recipe details
Extend the router, hide the cardContainer and show fullRecipeContainer
section Invoke the renderRecipe function
```

#### _Task 4_ ❌

```
The tags in the recipe list aren’t currently clickable - let’s fix that 😊
Add a ‘click’ event listener to every tag element (see comments), which
simply logs the tag text;
Let’s first filter the data we need - filter the recipeData variable
```

#### _Task 5_ ❌

```
Extend router functionality
On click on tag hash should change to #tag-tagname,
handle this in router, hide cardContainer and fullRecipeContainer,
but set tagContainer to display = “flex”.
Filtered data from the previous step should now
be displayed into tagContainer
Use createCard function for each of the filtered recipes
```

#### _Task 6_ ❌

```
Add a click event listener on the logo (header element), that should bring us on the homepage (empty hash).
```

#### _Task 7_ ❌

```
On the homepage under “What are we cooking today?” add a simple search form with search button.

Clicking on the button should set new hash ‘#search-SEARCHED-VALUE’
FilterrecipeData only by the name.

Filtered data should be displayed in new container
(Feel free to add new section).
```
