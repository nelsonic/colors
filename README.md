colors
======

A little experiment in Color (HTML + CSS + JavaScript)

![Color Spectrum](https://raw.github.com/nelsonic/colors/master/misc/Color-spectrum-thin.png "Color spectrum")

Sick of not knowing what the names / hex values of colors were I decided to create a little colors mini app that I can keep handy when ever I need to look up a color or remember one I've used before. (Don't worry there's more to it, but I'm keeping it simple for now ;-)

## Intro

Though often overlooked, color is an integral part of our lives.
Nature has used color to communicate since the beginning of time and humans are no exception.

(For the people *unlucky* enough to be 
[color-blind](http://en.wikipedia.org/wiki/Color_blindness) 
please feel free to *skip this chapter*)

As Web/Software developers/designers we use color all the time.
Fonts, Text Highlighting, Images, Backgrounds, Borders, Tables, you name it, all *enhanced* with color!

Most of the time we work from a pre-defined 
[color-scheme](http://en.wikipedia.org/wiki/Color_scheme) 
enshrined in some brand guidelines.
but every so often we get to work on something ** * New * **, 
if you are *lucky* enough to be in that position cherish it!

The process of discovering and deciding on colors can be
equal parts exciting and frustrating. 
Several times I have come up against the claim that:
**"XYZ Corp. is already using that color so we can't..."**

![Brands and their colors](http://images.sixrevisions.com/2009/11/10-03_brand_colors.png "Brand Colors")

See: ["T-Mobile Owns the Color Magenta"](http://www.colourlovers.com/blog/2007/11/04/beware-t-mobile-owns-the-color-magenta/)
and ["The Battle for Blue"](http://farm1.staticflickr.com/29/56867986_29aa1a3973_o.jpg))

But we need not despair, there are *plenty* of shades still left to chose from!
The [RGB (RedGreenBlue) "True Color" System](http://en.wikipedia.org/wiki/RGB_color_model) 
has 16.7 Million colors. 
[ 256 x 256 x 256 = 16,777,216 = 2<sup>24</sup> (Hence 24-Bit Color)] 

If you looked at *one color per second* it would take **194 days** to cycle through all the available colors. [ 256 x 256 x 256/(60 x 60 x 24) = 194.18]

Even if you viewed each color for just 20 miliseconds (50 colors per second) it would still take almost **4 days** to see them all. [ 256 x 256 x 256/(60 x 60 x 24 x 50) = 3.88 ]

Obviously viewing *one* color at a time is *inherently slow*. 
While it would make an OK "modern art" installation 
in a 360-degree projected color room, 
not that many people have this kind of *time*...

If instead we view a **palette** of colors on a large screen (e.g. 27 inch hi-res display) we have 3.68 Million [2560 x 1440 = 3,686,400] pixels available. 

To display **ALL colors** (symultaneously) at **one color per pixel**
would require **5 Monitors** 
[ 256 x 256 x 256 / (2560 x 1440) = 4.551 ] ... 
How many people have *Five* high-resolution monitors handy...? :-)

So instead we need a way of displaying fewer colors intelligently.



- - -

### Random Color Generator

While playing I built a quick **Random Color Generator** 
it does exactly what you would expect. 

![Random Color Generator](https://raw.github.com/nelsonic/colors/master/misc/random-color-generator.png "A Simple Random Color Generator!")

see: **random.html**

Obviously that's not very *useful* (it was just an experiment). 
So... lets get on to the palete.


### ideaQ for ways to Discover Colors

- Color Slider(s) 
- Color Lab (use keyboard R,G,B and arrow keys manipulate colors)
- Palette with 'Expander'
- Search by name auto-complete and expander
- Colors Trending/Stats (web crawler with focus on colors in CSS documents)
- Eye Dropper (most graphics programs have this or see *[ColorZilla](http://www.colorzilla.com/)* Firefox Plugin)
- Colors shared on Twitter ? (long shot but could be interesting ;-)

- - -

### Notes and Research

#### Websites Dedicated to Color

- Color Lovers (A great place to discover colors): [colourlovers.com](http://www.colourlovers.com)
- Color Matters: http://www.colormatters.com/ + http://www.pinterest.com/colormatters/
- Color Voodoo: www.colorvoodoo.com
- Spoonflower Color Map: http://www.spoonflower.com/SpoonFlower_ColorMap_2-1.png
- Visibone Color Charts: http://www.visibone.com/color/

- PDF with 800 colors: http://planetguide.com/docs/Pantone%20chart%20with%20RGB%20and%20HTML%20conversions.pdf
- PDF with 18 pages of colors http://www.techfak.uni-bielefeld.de/~walter/misc/colorRGB.pdf (scroll down to see there are in fact many more than "50 Shades of Grey"...)

- Quite similar to what I envisaged: http://www.colorschemer.com/online.html
- Style Guidelines for Brands: http://www.smashingmagazine.com/2010/07/21/designing-style-guidelines-for-brands-and-websites/

#### Useful Wikipedia Articles

- Color Depth: http://en.wikipedia.org/wiki/Color_depth
- RGB Color Model: http://en.wikipedia.org/wiki/RGB_color_model
- Web Safe Colors: http://en.wikipedia.org/wiki/Web_colors#Web-safe_colors 

#### Colorful Articles and Posts

- Color the next limited resource: http://sixrevisions.com/web_design/color-the-next-limited-resource/
- T-Mobile Owns Magenta: http://www.colourlovers.com/blog/2007/11/04/beware-t-mobile-owns-the-color-magenta/
- Microsoft Sues Google for Color Infringement: http://www.cap-news.com/story.php?id=200907011
- Basic Color Theory: http://www.colormatters.com/color-and-design/basic-color-theory
- Color Blindness research: http://www.colour-blindness.com/general/prevalence/
- Color Psycology in Medicine: http://munsell.com/color-blog/color-psychology-medicine-jill-morton/