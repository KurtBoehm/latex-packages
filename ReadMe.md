# Assorted LaTeX Packages

A collection of LaTeX packages I have written over the years.
Some of them might, at some point, move to CTAN, but that is yet to be seen.
This repository is intended to be used as a git subproject with the name `packages`; anything else will result in errors.

The packages are:

- `Memoir`: Configure `memoir` to use small caps in a lot of places.
- `MemoirHeader`: Configure the `memoir` headers modified by `Memoir` to use a given font. Originally designed to use Cormorant Garamond for the headers and EB Garamond for the text, but other combinations are possible, too.
- `Env`: Get environment variable. Primarily designed to get the build directory.
- `Fonts`: Set up a variety fonts. The fonts are either taken from packages included in TeX Live or assumed to be in a `fonts` folder within the same parent folder as `packages`.
