# Class-09

## Forms(HTML)

Forms allows user's to write inputs and submit data to the webpage server most know one is google search form.

### Forms control

1. Adding text
   + text input,like user name small usually
   + password input, authentication factor input

   + Text area,for large texts

2. Making choices
   + radio buttons , chose one option out of all options
   + check boxes, chose many out of all
   + drop-down boxes

3. Submitting forms
   + submit button , like (subscribe)
   + image button
   + file upload

### Form HTML structure

```HTML
<form action="http://www.example.com/subscribe.php"
method="get">
<p>This is where the form controls will appear.
</p>
</form>

```

1. `action` attr contains url of the server/ server function.

2. `method` determine how the form will be send ,its values either `'get'` or `'post'` post is the one uses HTTP.

***

```HTML
<form action="http://www.example.com/login.php">
<p>Username:
<input type="text" name="username" size="15"
maxlength="30" />
</p>
</form>

```

+ `input` self closing tag  used to construct a box to take text in it

+ `'name'` atrr used to tell the user what is this text that will be send to it , its like a header info.


