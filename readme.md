# uosThesisTitle

A latex package which provides a title page matching (and extending) the [example title](https://www.sheffield.ac.uk/polopoly_fs/1.463911!/file/Sample_thesis_title_page.pdf) page provided by the [Research & Innovation Services](https://www.sheffield.ac.uk/ris) of the [University of Sheffield](https://www.sheffield.ac.uk/).

## Warning

> Although usable this package is still under development and changes may/will break backwards compatibility

## Usage

1. Copy the `uosThesisTitle.sty` into a directory on your `TEXPATH` (i.e. the same directory as your `.tex` files)

2. Include the package in your preamble

    ```latex
    \usepackage[]{uosThesisTitle}
    ```

3. Input your title page details as required

    ```latex
    \universityLogoImage{path/to/logo}
    \title{Thesis Title}
    \subtitle{Optional Document Subtitle}
    \author{Authors Name}
    \supervisors{Supervisor Name(s)}
    \university{The University of Sheffield}
    \faculty{Faculty of ...}
    \department{Department of ...}
    \date{\today}
    ```

4. Include a call to `\maketitle`

### Package Options

Several options can be provided to the package to toggle certain features (i.e. `\usepackage[options]{uosThesisTitle}`).

+ `defaultMargins` - Do not set margins in the package to match the RIS example title page.
+ `showAuthorPrefix` - Show "By:" above the author.

Options such as the subtitle and list of supervisors are optional, and will not be displayed if set to an empty value.s

### Note

The University of Sheffield logo can be found on the University's Marketing team website > [Downloadable logos for use in print and on screen](https://www.sheffield.ac.uk/marketing/visual-identity/logos)

## Licence

See [LICENSE](LICENSE) file
