## Flask Application Design for Teaching Beginner Marathi

### HTML Files

- **index.html:**
   - This is the main page that displays the form to enter Marathi words and get their English translations.
   - It should contain an input field for entering Marathi words, a submit button, and a div to display the English translation.

- **translation.html:**
   - This page displays the English translation of the Marathi word entered by the user.
   - It should have a div to display the translated word and a link to return to the main page.

### Routes

- **route /:**
   - This route handles the GET request for the main page (index.html).

- **route /translate:**
   - This route handles the POST request submitted from the main page.
   - It extracts the Marathi word from the request, translates it using a translation API, and redirects to the translation.html page with the English translation.