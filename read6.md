# Java script example
this code in add-content.js


1. var today= new Date();
2. var hourNow = today.getHours();
3. var greeting;
4. if (hourNow > 18) {
5. greeting= 'Good evening!';}
6. else if (hourNow > 12) {
7. greeting = ' Good afternoon!';}
8. else if (hourNow > 0) {
8. greeting = 'Good morni ng!';}
10. else {
11. greeting = 'Welcome! ' ;}
12. document .write('< h3>'+greeting +'</ h3>');

+ var to declare a variable.
+ today :a variable name
+ new Date() :creates a new date object with the current date and time
+ if statement :

1. Use if to specify a block of code to be executed, if a specified condition is true
2. Use else to specify a block of code to be executed, if the same condition is false
3. Use else if to specify a new condition to test, if the first condition is false

+ if (condition){/
+ /}
+ document .write() :Write some text directly to the HTML document


