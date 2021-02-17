# class-05

## Images

there are many reason makes adding images to the website an appealing thing to do here we will learn how.

* `<img />` self closing tag used to add images to the html  page structure and its a self closing tag.

* img tag will be rendered differently depending on where you place it.

```HTML
 <img src="img_joker.jpg" alt="batman's Joker" width ='200' hight='200' > 
```

* `src` is the source of the image and it could be an absolute url or a relative one.

* `alt` its an alternative test that will be displayed if the img failed to load.

* `width` and `hight` to control the width and the hight of the picture, for the value `'200'` is taken in pixels.

***

## Color

* CSS allow us to use color to make our page feel alive.
* Css treats each HTML element as if it appears in a box

## Color properties

* Foreground color
  * `color` property allows you to specify the color of text inside.
* Background color
  * sets the colors of the background for the HTML element box.

Examples

1. *Foreground*

```CSS
h1 {
    color:DarkCyan;

}
```

1. *Background*

```CSS
body {
    background-color: #ee3e80; 
}
```

## Chosing colors

1. RGB
    * Red Green Blue, color chosen by detrmain the ratio/value between those three basic color.
    * computer process all color like that.
    * RGB values varies between 0 and 255 (8-bit for each color)
    * Example ``` color:rgp(0,250,155); ```

2. Hexadecimal Value
   * each color represented by a hexadecimal number
   * Example ```background-color; #efefe```

3. Color name
   * Example ```color:red;```

4. Hue

5. Saturation
   * refer to the amount of gray in Color
   * maximum saturation = no gray color
   * minimum saturation = only gray color

6. Brightness
   * Brightness (or "value") refers to how much black is in a color.

7. Contrast
   * it is important to ensure that there is
enough contrast for the text to be legible.
   * the higher the contrast the more readable is the text for short span
   * the longer the Text the better to balance out the contrast
   * opacity
   * `rgba` like `rgb` but with addtional value for opacity
      * opacity value can be determined also by using thr property `opacity`

8. HSL colors
   * Hue Saturation Lightness
   * Hue value between 0 and 360 , saturation and ligtness value are percentage
        * Example ` color:hsl(320,30%,60%); `
   * HSLA had an additional value over HSL , Alpha which is the transparency its value between 0 and 1.0
      * Example `color:hsla(112,30%,40%,0.4);`

***

## Text

properties that can change on texts can be :

1. properties that effect on the font

2. properties that have direct effect on the text regardless what its font is.

* browser can only use typefaces that installed on user computer so that should be in mind when using one of them.

* Serif typeface fonts are easier to read so they are used in longer paragraphs.

* Sans-serif typeface give a clearer design.

* Monospace (Fixed-space) makes the text easier to follow.

* cursive fonts closer to hand writing.

* Fantasy are decorative fonts that can be used in titles.

```CSS
p {
    font-size:12px;
    font-family: Arial, Verdana, sans-serif;
    font-weight:bold;
    font-style:oblique;
    text-transform:uppercase; 

}
```

* `font-size` used to determine the text size and the default is 16 pixels , font-size values units:
  * pixels `px` gives precision , its the most popular unit as its give precision.

  * percentage `5%`.

  * EMS `em` changes the text size relatively to the parent element text size.

* `text-transform` transform the case of the words.

***

## jpeg vs png vs gif

> Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.
>
>TL;DR:https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d
