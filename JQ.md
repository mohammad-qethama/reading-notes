# JQuery

JQuery offers simpler way to achieve some JS function:

* Select element `$('#mainForm')`.
* Preform tasks `$('#mainForm').html();`.
* Handle event `$(#img).click((add) => {return add+2})`.

JQuery is a JS file that you include in your webpages that makes you use CSS-Selector and add functions to use on them.

```HTML
<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
```

> JQuery CDN usage example

* Some JQuery methods can read or set values `.text()`.
* method changes on values through JQuery applied to all selected element no need for loops like JS.
* you can chain multiple methods on the same time using `.`

```JS
$( 'l i [i d!="one"] ').hide().delay(SOO).fadeln(1400);
```

more compact form and much easier way to achive multiple jobs.

* `$(function(){})` is a shortcut to check the readiness of the webpage (if document.ready is accrued ).

* `$('main').css({'color':'red'})` used to set css property of the selected element(s).
* `.each()` and `$(this)` or `this` used to loop and preform functionality on each elements that the selector refer to.

* if you place the script at the end of the page before the closing `</body>` tag, it will not affect the rendering of the rest of the page.

***

## Pair programming

programming with pair of people working on the same code.

* Driver is the one who writing the code and handle all technical requirements to do so.

* Navigator is the one who use words to guide the driver

reasons to utilize pair programming :

1. higher quality products, overall higher efficiency.

1. provokes higher concentration levels and for longer spans.

1. provides Learning opportunity from colleagues.

1. Forcing people to develop and practice their communication skills.

1. A skill that employers looks for.

1. its actually a work environment that you will learn to overcome.
