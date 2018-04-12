# 4xx

https://4xx.andilyn80.com

inside out project version 400.0
-added base code to index.html and added initial JaveScript to app.js 

inside out project version 401.0
-created the appData object, moved the title & tag line varibles into appData, and refactor the initilizeApplication function

inside our project 402-1
- added style.css and linked in index.html
-added login form form function and call after progress bar is completed
-added minimal validateLogin function to check for blank strings. 

inside out project 403-0
-index.html
	-updated all hrfs/links passive protocol
	-moved style sheet link below animated and bootstrap to allow custome styles to override all
-style.css
	-added style for application interface - sidebar, wrapper, navigation, etc.
-app.js
	-added the applicationUserInterface function which defines the application user interface.
	-added the buildMenu fuction with return the navigation menu and will increase in dynamic navigation building
	-added the buildMain fu nction which returns the primary content area and will evolve to retuen content dynamically.
	-replaced document write with call to applicationInterface function in the validateLogin function
	-added the linkedClick function which is click event on anchor element and return dynamically driven results. 
	
inside out project version 404.0

-index.html
	-code changes https://www.diffchecker.com/oybNnzTY
	-removed comments and cleaned code
	-added script tag for quotes.js file
-style.css
	-code changes https://www.diffchecker.com/114fW8QY
	-modified the sidebar and sidebar ul classes
	-added the auth and infoDiv classes
-app.js
	-code changes https://www.diffchecker.com/oKMHtB1u
	-added the quotArr sort to the initializeApplication function
	-modified buildMenu function to dynamically build the menu from the array
	-modified linkClicked function to dynamically populate main content with array content
-added the assets/data/quotes.js file
	-code changes https://www.diffchecker.com/YlRCv0UM