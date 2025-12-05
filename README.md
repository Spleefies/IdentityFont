![Title](https://raw.githubusercontent.com/Spleefies/IdentityFont/main/docs/resources/title.png)

# IdentityFont
Reconstruction of the LTAIdentity font, a Humanistic sans-serif font that is commonly found in Singapore's public transport graphics.

[Download it from the Releases](https://github.com/Spleefies/IdentityFont/releases)

## How was it made?
This was forked from [jglim/IdentityFont](https://github.com/jglim/IdentityFont), and the characters added after were pulled from [this document](https://www.lta.gov.sg/content/dam/ltagov/who_we_are/statistics_and_publications/books/pdf/REthink_190918web.pdf) using MuPDF.

## Is it exact?

![Overlay](https://raw.githubusercontent.com/Spleefies/IdentityFont/main/docs/resources/overlay.jpg)

No. The individual glyphs' outlines should be pretty close, along with its metrics such as the baseline, x-height and cap height. However, the letter-spacing (leading/tracking/kerning) varies significantly as I do not know of any techniques to create a close match. Instead, this font was optically spaced, then manually adjusted by hand. The above overlay shows this font (in pink) over an existing signage, highlighting the spacing variations.

Please let me know if there are better approaches to this issue.

## What's in the character set?
[a-zA-Z0-9] and +-./,:;<=>!&"'?()_.

![Glyphs](https://raw.githubusercontent.com/Spleefies/IdentityFont/main/docs/resources/glyphs.png)

## Does it support hinting?
No.

## There seems to be another font that's used in our public transport..?
That would most likely be _Ocean Sans_, which is frequently used together with their Identity font.
Newer signages will most likely use _Stroudley_.
