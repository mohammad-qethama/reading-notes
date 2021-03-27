# SMACSS & RWD

in this notes we will take notes on  Responsive Web Design (RWD) and Floats.

## Responsive Web Design (RWD)

Mobile internet usage is very large and still growing even more ,RWD is the response from the industry for this surge in mobile usage.

* RWD is the practice a web page that is suitable for all devises and all screen sizes.
* RWD create natural user experience across devises.
* Responsive and adaptive web design are closely related usually referring to the same practice 'the layout would change depending on viewport'.
* mobile web design refer to a separate domain for the website mobile users.

**RWD is broken down to 3 main components:**

1. Flexible Layouts
2. Media Queries
3. flexible media

### Flexible Layouts

1. flexible grid: using percentage to assign width and relative values like `em` used to maintain layout even when container changes.

### Media Queries

Media queries provide the ability to specify different styles for individual browser and device circumstances.

Example:

HTML.

```HTML5
<link href="styles.css" rel="stylesheet" media="all and (max-width: 1024px)">
```

CSS.

```CSS3
* @media Rule */
@media all and (max-width: 1024px) {...}

/* @import Rule */
@import url(styles.css) all and (max-width: 1024px) {...}
```

Logical operators in media queries help build powerful expressions.(`and` `only` and `not` ).

```CSS3
@media all and (min-width: 800px) and (max-width: 1024px) {...}
```

***

**Mobile First**: using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

## Float

* float is a layout positioning property.
* float is used to wrap text around picture or make picture within the paragraph flow.
* float can be used entire web layout
* floated elements  can collapse there parent element ie 0 height.
* clearing floats can solve its caused proplems
* on of the methods is the empty div clearance method `<div style="clear: both;"></div>`
