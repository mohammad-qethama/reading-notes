# Texts 
## Markup
Adding tags in the webpages called markup 

Types of markup : 
* Structural markup
    * elemnets to describe both heading and paragraphs. `<p></p>`.

* Semantic markup 
   * provides extra information ` <body></body>`.

# Structural markup

## Headings 

Headings tags '`<h1></h1>`' are used to markup certain text to be declared as header as it increases its font size. 

heading tags goes from `<h1></h1>` to `<h6></h6>` where h1 has the largest font and h6 has the smallest. 



## Paragraphs 
Paragraph tag `<p> </p>` can hold text between its open and closing tags. 

## Bold & italic 

bold tag used `<b></b>`  to make any thing between the tag <b> bold </b>

italic tag used `<i></i>`  to make any thing between the tag <i> italic</i> 



Example:


```

<p> On the other hand, we <b>denounce </b> with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through <i>weakness of will</i>. </p>




```

## subscribt 
`<sub></sub>` and `<sup></sup>` used to subscript text between tag. 

Examples:
1. E= MC<sup>2</sup> |`MC<sup>2</sup>`
1. water chemichal formula is H<sub>2</sub>O | `H<sub>2</sub>O`

## Line breaks & horizontal rules
* Line break `<br />` is a self-closing tag (does not need a closing tag ) that breaks the line and start a new one when placed inside a piece of text (ex.paragraphs). 
 * horizontal rule`<hr/>` used to add a visual line to break pages parts. 

*** 
# Semantic markup
 ## Qutation 
 * `<blockquote> </blockquote>` element used to quote a large text 
 * `<q></q>` used for shorter quotes 

*** 

## Abbreviations & Acronyms
![bookSC](/assets/a&a.PNG)
> HTML AND CSS , Duckket; Page(53)

# ***The rest of symnatic tag better described in the book chapter 2 no need to but him here nothing will be simplified***






 ***
 <hr/>

# Introduicng CSS 
Cascade Styling Sheet used to add styles to my HTML page

* CSS treats each HTML element as if it appears in a box 

* CSS uses Selectors to target certain HTML elements and Declaration which in it the changes to be applied.  

```
p {
    color:red;
}
```
1. `p` is the **Selector** 
1. `color` is the **Property** 
1. `red` is the property color **Value**

CSS can be used by: 
1. External CSS 
     * linking an external .CSS file 
 
    ```
        <head>
            <title>Using External CSS</title>
            <link href="css/styles.css" type="text/css"
            rel="stylesheet" />
        </head>

    ```

2. Internal CSS 
   * Using style tag `<style></style>` 
   ```
    <style>
    .data {
        color: red ;
        text-size: 20 px; 

    }
    
    
    </style>

   ```
***
## CSS rules Cascading 

1. Last rule 
   * the last rule will be executed if two rule came for the same element 
2. Specificity 
   * more specific selector rules will be executed `h1` is more specific than ` * `

3. Important 
   * `!important` can be added after the propirty to give it more wight of excution than other ones.  
      * ` p b {
color: blue !important;}`

3. Inheritance 
   * property will be applied on all child elements 





***
# JS basic instructions 

## Variables 

* a name that be giving for a reserved location of memory 'cash memmory i guess ' to store some bit of information in it 

* it will be deleated once the user leaves the page or reload it 
* variable value can be changed with the execution of the script 
* syntax to declare variabels is `var varname = 'varvalue'; `
    * `var ` is the recived order to start the decleration of the variable 
    * `varname` is an example of the variable name you can name it any thing as long as it start with aletter a $ or _ `_sun `
        * variables name better or almost must have a meaningfull name
    * `'varvalue'` is the intial value for this variable and its a **string**.

### Data types 

1. Numric `0.785`
2. Strings `'this is democracy manifest'`
3. boolean `true`

## Arrays 
Arrays is a special type of varaiables that can store multible(a list of ) values.

syntax `var array1 = ['element1','element2', 'element3']`

Each array element are numred from 0 to X (an index )and can be called alone by it 
index|value 
-----|----
0|'element1'
1|'element2'
2|'element3'


**console** example:


```
 > array1[2]
   element3
 >
```
## Expressions 

Expression is a line of code that evaluates into single value. 
## Operators 

it can process multiple values into single one so **Expressions** rely on it.

types of operators and examples : 
 * Assignment opretors 
    * `var car = 'Toyota' `
* Arithmetic operators 
   * `var days = 30*12`
* String opretors 
  * concatenate  : ` var fullname = 'Mohammad ' + 'Quthama' ` 




***

# Decisions and Loops

## Loops


### comparison operators 
an operators used to compare between two -or more- variables , values , expressions, and it will produce a boolean as result. 

#### some comparison operators: 

Operator symbol| Name | output of an example 
----------|------------------|------------
`==`|Equal to | `hello == hi ` returns `false`
`!=`|Not equal to | `hello != hi` returns `true`
`===` | Strict equal to| `3 === '3'` returns `false` 
`!==` | Strict not equal to | `3 !== '3'` returns `false` 
`>`| Greater than| `4 > 2` returns `true`
`<`| Less than | `4 < 2` returns ` false`
`>=` | Greater than or Equal | `5 >=5` returns `true`
`<=`|Less than or equal| `5 <= 6` returns `false`

## Logical operators 

operator used to process boolean values , results , variables 

##  The Logical operators
* `&&` logical and 
   * Both of the conditions are tested 
   * if both of them are true it returns true other false 
* `||` Logical or 
   * one condition is tested 
   * if one of them is true then it will returns true 
* `!` Not 
    * inverts its boolean input 
    * !true = false , !false = true 

## Loops 
 a piece of code that will run  repeatedly until a certain condition became false 
 ### For loops 
 its a loop that repeat for a specific number of times (counter conditioned)

Syntax:

``` for (var i = 0  ; i > 5 : i++) ```

 * `var i = 0` 
    * assignment for an initial condition it will be executed one time. 

* ` i > 5` 
   * the condition , loops keep running as long as it returns true. 
   * `i++` 
      * update statement , changes the value of the counter i. 

### While loops 
the condtion here is pure logical one it can be counter or anything else that produce true or false. 

Syntax :  

```
 While (A != 'A'){
 doc.write(A) 
} 
```

