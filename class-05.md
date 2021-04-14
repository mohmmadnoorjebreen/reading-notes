# read

## Chapter 5: “Images” (pp.94-125)

A picture can say a thousand words.

### Adding Images

```
<img src="images/quokka.jpg" alt="A family of
quokka" title="The quokka is an Australian
marsupial that is similar in size to the
domestic cat." />
```

### Height & Width of Images

specify the size of the image
so that the browser can render
the rest of the text on the page
while leaving the right amount of
space for the image that is still
loading.

### Three Rules for Creating Images

1. Save images in
the right format

2. Save images at
the right size

3. Use the correct
resolution

### Image Formats: JPEG

Whenever you have many different
colors in a picture you should use a JPEG.

![Image Formats: JPEG](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRb8r_XDS58Xp1xQOkDs2EtAzKx3CSWqz8xEA&usqp=CAU)

### Image Formats: GIF

Use GIF or PNG format
when saving images
with few colors or large
areas of the same color.

![Image Formats: GIF](https://upload.wikimedia.org/wikipedia/commons/a/aa/SmallFullColourGIF.gif)

## Chapter 11: “Color” (pp.246-263)

The color property allows you
to specify the color of text inside
an element.

You can specify any
color in CSS in one of three ways in Foreground Color

## Foreground Color

### rgb values

 These express colors in terms
of how much red, green and
blue are used to make it up.

### hex codes

These are six-digit codes that
represent the amount of red,
green and blue in a colo

### color names

There are 147 predefined color
names that are recognized
by browsers.

![color names](https://99designs-blog.imgix.net/blog/wp-content/uploads/2018/02/COLOR-MEANINGS.jpg?auto=format&q=60&w=1860&h=1395&fit=crop&crop=faces)

## Background Color

CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.

## Understanding Color

every color on a computer screen is created by mixing amounts of:

1. red
2. green
3. blue

## Chapter 12: “Text” (pp.264-299)

The formatting of your text can have a significant effect
on how readable your pages are.

### Typeface Terminology

1. Serif

serif fonts were
traditionally used for long
passages of text because they
were considered easier to read.

2. Sans-Serif

Screens have a lower resolution
than print. So, if the text is small,
sans-serif fonts can be clearer
to read.

3. Monospace fonts are commonly
used for code because they align
nicely, making the text easier to
follow.

### Specifying Typefaces

The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.

```
<!DOCTYPE html>
<html>
<head>
<title>Font Family</title>
<style type="text/css">
body {
font-family: Georgia, Times, serif;}
h1, h2 {
font-family: Arial, Verdana, sans-serif;}
.credits {
font-family: "Courier New", Courier,
monospace;}
</style>
</head>
<body>
<h1>Briards</h1>
<p class="credits">by Ivy Duckett</p>
<p class="intro">The <a class="breed"
href="http://en.wikipedia.org/wiki/
Briard">briard</a>, or berger de brie, is
a large breed of dog traditionally used as
a herder and guardian of sheep...</p>
</body>
</html>
```

## JPEG vs PNG vs GIF

There are hundreds of image formats available each with a specific use case.

the most image formats in websites and mobile applications:
1. JPEG

Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth.

2. PNG

Use PNG format for any image that needs transparency.

3. GIF

Use GIF format for images that contain animations.

To choose the best image format, the following should be taken into consideration.

* Compression

* Transparency

* Colours

* Animation

