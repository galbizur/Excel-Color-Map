# Excel-Color-Map
Tool created that enables table visualizations to appear close to Excel processed.

While pandas contains the ability to use a color map that ranges from Green-Yellow-Red and the reverse of it.
The client I coded the automation for had grown rather attached to the Excel color map over the one in pandas.
This was one of the rare occasions where the colors were too rich.

The codes for the color map were extracted using a RGBA script on a screen capture of a 7 cell range 1-7.

For a more gradual color change use a wider range.

Matploblib recognizes RGBA values 0-1, thusly why all values were divided by 255.

Everything needed to use in your code is already included.. just copy and paste and then set your cmap to my_cmap(_r) and that's it.

Enjoy!
