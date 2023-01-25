# twemoji.ttf

This project builds [Twemoji](https://github.com/twitter/twemoji) as a TrueType
font. In particular, it is usable on modern Linux (either desktop or mobile) as
well as other Unix-like distributions.

The build script here combines some patches from Fedora's package, the build
system from Noto fonts, and Twemoji itself from Twitter.

Font files themselves are redistributed as raw TTF files, so that any
downstream project can ship those without further hassle.

# Prior art

Mozilla distributes it's own builds of this font. However, these are in a
font-format designed by Adobe and Mozilla, which basically only work on
Windows, Firefox and some very rare applications. Major toolkits like Qt and
GTK do not support them.

# Licence

Copyright 2019 Twitter, Inc and other contributors

Graphics licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/

The build system and Fedora's patches have their own licence, but these are
just dependencies of this project; this project does not redistribute them.
