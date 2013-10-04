colors
======

![Color Spectrum](https://raw.github.com/nelsonic/colors/master/screenshots/Color-spectrum-thin.png "Color spectrum")

A little experiment in Color (HTML + CSS + JavaScript)

*Sick of not knowing what the names / hex values of colors were I decided to create a little (single-page) colors app.*

## Background

Though often overlooked, color is an integral part of life.

As Web/Software developers we use color all the time. 

We use color to highlight identification, communication.

![Life without color](http://fc08.deviantart.net/fs71/i/2011/147/b/e/what__s_life_without_color_by_lydiajeanphotography-d3hdlzp.jpg "A life without color")



The RGB (RedGreenBlue) Color System has 16 Million (16,581,375) colors. 

see: http://en.wikipedia.org/wiki/RGB_color_model

If you looked at *one color per second* it would take **192 days** to cycle through all the available colors. [ 255 x 255 x 255/(60 x 60 x 24) ]

Even if you viewed each color for just 20 miliseconds (50 colors per second) it would still take almost **4 days** to see them all. [ 255*255*255/(60*60*24*50) ]

Obviously viewing *one* color at a time is inherently slow. 
While it would make an OK "modern art" installation 
in a 360-degree projected color room, 
not that many people have this kind of *time*...

If instead we view a **palete** of colors on a large screen (e.g. 27 inch hi-res display) we have 3.68 Million [2560 x 1440 = 3,686,400] pixels available. 

To display *all* the colors at *one color per pixel*
would require **5 Monitors** to display them all symultaneously. 
[ 255 x 255 x 255 / (2560 x 1440) = 4.498 ]

How many people have *Five* high-resolution monitors handy...? :-)

So instead we need a way of displaying fewer colors.



- - -

### Random Color Generator

While I was playing I built a quick **Random Color Generator** 
it does exactly what you would expect. 

![Random Color Generator](https://raw.github.com/nelsonic/colors/master/screenshots/random-color-generator.png "A Simple Random Color Generator!")

see: **random.html**

Obviously that's not very *useful* (it was just an experiment). 
So... lets get on to the palete.




