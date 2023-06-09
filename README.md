# The Test Suite (exercise) - JavaScript Unit Testing 

Theory: 

Tests are written with code, just like the rest of your web app. You can refer to the code defining your app as implementation code, and the code defining your tests as test code.

A collection of tests for a web application is called a test suite. In the last exercise, you ran a test suite with npm test. In that case the test suite contained all tests for the application.

Test code is included with and structured similarly to implementation code. Often times changes to test code are associated with changes to implementation code and vice versa. Both are easier to maintain when they are stored in the same place.

For example, if implementation code is written in index.js then the corresponding test code may be written in index-test.js.

Exercise Instructions

1.All bugs have been fixed!

Confirm that by running the test suite (this may take some time).
Check your work once you see that all tests pass.

Checkpoint 2 Passed


2.In the test output, find the string starts with a blank order. That string defines part of the “User visits index” feature in the application, so find it in the test/features/user-visits-index-test.js test file.

Around line 9, change starts with a blank order to starts with an empty order in the test file.

Checkpoint 3 Passed

3.Run npm test.

Check your work once you see starts with an empty order in your test output.

Checkpoint 4 Passed


4.That test is interacting with the index webpage, which is controlled by index.handlebars. Add some text to make the order NOT empty.

At the bottom of index.handlebars, around line 122, add your name next to {{order.name}}. It should look like this:

<h2 id="deliver-to">deliver to: <span>My-Name{{order.name}}</span></h2>

Checkpoint 5 Passed

5.Run the test suite. Your change in index.handlebars affected the outcome of tests in features/user-visits-index-test.js! When you make the order NOT empty, the starts with an empty order test fails. (You can scroll up the terminal to see more information.)

Practice exercise from Codecademy Pro. 
