Task 1: To create a list using the groupList image and json below


Each group has in the header:
Name (with warning icon if present warning field)
Menu button (visible on hover)
Users list
Warning message
Services list (field functions)
Each item has title/min/max values 

You can use some random icon from the net

Sort lists ascending



Actions 1st page:

Button Nuovo Gruppo – open second page, enable everything, empty fields
Card Click – open second page, everything disabled, (only footer buttons enabled)
Modify button (from popup) – open second page, everything enabled (in footer Save instead of Modify)
Button Elimina (from popup) – remove item from list


Actions 2nd page:

Modify button, enabled everything, replace "Modifica" button with "Salva"/"Save"
Go back to the list
For selected services, if the minimum/maximum threshold value is different from the minimum/maximum service threshold value, a warning icon and warning color appear in the text.
groupList.json (click to open the file)
groupList= [
  {
    functions: [
      {
        title: "MAV",
        functionCode: "MAV-SLIP",
        minValue: "1",
        maxValue: "500"
      },
...

Task 2: Implement an application that can show the following pages:

/ - main page 
/login - login and password entry page
/news - news page (any information of the same type)
/profile - a free-text page that is not accessible without authorization 
On the site, in the header or footer to implement links:

Back to main page (/) 
News (/news) 
Profile (/profile) 
 

If the user clicks on the "profile" page and he is not "authorized" - throw to the /login page
The login form (/login) accepts "fake" data:
username: Admin 
password: 12345  

 

If other data is entered, the following messages are displayed:
Username or password entered incorrectly 

If the correct data is entered, then throw to the page /profile
User authorization information can be stored in localStorage, with a simple true/false parameter. You do not need to implement a database.
A request for news, an attempt to log in and all that you see fit.
Design - it does not matter. Make it so that you can comfortably watch the example in the browser.
About the app

basic functionality has been completed
TypeScript and Angular used
typography
 

Resources:
1) https://www.typescriptlang.org/docs/handbook/angular.html
2) https://angular.io/start
