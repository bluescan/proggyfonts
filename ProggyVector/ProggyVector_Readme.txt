The FontForge sfd files are currently the latest source project files for Proggy Vector since FontForge a) Lets you set the tags for a monospaced font, and b) Supports more extensive validation than the birdfont files.

The birdfont files are NOT up to date with all the fixes in the sfd files(non-overlapping shapes, extrema fixes, curve direction fixes, etc).

To tag the font as monospaced in FontForge:
* Select Element -> Font Info -> OS/2
* Under Misc set PFM Family to Monospace.
* Under Panose set Proportion to Monospaced.

Other FontForge notes:
* In Font Info -> Lookups the kerning info is in GPOS. It has been removed for monospace.
* In Font Info -> PS Names make sure the Versions and names match what you see under TTF Names.
* FontForge cannot create embeddable EOT files. To do so use the online tool here (https://www.kirsle.net/wizards/ttf2eot.cgi) and drop the generated ttf file there.
