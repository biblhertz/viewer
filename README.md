# viewer
IIIF viewer with paramaters snatched from URL

index.html was a start, but is now deprecated (delete w/o problems)

viewer.html (short URL: id instead of manifest) is now online at dlib.biblhertz.it/viewer

Working Example:

https://dlib.biblhertz.it/viewer?id=be39205320&view=annotations&canvas=26

Parameters

id	[string]	a filename string which will be complemented as here: https://dlib.biblhertz.it/iiif/+ STRING +/manifest2.json
canvas	[0-9]* without leading zeroes	124 is ok, but not 009
view	annotations, attribution, canvas, info	for now, not search or layers

