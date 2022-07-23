# Let's build a quoteboard!

Today, we are building a web app that stores and displays quotes that a user inputs.

In our project folder, we have a **'static' folder** where you can add **css files**, and a **'templates' folder** where you'll find all of our **templates (html files)** that we are/will be using.

In today's lab, you'll only work with and edit one main Python file and 2 templates: **home.html and display.html**. Flask session has already been imported in the main Python file.

### First things first, _fork_ this repo(sitory) and _clone_ it to your desktop!

## Part 1: Home

1. Add a form to `home.html`! Take in a quote, the quote's author, and the author's age.

2. When the form is submitted, store the form's information in `login_session`, example: `login_session['age'] = age`.

3. Display `thanks.html` if the form's information is successfully submitted and stored.

4. Use **try and except** to handle errors with storing the form responses in the login session. If there is an error, users should be redirected to `error.html`.

## Part 2: Display Page

1. Fill in `display.html` with a template to display a quote, author, and age.

2. Pass information from `login_session` to `display.html`.

3. Check to make sure the display page will now correctly display the quote that a user enters.

### Bonus:

-   Add a button to the display page to take in additional quotes
-   Modify the `display.html` template to loop through a list of submitted quotes and display all of them.
-   Use CSS to make your quoteboard look like an actual whiteboard!
