# peppercarrot-metadata
Community-driven Metadata of Pepper &amp; Carrot and Its Episodes.

The data is written in JSON format.

This directory is also available directly as [http://qtwyeuritoiy.github.io/peppercarrot-metadata/](http://qtwyeuritoiy.github.io/peppercarrot-metadata/).

# License

This project is licensed under [CC0 1.0 (public domain)](https://creativecommons.org/publicdomain/zero/1.0/).

# Description

> episode.json

Lists common atrributes of episodes, including: page(includes title cover and credits) count(total_page), directory name(name) (e.g. "ep04_Stroke-of-genius"), and translation status(translated_languages).

**This file is obsolete. Refer to auto-generated [official file](https://peppercarrot.com/0_sources/episodes.json).**

> gif_slides.json

Lists info of slides that are in .gif format.

> files in /lang

Lists language-specific attributes of translated episodes, including: the displayed title(title) (e.g. en: "Episode 4 : Stroke of Genius").

Each file name is a name of the language as shown in [the translations panel](https://www.peppercarrot.com/en/static6/sources&page=translation)

> /lang/lang.json

This is a special file for mapping P&C language code with the standard [ISO 639-1](https://en.m.wikipedia.org/wiki/ISO_639-1). It also includes full name in English for identifying languages that are not listed in ISO specifications.