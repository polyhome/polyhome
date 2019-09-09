# Classes

## What is a class?

If you're familiar with web development, you'll know what a class is. The classes you define in your configuration, are straight CSS classes that will be applied to groups or cards you want to.

To those who are not familiar with web development: when you want to style something in a specific way, you can tell a specific element everything you want it to have. Maybe a nice border, or a specific background color. It doesn't hurt to tell the specific element all this, but it becomes tiring when you suddenly have 10 elements, that you want to be styled in the same way. Enter Classes.

## Example

Out of the box PolyHome offers some Classes. In many cases you will end up using the `card` class. This class will give an element a nice shadow around the edges. This is an example of how a class can be used purely for styling. Because PolyHome supports what are called native CSS classes, the possibilities for styling are almost endless!

Another example of how classes can be used, are in terms of resizing/scaling content. Heavily inspired by Bootstrap, you can give elements classes like `col-4` and `row-2`. This will make an element that spans 4 columns and 2 rows. Now is a good time to introduce the grid system within PolyHome.

## Grids

In order to make PolyHome as dynamic as possible, it utilises a grid system. More on how this makes it dynamic later. Whenever you are looking at your setup, it is divided into a 12 columns and 12 rows. From here it is then up to you, how you want to style your setup.

By default, all elements will fill up from left to right, and spill onto the next row if needed. Say you have 4 elements with the class `col-4`. 3 of those elements will be put next to each other on the same row, while the 4th will be put onto the next row. In the case that those 4 elements have the class `col-3`, they will be on the same row.

## \*-md-\*

This is where it gets a bit more complicated, but also more dynamic. Most likely you aren't going to only ever use your setup on the same size screen. Sometimes it may be on a tablet, other times on your PC, and sometimes on your phone. Wouldn't it be nice to have your setup scale to whatever device your watching it on? Well that's certainly possible.

If you give an element the class `col-4`, it will take up 4 columns. If you then also give an element the class `col-md-6`, it will take up 6 columns when viewed on a **m**edium-sized **d**evice. PolyHome provides 3 options like this.

| \*-md-\*  | \*-sm-\* | \*-xs-\* |
| --------- | -------- | -------- |
| < 1200 px | < 992 px | < 768 px |

Just to hammer the point home. Say you have an element with the following classes: `col-4, col-md-6, col-sm-8, col-xs-12`.

- When the screen width is over `1200 px`, it will fill 4 columns.
- Between `1200 px` and `992 px`, the element will fill 6 columns.
- Between `992 px` and `768 px`, the element will fill 8 columns.
- When under `768 px`, the element will fill 12 columns.
