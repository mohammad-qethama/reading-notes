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

+ `'maxlength'` attr used to limit the input to a maximum value,  '`30` in this example'.

***

## forms tables and lists (CSS)

there are many way to style alot of HTML element on CSS here are some for the `forms` `tables` and `list` elemnts .

### lists

+ lists '`<ul></ul>`and `<ol></ol>`' elements `<li>` bullets can be changed to style them by `list-style-type: /*place value*/;` or by images using `list-style-img:*/URL here/*`.

+ you can position lists bullets/marker using `list-style-position: ;`; two options are valid : outside and inside.

+ `list-style:` is short hand to all of the above.

### Tables

+ table can uses `width`, `padding`,`font-size`, properties and more.

+ `empty cell:` property can be used to style empty cells border in your table,values `show`,`hide`,and `inherit`.

+ `border-spacing, border-collapse` used to determine spaces between cell.

### Forms 

+ Text in forms can be styled like normal text so text propirtes can be used . 

***

## Events (JS)


