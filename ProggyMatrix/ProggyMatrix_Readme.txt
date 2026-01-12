ProggyMatrix is a cubic-spline font visually based on ProggyClean and ProggyVector. It is MIT Licensed (only). ProggyMatrix has fewer glyphs compared to ProggyVector but benefits from a clean MIT License stack.

Notes:
* Created with FontForge. Version 20251009 as of 2026-01-11. BirdFont is not used.
* Currently set to encode ISO8859-1
* ALL glyph widths should be set to 600 (monospaced).
* Authoring is done using Cubic Splines (only) even though TTF is Quadratic. We let FF figure out the conversion.
* Em size is 1024 (TTF likes power of 2 sizes). Ascent: 768. Descent 256.
* For line spacing the OS/2 Metrics are used. To give a bit more separation we add 128+64=192 to the ascent of 768 yielding 960. On Windows sometimes TypoAscent, TypoDescent, and TypoLineGap may be ignored and WinAscent and WinDescent used instead. They are set equivalently.
* X-height (for lower-case X) is 520.
* Cap-height (for capital letters) is 720.
* Additional rulers for Cap-height, X-height, Cap-center, and X-center have been added. The baseline, ascent, and descent are automatically displayed.
* Arithmetic operators (like asterisk, plus, minus, etc) should be centered vertically about X-center.
* Digit (0 to 9) glyphs should be Cap-height high (and not over-shoot).
* When centering a non-symmetric glyphs horizontally, use jusdgement to have roughly equal whitespace area on the right and left. Symmetric glyphs can use FFs "Center in Width".
* Fewer Spine CVs are better.
* When "Generating Fonts" with TrueType selected, validation should be enbled and clean.
* Version starts at 0.1.0. Can increment as desired until all ISO8859-1 glyphs are done, at which point version is 1.0.0
* There are 190 glyph shapes for ISO8859-1 (including SPACE).

Tag Font as Monospaced:
* Select Element -> Font Info -> OS/2
* Under Misc set PFM Family to Monospace.
* Under Panose set Proportion to Monospaced.

Other FontForge Notes:
* In Font Info -> Lookups the kerning info is in GPOS. It has been removed for monospace.
* In Font Info -> PS Names make sure the Versions and names match what you see under TTF Names.
* FontForge cannot create embeddable EOT files. To do so use the online tool here (https://www.kirsle.net/wizards/ttf2eot.cgi) and drop the generated ttf file there.
* There is a FontForge book on creating typefaces at http://designwithfontforge.com/ebook/design-with-fontforge_en-US.pdf
