# Fortune Teller!

## LEVEL ONE

### Home Page in `home.html`
* Create a heading with your fortune teller name.
* Change the background color of this page.
* Change the text color of this page (you can keep it black if you prefer that)
* Add an image to your page. It can be whatever image you would like here are some suggestions: crystal ball, fortune teller, fortune cookie...
* Add a `<button>` to the page that says "TELL MY FORTUNE!" put an id on this button tag. (you will use the id later)

### Contact Page in contact.html
* Add a background image to the body using the `background-image` CSS property. Look [here](https://css-tricks.com/perfect-full-page-background-image/) for more help. 
  * The website [stocksnap.io](https://stocksnap.io/) has some great free images. Try typing "fortune" into the search bar.
* Add a `<div>` that has some made up contact information
  <!-- TODO add example image -->

### Reviews Page in reviews.html
* Use a `<table>` HTML tag to create a list of reviews 
  <!-- TODO add example image -->

## LEVEL TWO

### Home Page
* Change your background color to be a linear-gradient() <-- google it! instead of one solid color.
* Add a [google font](https://fonts.google.com/) to your page.
  * Click on the red plus sign of the font you want to use
  * Click on the black bar at the bottom of the page that says 1 Family Selected
  * Copy the `<link>` and put it inside the `<head>` tag in your HTML file
  * Follow the font-family instructions for your CSS
* Style your button to look better. Here are some CSS properties you will probably want to use:
  * `background-color`
  * `border-radius`
  * `padding`
  * `color`
  * `border`
  * `box-shadow`


### In `script.js`
* Select the "TEll MY FORTUNE" button using it's `id` and save it as a JavaScript variable. For example:
  * ``` var exampleVariable = $("#example-id") ```
* Call the onClick() jQuery function on your variable
  * Once the user clicks on the button we want to use prompt() to ask the user to pick a number: 1, 2, 3, or 4.
  * Save this prompt as a variable called `number`
  <!-- TODO add example link -->
  * Write and if/else if/ else statement that give the user a fortune
    * **If** variable `number` is equal to 1, `alert()` the user: "You will have a happy life!"
    * **Else if** the number is 2, `alert()` the user: "There is great danger in your future!"
    * **Else if** the number is 3 `alert()` the user: "You will meet your soulmate today!"
    * ** Else if** the number is 4 make up a fortune to  `alert()` the user
    * **Else** this means that they did not type in 1, 2, 3, or 4 to the prompt. You will probably want to `alert()` the user that they did not pick a valid number. But maybe you will want to tell them they have bad luck for 100 years!

## LEVEL THREE

### Home Page
* Make your navigation bar slowly fade in when the page loads. Hint: you will need to use the jQuery fadeIn() function. Google it if you forget how it works.
* Get rid of the underlines on the link tags in your navigation. Google "how to remove underlines from link tags with CSS"

### In `script.js`
* Test out the jQuery `append()` function. Write the code below in your `script.js` to see what the `append()` function does.
  ``` 
    var body = $("body")
    body.append("<h1>THIS IS A TEST</h1>")
  ```
* Change the fortune telling `alert()`s to use `.append()`


## LEVEL FOUR

### Home Page
* Add another button to your `home.html` that also tells fortunes. This fortunte telling button should ask a different question in the `prompt()`

### CREATE!
* Use your creativity to make your website even more awesome!





