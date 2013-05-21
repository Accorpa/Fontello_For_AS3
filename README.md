Description
===========

The Fontello.as Class allow you to use the Fontello font (http://fontello.com/) in Flex, the font contains all icons 
that fontello have.

Fontello basically provide a way to put icon inside your text easily without the need for an image, and it is also
vector based and can be colored.

The TryFonts project has a browser for all available icons and there variable names, for easy access.

The font contains more than 1,669 Icon.

Try the DEMO here http://developers.accorpa.com/fontello/TryFonts.html

How to use:
============
1) include the fontello.ttf and Fontello.as in your project.

2) embed fontello.ttf in your style
```
@font-face {
        src: url("fontello.ttf");
        fontFamily: Fontello;
}
```

``` as
        <s:Label text="{Fontello.camera_alticon}" fontSize="14" fontFamily="Fontello" color="red"/>
```
3) doesn't work with mx components only spark.
