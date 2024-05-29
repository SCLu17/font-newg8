NewG8 is an open font family based on the original designs of Claude Garamond.

This project is derived from Michael Sharpe’s modifications to (URW)++’s Garamond No. 8, itself bearing close resemblance to Linotype/Adobe’s Stempel Garamond.

The project is forked from probonopd’s TTF conversions. Additional modifications so far include:

- Tidied character mappings, introducing OpenType features (old-style figures, small capitals, f-ligatures, one stylistic set (enables a long-tailed Q)).
- Unified the package into four fonts.
- Tidied kerning pairs.
- Addition of glyphs with diacritical marks as provided in the original packages.

There is otherwise no change to the glyphs’ designs from 2017.

## Ligatures

By default, f-ligatures are not included in the common ligature tables (`liga`) for the regular and bold fonts, but are included in the italic and bold italic fonts. If you wish to use f-ligatures in the regular and bold fonts too, please toggle discretionary ligatures (`dlig`).

With common ligatures enabled:

![liga](https://github.com/SCLu17/font-newg8/assets/85668984/671f7cfd-dc16-4a4a-bdfa-113b5b6a517e)


With discretionary ligatures enabled:

![dlig](https://github.com/SCLu17/font-newg8/assets/85668984/8729dd9f-b4d5-4772-a37b-4a0ec3143a27)


## Download

Fonts in TTF format can be downloaded from [GitHub Releases](../../releases).

## Copyright and License

Modified version of garamondNo8 (Copyright (URW)++, Copyright 2000 by (URW)++ Design and Development).

Modified kerning data was based initially on a package by Gael Garoquaux. This was subsequently manually adjusted in Fontforge by Bruce S.C. Lu.

Modifications are Copyright 2012–2017 by Michael Sharpe (msharpe@ucsd.edu) and Copyright 2021–2022 Bruce S.C. Lu, and are subject to the Aladdin Free Public Licence.
