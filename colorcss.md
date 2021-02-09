# Color 

* CSS allow us to use color to make our page feel alive.
* Css treats each HTML element as if it appears in a box 


## Color properties 

* Foreground color 
    * `color` property allows you to specify the color of text inside. 
* Background color
   * sets the colors of the background for the HTML element box.

**Examples**

1. *Foreground*
```
h1 {
    color:DarkCyan;

}
```
2. *Background* 
```
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
   * Example ``` background-color; #efefe  ```

3. Color name 
   * Example ```color:red; ```

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
        * Example ` colro:hsl(320,30%,60%); `
    * HSLA had an additional value over HSL , Alpha which is the transparency its value between 0 and 1.0 
         * Example `color:hsla(112,30%,40%,0.4);`