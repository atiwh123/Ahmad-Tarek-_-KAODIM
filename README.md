# Ahmad-Tarek-_-KAODIM
Submission of KAODIM Software engineering intern assignment  

This is my submision of the Software engineering intern assignment. There are Some points that i have to point out, I used XAMPP and php to create most of the important part of the assignment.

Architechture: 
To create the pages i used HTML, CSS and JavaScript. To create the forms, the data is exctracted from the JSON array ,create Objects to hold the data which i then printed as a HTML string programatically to create the forms at rune time, each question has an index which specifed which question to view.

Value transfare:
To pass values from one page to another, i used POST and SESSIONS, when the form is first sumbited POST variables are created , which are then assigned to SESSION variables throught a redirecting page. SESSION variables are then used to construct the rest of the assignment.

Calculations:
With each input value submited, a hidden input is also submitted which containes the value of the chosen choice and another input for the price, the values where passed using the same methode mentioned above and calculated at the final page to view the result.
