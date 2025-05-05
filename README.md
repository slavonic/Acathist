# Acathist Typeface

Acathist is a contemporary Church Slavonic font that reproduces the typeface used in the Synodal editions of the second half of the 19th and early 20th centuries. This typeface was used for large format editions such as Altar Gospel Books and Acathists.

![Sample Image](documentation/image2.png)

## History

The font was originally designed by Vlad Dorosh as Akathistos UCS for
the [Irmologion project](http://irmologion.ru/fonts.html#akathistos).
It was then released under the LaTeX Project Public License
as part of [CSLTeX](https://sites.google.com/site/csltex/).
Next, it was reencoded for Unicode by Aleksandr Andreev.
Additional glyphs and OT features were by Aleksandr Andreev
and Nikita Simmons and the font was released as Acathist
as part of the [Slavonic Computing Initiative](https://sci.ponomar.net/fonts.html), and under SIL OFL v. 1.1.

## License

This Font Software is licensed under the SIL Open Font License,
Version 1.1. This license is available with a FAQ at
[https://openfontlicense.org/](https://openfontlicense.org/).

## Building the Fonts

The font source is stored in a FontForge SFD file in the `sources/` directory. All modifications should be made in FontForge, resulting in an updated SFD file. This file is then converted to UFO format by running the convert script. From terminal:

```
cd your/local/project/directory
./convert.sh
```

The font can then be built using fontmake and gftools by running:

```
make build
```

Note that this requires Python and will install all of the necessary libraries and tools into a virtualenv at `venv/`.

To delete the virtualenv and the results of the build, run:

```
make clean
```

To build the sample image the sits at the top of this README, run:

```
make images
```

The commands `make update` and `make update-project-template` update the repository structure and Python dependencies and should be run periodically.

Google's master repository also had a GitHub workflow for building the fonts in the cloud on push, but this seems to always fail because of incorrect dependencies, so has been disabled. Instead, built binaries are stored on GitHub in the `fonts/` directory.

## Features

* Stylistic Set 1 (*ss01*) changes the hyphen symbol (-) to an 
underscore (_), which is the default hyphenation symbol used
in Synodal Church Slavonic. This can be used for software such
as LibreOffice that does not support changing the default
hyphenation character.

* Stylistic Alternatives (*salt*) are provided for the following
characters:
  - an alternative form of capital ot (U+0460)

See your software's documentation about how to access these glyphs.

## More Church Slavonic Fonts

See the [main repository](https://github.com/typiconman/fonts-cu/issues) and the [website](https://sci.ponomar.net/fonts.html).
