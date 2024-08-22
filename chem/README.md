# Convert webarchive to html

textutil -convert html example.webarchive

Be careful — html with files is created in the same folder as webarchive!

Also, I had to open .html with text editor and replace "file:///image.tiff" links (replace "file:///" with "") so they point to relative path.

Also, not all browsers display .tiff images.
