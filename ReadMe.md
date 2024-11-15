# Assorted LaTeX Packages

A collection of LaTeX packages I have written over the years.
Some of them might, at some point, move to CTAN, but that is yet to be seen.
This repository is intended to be used as a git subproject with the name `packages`; anything else will result in errors.

The packages are:

- `Env`: Get environment variable. Primarily designed to get the build directory.
- `Fonts`: Set up a variety fonts. The fonts are either taken from packages included in TeX Live or assumed to be in a `fonts` folder within the same parent folder as `packages`.
- `Maths`: A lot of mathematical utilities. `\del` is the most noteworthy and allows for uses such as `\del(a)` and `\del{b}`, which are typeset using `\left` and `\right`.
- `Memoir`: Configure `memoir` to use small caps in a lot of places.
- `MemoirHeader`: Configure the `memoir` headers modified by `Memoir` to use a given font. Originally designed to use Cormorant Garamond for the headers and EB Garamond for the text, but other combinations are possible, too.
- `SemanticCode`: Highlight code using `pysemco_tex` from [`pysemco`](https://github.com/KurtBoehm/pysemco).
- `Units`: Set up `siunitx` and add a few units.
- `UnixTime`: Convert the timestamps provided by LaTeX3 to Unix timestamps (without leap seconds), with commands to query Unix timestamps directly.
