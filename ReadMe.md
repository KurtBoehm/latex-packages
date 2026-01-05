# Assorted LaTeX Packages

A collection of LaTeX packages I have written over the years.
Some of them might, at some point, move to CTAN, but that is yet to be seen.
This repository is intended to be used as a git subproject with the name `packages`; anything else will result in errors.

The packages are:

- `BeamerClausthal`: My Clausthal beamer theme, which is simply `moloch` with some customizations. Since `beamer` does not support themes in subfolders, no attempt has been made to follow its naming conventions.
- `BeamerTools`: Tools for use with `beamer`. Currently, the main tool is `\AltOnSlide`, which supports switching between multiple contents (like an extended version of `\alt`) while allocating an appropriate amount of space for all contents (like `\onslide`).
- `Env`: Get environment variable. Primarily designed to get the build directory.
- `Fonts`: Set up a variety fonts. The fonts are either taken from packages included in TeX Live or assumed to be in a `fonts` folder within the same parent folder as `packages`.
- `LanguageCases`: Switch between different contents depending on the document language.
- `Listings`: Extended language definitions for `listings`.
- `Maths`: A lot of mathematical utilities. `\del` is the most noteworthy and allows for uses such as `\del(a)` and `\del{b}`, which are typeset using `\left` and `\right`.
- `Measure`: Measure multiple contents and compute dimensions based on the results.
- `Memoir`: Configure `memoir` to use small caps in a lot of places.
- `MemoirHeader`: Configure the `memoir` headers modified by `Memoir` to use a given font. Originally designed to use Cormorant Garamond for the headers and EB Garamond for the text, but other combinations are possible, too.
- `NumberFormat`: Format a number, especially to align numbers in a table.
- `OpenColor`: Provide `xcolor` definitions for the [OpenColor](https://yeun.github.io/open-color/) colours.
- `Picta`: My own colour scheme, which is already available in a VS Code theme.
- `QrCode`: Generate TikZ-based QR codes using [PolyQR](https://github.com/KurtBoehm/polyqr).
- `RadixColors`: Provide `xcolor` definitions for the [Radix](https://www.radix-ui.com/colors/) colours.
- `RoundedRectangle`: A TikZ rounded rectangle with a per-corner radius.
- `SemanticCode`: Highlight code using `pysemco_tex` from [`pysemco`](https://github.com/KurtBoehm/pysemco).
- `Units`: Set up `siunitx` and add a few units.
- `UnixTime`: Convert the timestamps provided by LaTeX3 to Unix timestamps (without leap seconds), with commands to query Unix timestamps directly.

## License

The packages within this project are licensed under the terms of the LaTeX Project Public License 1.3 or later, which is provided in [`License`](License).
