# Class-04

## Links

Links allows the movement from webpage to another.

### Writing Links

links created by using the `<a>` anchor element.

```HTML
<a  href='http://www.google.com'>google.com</a>

```

* Link text is the text between `<a>` and `</a>` tags.

* `'http://www.google.com'` this called absolute URL.

* Relative URL used to link different pages within the same domain.

```HTML
<a href ='index.html'>Home</a>
```

* Link an email and start the user mail program and but the email address in it by using `'mailto'`.

```HTML

<a href='mailto:jonDoe@gmail.com'>Email JonDoe</a>

```

* `target=_blank` used to open the URL in new window(not recommended).

```HTML
<a href='https://almohaweron.com/' target='_blank'>almohaweron</a>
```

* Id can be used to link elements from the same page.

```HTML
<a href='#title'>Title</a>
```

* you can also link a specific part of another page using its URL/#id.

```HTML
<a href='http://www.amazon.com#dicsounts'>Discounts</a>
```

***

## Layouts

with CSS Control how the element sits on the page and create attractive layout.

* Containing element : an element that contains smaller element inside of its box the **Direct Parent**.

CSS has the following positioning scheme:

* Normal flow

* Relative positioning `position:relative;`
  * it moves the element  in relation to where its *normally flow*
  
  ```CSS
  main p {
    position:relative; 
    top:10px;
    left:20px;

  }
  ```

* Absolute positioning `position:absolute;`
  * the element can now be moved without considriong its normal flow , like there is no other boxes in the page.

```CSS
main img {
position:absolute;
top:180px;
left: 420px;
width:100px;
} 

```

* fixed positioning `position:fixed;`
  * postions the element in relation with browser window , so when you scroll down it will stay in its place.
  
* `z-index` added depth to the elements, ie moves it along z axis.

***

## Functions

a grouped commands that do certain task.

### Notes on functions

* Functions helps to make your code organized and easier to read also they are reusable for the same code.

  * Functions are called within the code when ever they needed ""`functionname();`"" i.e provoking the function.

* Some function needs a Parameter which is a piece of information the function use.
* Function answer you with a return value i.e its result.

 ***define a  simple function syntax is:***

 ```JS
  function functionname(){

// place code to be executed
    
 } 
 functionname();
```

***

 ***define a function that needs information syntax is:***

 ```JS

 function funcName(Value1,Value2, Value3){
return Value1 * Value2 % Value3
    
 } 
 functioName(123, 34,5); // Calling it

 ```

* `Value1` called Parameter.

* `(123,34,5)` called an arguments.

***

## Pair programming

programming with pair of people working on the same code.

* Driver is the one who writing the code and handle all technical requirements to do so.

* Navigator is the one who use words to guide the driver('Persona  initial thought'; looks like glorified back-seating and i already hated it ).

reasons to utilize pair programming :

1. higher quality products, overall higher efficiency.

1. provokes higher concentration levels and for longer spans.

1. provides Learning opportunity from colleagues.

1. Forcing people to develop and practice their communication skills.

1. A skill that employers looks for.

1. its actually a work environment that you will learn to overcome.
