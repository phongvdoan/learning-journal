# CSS - Color
You can specify color in three ways:
1. RGB values meaning Red, greena and blue.
2. Hex Code which is a six-digit code that represents the amount of red, green, and blue in a color.
3. One of the 147 predefined color names.
For foreground color:
```
h1 {
  color: DarkCyan;}
h2 {
  color: #ee3e80;}
```
CSS treats each element as if it is in a box. You can specify background color:
```
body {
    background-color: rgb(200,200,200);}
h1 {
    background-color: DarkCyan;}
```

Color picker can be used to get information at http://colorschemedesigner.com

Saturation is the amount of gray in the color. Brightness how much black is in the color.
When picking a color, it is important to ensure that there is enough contrast for the text to be legible. Text is easier to read in high contrast, but only ideal for short span of words. For long spans of text, medium contrast can improve readability.

## Opacity

 CSS3 allows you to specify opacity of an element and its child elements ranging from 0.0 to 1.0.
 CSS3 rgba allows you to specify the color and adds a fourth value to indicate opacity known as alpha value.

## Alternate

 HSL and HSLA are an alternate way to specify colors. hsl followed by the values inside parentheses for:
    - Hue which is expressed as an anlge from 0 to 360 degrees
    - Saturation as a percentage
    - Lightness from 0 to 100 percent, white to black
    - Alpha is a number between 0 to 1.0 for transparency.
    
    
    body {
        background-color: #C8C8C8; 
        background-color: hsl(0,0%,78%);}
    p{
        background-color: #ffffff; 
        background-color: hsla(0,100%,100%,0.5);}
    
