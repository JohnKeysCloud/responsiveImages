#responsiveImages

In my learning, I created this page to display responsive images.

The first image displaying the aurora, solves the "art direction" problem, where an alternate, smaller image is shown on displayed screens.
This is achieved using <picture>, highlighting "srcset"(see code for full syntax).

The second image displaying yours truly, solves the "resolution switching" problem, where as multiple versions of the same image are provided at different resolutions to preserve bandwidth on devices with smaller viewports by displaying the smallest possible version without sacrificing the quality of the image.
The "sizes" attribute (only for use when adding the intrinsic width value of each image within each comma-separated source using "w" instead of px... vs adding nothing... or 2x / 3x) is what I'd like to highlight here

... to be continued (inital commit prior to full understanding)
