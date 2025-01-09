# JS-Chapter9
JavaScript Chapter 9 Programming Assignment

In this project you will work on a web page in which customers attach greeting messages to gifts purchased for friends and family. The contents of the greeting message will be entered on one web page form and then displayed as part of a shopping cart on a separate page. Data will be transferred from one page to the next by appending data to a query string. A preview of the shopping cart page with a sample gift card message is shown in Figure 9-22.

![image](https://github.com/user-attachments/assets/b67ef040-d9ac-49ca-92fe-eacd421cec38)

Figure 9-22

Do the following:

Use your code editor to open the index.html, indexb.html, and script.js files. Enter your name and the date in the comment section of each file and commit.

Go to the index.html file in your code editor. Edit the form element so that submitting the form opens the indexb.html file using the get method. Close the file, commiting your changes.

Go to the indexb.html file in your code editor and add a script element linked to the script.js file. Defer the loading of the script until the page finishes loading. Take some time to study the contents of the HTML file and then close the file, saving your changes.

Go to the script.js file in your code editor. Apply the slice() method to the location.search object, storing the text after the first character in the query variable.

Use the replace() method to replace very occurrence of the + character in the query variable with a blank space. Apply the decodeURIComponent() method to replace every URI-encoded character in query with the matching character.

Appy the split() method to the query string to split the text at every occurrence of the & character, placing each name=value pair as a separate item in the cardFields array.

Create a for of loop that loops through every item in the cardFields array. At each iteration of the loop do the following:

Split each item at the location of the = character, store the substrings in the nameValue array variable.

Store the first item in the nameValue array in the name variable. Store the second item in the nameValue array in the value variable.

Store the value of the value variable as the text content of the document element with an id equal to the name variable.

Commit your changes to the file and then load index.html in your web browser. Enter sample greeting text in the field of the web form and then click the Submit button. Verify that the browser opens the indexb.html file with the text of the greeting message displayed in the page.
