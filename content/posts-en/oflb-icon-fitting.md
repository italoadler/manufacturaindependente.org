Title: OFLB: Icon fitting
Date: 2011-08-04 17:16
Author: manufactura
Status: draft
Category: Post
Tags: oflb
Slug: oflb-icon-fitting
Lang: en

One of our tasks in OFLB is to design status icons for various
states that a font can have. They are to be featured in the admin
section, where librarians and secretaries (OFLB nomenclature for admins
and editors) can check on the status of the published fonts.

While serving an obvious decorative function, icons have to be easily
distinguishable from each other while scanning a page. Given OFLB's
limited colour palette, we have an additional restriction to work with
-- since colour is a straightforward way to differentiate two elements.
And once you try your hand at icon design, you quickly find it requires
a specific skill set of its own. (Regarding this, Nuno Pinheiro’s
interview in [Libre Graphics Magazine](http://libregraphicsmag.com) \#2
is a great read.)

Earlier, we posted initial ideas for those icons. For this, we used a
capital F from the
[Bevan](http://www.google.com/webfonts/family?family=Bevan) font, along
with visual elements reflecting the font status.

After doing the vector sketches, we then proceeded to adapt them to a
pixel grid. If you’re into FLOSS design tools, you know you don’t have
to leave Inkscape to make crisp pixel icons.

### Aligning shapes to the pixel grid

First, we need to tweak the shapes’ nodes in order to fit them into the
pixel grid. You can turn on the pixel grid in *Document Properties \>
Grids*, setting a 1px grid spacing. We used 4px for each major grid
line, since we are aiming for 16x16 icons.

To see why this step is relevant, here’s an example of the original and
pixel-aligned shapes, after exporting to a bitmap file:

[![Screenshot 1]({filename}/media/Screenshot-1.png "Screenshot-1")]({filename}/media/Screenshot-1.png)  

[![Screenshot 2]({filename}/media/rect4031.png "rect4031")]({filename}/media/rect4031.png)

### Icon preview

We don’t need to export every time in order to see the output, though.
Inkscape has this awesome **Icon preview** window which shows the bitmap
output in various icon sizes (and you can set your own custom sizes as
well).

[![Screenshot 3]({filename}/media/Screenshot-3.png "Screenshot-3")]({filename}/media/Screenshot-3.png)

### Where we are

So these are what we came up with. There's still room for tweaking, and
we're confident in this direction.

[![Flag icons in the pixel grid]({filename}/media/flag-icons-pixelgrid.png "flag-icons-pixelgrid")]({filename}/media/flag-icons-pixelgrid.png)

[caption id="attachment\_151" align="aligncenter" width="516"
caption="All font states, from left to right: Normal, Featured, Hidden,
Needs Checking, Marked for Removal,
Broken."][![Flag icons in the pixel grid]({filename}/media/flag-icons-pixelgrid-3x.png "flag-icons-pixelgrid-3x")]({filename}/media/flag-icons-pixelgrid-3x.png)[/caption]  

