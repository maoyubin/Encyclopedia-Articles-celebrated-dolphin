# background-position

Positioning your background.

background-position is a CSS property that allows you to set the position for the background image you have chosen.


## Syntax

The CSS property background-position:



`div {`

`background-image: url('http://all4desktop.com/data_images/original/4246653-duck.jpg');`

`background-position: `

`}`

![](http://puu.sh/rupAe/8310d6ada0.jpg)

The default positioning of a background-image. I have used a url to set the background image. 

## Center

If you want to center the background-image, you will want to use the below example.

```
        background-position: center;
```

![](http://puu.sh/rupLq/cb12c243fc.jpg)

You can see that the background-position: center has centered the background image both vertically and horizontally.

Other keywords are: top, bottom, left, right.

## Percentages

You can also use percentages to position the background-image.

```
        background-position: 25% 75%;
```

![](http://puu.sh/rupWe/e47aa8e586.jpg)

This is setting the left and bottom spacing to 25%, while setting the right and top spacing to 75%. 

## Length Units

You can use length units to position your background-image. Here we are using cm to position the image.

```
        background-position: 4cm 3cm;
```

![](http://puu.sh/rur1j/c80511c93f.jpg)

As you can see, this puts the image 4 centimeters from the left, and 3 centimeters from the top.

#### Absolute Length Units:

**px**: One device pixel.

**mm**: One millimeter.

**q**: A quarter of a millimeter.

**cm**: One centimeter.

**in**: One inch.

**pt**: One point(1/72th of an inch).

**pc**: One pica (12 points).

#### Relative Length Units

**em**: Based on the calculated font-size of the element.

**ex**: Based on the x-height of the element's font.

**ch**: Based on the width, or the glyph '0' (advance measure), of the element's font.

**rem**: Based on the font-size of the root element, or the font-size of the `<html>` element.

## Special Notes

#### Viewport-percentage lengths

You can use viewport-percentage lengths as shown below. 

[Source](https://developer.mozilla.org/en-US/docs/Web/CSS/length)

**vh**: 1/100th of the height of the viewport.

**vw**: 1/100th of the width of the viewport.

**vmin**: 1/100th of the minimum value between the height and width of the viewport.

**vmax**: 1/100th of the maximum value between the height and the width of the viewport.

####Size conversion

**1in** is always 96px.


**3pt** is always 4px.


**25.4mm** is always 96px.