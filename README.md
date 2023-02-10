# twemoji.ttf

This project builds [Twemoji](https://github.com/twitter/twemoji) as a TrueType
font. In particular, it is usable on modern Linux (either desktop or mobile) as
well as other Unix-like distributions.

The build script here combines some patches from Fedora's package, the build
system from Noto fonts, and Twemoji itself from Twitter.

Font files themselves are redistributed as raw TTF files, so that any
downstream project can ship those without further hassle. Files are published
at:

    https://artefacts.whynothugo.nl/twemoji.ttf/

Builds are manually triggered when there are upstream releases.

# Prior art

Mozilla distributes it's own builds of this font. However, these are in a
font-format designed by Adobe and Mozilla, which basically only work on
Windows, Firefox and some very rare applications. Major toolkits like Qt and
GTK do not support them.

# Patches

Patches can be sent to my [public inbox]. Questions too.

[public inbox]: https://lists.sr.ht/~whynothugo/public-inbox

# Licence

Copyright 2019 Twitter, Inc and other contributors

Graphics licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/

## Build scripts

The code in this repository (which is honestly just a tiny script) is under the
Apache license, version 2.0. This choice was made to match the licensing of the
build scripts being used.
