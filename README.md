# ColorCodingDesigner
Small Javascript application supporting color coding design for a set of labels.

Idea
---
You can move your category labels on the color spectrum.
The color scheme is based on HSL color model.
What you see on the screen is hue ranging from 0 to 360
and luminance from 5% to 95%. Saturation is always 100%.

Features
---
You can add label. It appears roughly in the centre of the spectrum area.

You can sort your labels with respect to the hue values.

Import and export to files is possible.

Drag a label out of the color area to delete it.

Drag'n'drop input file on the colors area to load it.

Files
---
You can save or load the labels to a `.csv` file.
Format supporting MS Excel is used on save with the `sep=` header.
Input files need to have `label` and `color` columns
or the first column is treated as `label` and the second one is the `color`.

Labels are stored in the sequence visible on the screen.
Sort your labels if you want to have them ordered by hue.

Only hex codes are supported in the `.csv` files.
