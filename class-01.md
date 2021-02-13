# **Structure**

webpages are built like their paper ancestors document so the need to be giving a structure to help the reader navigates through it. 

## HTML 

 Hyper-Text Markup  Language describes the structure of the webpage using **eLements**  which are made up of two tags open tag `<p>` and closing tag `</p>` with content be inside of them 

 + Tags act as a container for certain contents.
 + Tags helps the browser to understand the structure.
 + Good tagging can help the search engine to read your page.
 + open tag syntax is `<` and a word or a letter `header` and `>`: `<header>`
 + closing tag is as same as the open one but with extra character `/` : `</header>`.
+ attributes is added to describe the element a little bit more : ```<p attr='this is a paragraph` lang = `english-uk`> indeed i am one </p>```.
    + Attributes require a name and a value.

## illustration 
```
<head>
<!-- here we but informations about the page  -->

<title> page of a site</title>  <!-- here the title of the page that will appear on the tag written  -->

</head>
<body>

<!-- everything the users see will be here -->
</body>
```

***

# **Extra markup**

## DOCTYPE
`DOCTYPE` tag is used as a declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included).

HTML5 declaration tag is `<!DOCTYPE html>`
***
## Comments in HTML 
Comments in the code can be added between those characters `<!-- -->`

Example:`<!-- this where comments go !! -->`

Comments are used for making the code easier to understand enhancing the ability of reading and improving it 
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
   * used to display reserved  characters in HTML in your page like &#60; and more 

   Example :
     
     Character| Escape character 
     ---------|-------
     &#60;|`&#60;` 
    &copy;|`&copy;`


****


# **HTML5 Layout**
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
`<nav>` contains the major navigation blocks and some developer used them for the links that appear at the bottom of every
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
More of those tags are described in the  but here I will  mention them  :
* `<aside>`
* `<hgroup>`
* `<section>`
* `<figure> <figcaption>`
* 
## Sectioning elements 
is done by the good-old `<div>` tag so its still important in HTML5 but it was deployed in another place  
## Linking block-level elements 
Turning an entire block into a link can be done by using `<a>` element it's not new but wasn't seen as a correct usage before HTML5
## Older browser 
To make old browsers understand new tags, you need to use the following CSS block of code 
```
header, section, footer, aside, nav, article, figure
{
display: block;}
```
***In order to style these elements
using versions of IE below IE9 , you need to use a simple JavaScript known as the HTML5 shiv or HTML5 shim.***

***

# **Process & Design**

## Introduction 
This chapter guide how to process the making of a new website by looking at some information and using tools and techniques to make your website appealing and successful also introducing design theory

***
## who is this site for? 
answering this question needs to understand your target audience and by accruing some information about them like their :
* Age 
* Country
* average income 
* web access device 

and more, all of those should be taking into consideration in this process. 

**book mentioned another set of criteria to be considered for target companies**

 ***
## More process's 
 the book detailed after that the rest of those process as questions and sub-questions I will mention them: 
 1. who is this site for
 1. why they are visiting
 1. what are they trying to achieve 
 1. what info they need 
 1. how often they will visit the website 

***
# Site map 
after accruing all the information above now we can do a site map which is a diagram of pages that will be used to structure the site. 

this can be done **by:**
1. writing each information on a separate page 
2. sorting those pages into groups a technique called **card sorting**

3. Groups will be diagramed into **site map**

### Example : 

***

![Sitemap](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fd2slcw3kip6qmk.cloudfront.net%2Fmarketing%2Fblogs%2Fchart%2Fhow-to-make-a-site-map%2Fsite_map_example2-700x533.PNG&f=1&nofb=1)

***

# Wireframes 

A **wireframe** is a simple sketch of the key information that needs to go on each page of a site
 
 Wireframes are: 
 1. Information forward 
    * No color scheming or images is included in it 
2. It will make the designs easier as it sorting the information on each page 

3. Can be shown to customers before starting the design 

How to make wireframes: 
* Sketching on papers 
* Using illustrator or photoshope 
* Online tools like 
   1. http://gomockingbird.com
    2. http://lovelycharts.com

### Example 


![wireframes](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fexecutionists.com%2Fwp-content%2Fuploads%2F2015%2F10%2Fwireframes.jpg&f=1&nofb=1)

***
# Design 
The primary usage of design is to communicate, helping the user to read the site by organizing and ordering priorities. 

## Deliver your message using design 

 * **Content** 
   * A lot of content is on the page so the designer must prioritize and Organize Them 
   
   * Prioritizing is done by making the user pay more attention to some parts of the page (visual hierarchy)
   * Grouping together related content into blocks or chunks makes the page look simpler

***

 ### Visual hierarchy
   * Size
      * Larger element attract people attention 
* Color
   *Brighter sections tend to draw users' attention first
* Style 
   * Elements Differ in style form its surrounding drags more attention 

***

### Grouping and organizing 
which is simply grouping similar elements in a certain style that the author states on the page (469)

### Designing navigation 
To help people understand and move to your site.

Good navigation tends to follow these principles: 

1. Concise 
    * limiting showed element to make the website easier to read. 
2. Clear 
    * Choosing one descriptive word for your link. 

3. Selective 
   * Hide sections like "terms and conditions' and login elsewhere on the page.  


