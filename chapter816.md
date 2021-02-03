# HTML5 Layout
 HTML 5 introduced a new set of elements that helps the webpage author with describing  the structure of the webpage 
 
 ## `<div>` elements 
 HTML5 replaced most `<div>` elements which was used to group related elements together with another group of tags and some of them are :

 HTML4|HTML5
 ------|-----
 `'<div id-"header">`|`<header>`
 `'<div id-"nav">`|`<nav>`
 `'<div id-"article">`|`<article>`
 `'<div id-"footer">`| `<footer>`




***

### Header and footer 
`<header>` and `<footer>` used in:
 1. the main header and footer of the page
 2. for an individual `<article>`  or `<section>` header and footer

*Example from the book:*
 ```
 <header>
<h1>Yoko's Kitchen</h1>
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
</header>
```
### Navigation 
`<nav>` contains the major navigation blocks and some developer used it in for the links that appear at the bottom of every
page (links to things like privacy policy, terms and conditions
and accessibility information) ***at the time of the book release***.

Example: 
```
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
```
***
More of those tags are described in the  but here i will  mention them  :
* `<aside>`
* `<hgroup>`
* `<section>`
* `<figure> <figcaption>`
* 
## Sectioning elements 
is done by good old `<div>` tag so its still important in HTML5 but it was deployed in another place  
## Linking block-level elments 
Turning an entire block into a linkcan be done by using `<a>` element its not new but wasnt seen as a correct usage before HTML5
## Older browser 
In order to make old browsers understand new tags you need to use the following CSS block of code 
```
header, section, footer, aside, nav, article, figure
{
display: block;}
```
***In order to style these elements
using  versions of IE bellow IE9 , you need to use a simple JavaScript known as the HTML5 shiv or HTML5 shim.***

***
# Extra markup 

## DOCTYPE
`DOCTYPE` tag is used as declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included).

HTML5 declaration tag is `<!DOCTYPE html>`
***
## Comments in HTML 
Comments in the code can be added between those characters `<!-- -->`

Example:`<!-- this where comments go !! -->`

Comments is used for making the code easer to understand enhancing the ability of reading and improving it 
***
## ID attribute 
It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore. 

Example: ``` <p id="unique"> Unique text </p> ```

Tow elements in the page should not hold the same ID value because it will not be unique if that happened. 
***
## **Class** 
Class is a way to mark up several elements that is wanted to be treated the same.

Example: (this paragraph is in the `class` "important")
``` 
<p class="important"> For a one-year period from
November 2010, the Marugame Genichiro-Inokuma
Museum of Contemporary Art (MIMOCA) will host a
cycle of four Hiroshi Sugimoto exhibitions.</p>
```
***
## Other mark up 
 the mark-ups: 
 1. Block element
2. Inline elements 
3. `<div>`
4. `<span>`
    * its like div but for inline texts
5. `<iframe>`
   * can but a frame from other website i.e display it in your page 
6. `<meta>`
   * Used in header to give information about your page

7. Escape character 
   * used to display reserved  characters in html in your page like &#60; and more 

   Example :
     
     Character| Escape character 
     ---------|-------
     &#60;|`&#60;` 
    &copy;|`&copy;`


