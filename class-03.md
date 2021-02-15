
# Lists

to mention or organize a group of things lists was always the way to go, so it used in HTML.

Here are the types that are provided from HTML:

## Ordered lists

list items here are numbered. it can be used to force particular order for a certain procedure.

The ordered list is created with the `<ol>` element ,each list element is placed between `<i></i>` tag.

EX:

```HTML


 <ol>
                <li>water</li>
                <li>steam</li>
            
                <li>cloud</li>
                <li>rain</li>
                <li>water</li>


            </ol>


```

## Unordered lists

list element begins with a bullet

the unordered list is defined with `<ul>` tag,each list element is placed between `<i></i>` tag.

Ex:

```HTML
<ul>

<li>eggs</li>
<li>flour</li>
<li>mlik</li>
</ul>
```

## Definition lists

set of terms with their definition.

the definition list is created with `<dl>` element.

* `<dt>` to conatin the term being defined (t = term).
* `<dd>` to conatin the term  defintion (d= defintion).

Ex:

```HTML
<dl>
    <dt>transistor</dt>
    <dd> semiconductor device that used as an electrical switch also it can amplify singles . </dd>
</dl>
```

## Nested list

another list inside one of the elements of the list

EX:

```HTML
<ul>
    <li>Mousses</li>
    <li>Pastries
        <ul>
            <li>Croissant</li>
            <li>Mille-feuille</li>
            <li>Palmier</li>
            <li>Profiterole</li>
        </ul>
    </li>
    <li>Tarts</li>
</ul>
```

***

# Boxes

CSS sees each HTML element inside a box, here we will deal with those boxes and see how they can be used to style the page

## Box Dimensions

you can adjust the box dimension using `width` and `height` properties.
CSS EX:

```CSS

.logo{
width:100px; 
height:100px; 


}

```

The most popular value to set those parameters was px as it allows precision, but the percentages and ems took their place as the websites have now been accessed from different devices.  

***

### Minimum and maximum width and height

 you can set minimum and maximum values for both width and height using :

 ```CSS

min-width: 450px;
max-width: 650px;
min-height: 10px;
max-height: 30px;
 
```

as they prevent pages to shrink stretch beyond those values which helps the page elements to stay eligible.

* if the content does not fit in the minimum values it will look very messy you can use the `overflow` property along with `min-X` to prevent that.

***

### Overflowing Content  

if the content of an element is larger than its box the `overflow` tells the browser how to handle that problem.

`overflow` has two values :

* `hidden` which hides the extra content.

* `scroll` add scrollbar so the user can scroll to see missing content.

## Border, Margin, and Padding

Each box has those three variable properties that control its appearance.

### Border

Every box has a border but they are invisible.

`border` value can be determined py pixels or the values:

1. `thick`

2. `thin`

3. `medium`

***

```css

border-top-width
border-right-width
border-bottom-width
border-left-width

```

* can be used to control each border side spritely or:

```css

border-width: 2px 1px 1px
2px;
```

* The values here appear in
clockwise order: top, right,
bottom left.

* border can be styled using `border-style` property.

* border colors can be changed through `border-color`.

* you can use the shorthand property `border` to specify all three previous ones.

```css
  
    p {
    width: 250px;
    border: 3px dotted #0088dd;}  

 ```

***

## Padding

the space between an element and its border can be determined by using the `padding` value determined by pixels.

***

## Margin

`margin` property is used to determine space between boxes.

if two boxes are on top of each other the larger margins of the two will be used.

***

## Change Inline/Block

`display` property let you change element from inline to box level and vice versa.

***

# Switch statements

```js
switch(fruits) {
  case "Banana":
    text = "Banana is good!";
    break;
  case "Orange":
    text = "I am not a fan of orange.";
    break;
  case "Apple":
    text = "How you like them apples?";
    break;
  default:
    text = "I have never heard of that fruit...";
} 

```

> code from [W3school.com](https://www.w3schools.com/jsref/jsref_switch.asp) .

* `switch` star with a variable called switch value.

* `cases` are conditions if the value in the case `==` the switch value then the line beneath it will execute

* `break` will end the execution of the switch statement.

* if the switch value does not equate to any of the cases the `default` statement will be executed.

## Rest of the chapter notes

* JS can convert the data types behind the scenes to complete an operation i.e type coercion.

* JS uses weak typing as the data type for a value can change.

* Type coercion can return unexpected results.

* `NaN` value generated when a number is expected but is not returned.

* values can be falsy or truthy values

  * if you equate `false`, `0` and `''` result will be `true` boolean value but if you use strict equate its result will be a `false` boolean value.

  * `null` and `undefined` are not equal to anything but themselves.
  
  * `NaN == NaN` will return false its.(like the improper values in calculas and limits undifined values)
  
  * A unary operator returns a result with just one operand

# Loops

 a piece of code that will run  repeatedly until a certain condition became false

## For loops

 its a loop that repeat for a specific number of times (counter conditioned )
Syntax:

``` for (var i = 0  ; i > 5 : i++) ```
  
* `var i = 0`

  * assignment for an initial condition it will be executed one time.

* `i > 5`

  * the condition, loops keep running as long as it returns true.
  
  * update statement, changes the value of the counter i.

## While loops

the condition here is a purely logical one it can be counter or anything else that produces true or false.

### Syntax

```JS
 While (A != 'A'){
 doc.write(A) 
} 
```

* `do while()` used to execute the code once even if its initial value was `false`.

* `break` statement can be used conditionally to prevent infinite loops.
