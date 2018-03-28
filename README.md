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