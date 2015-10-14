# uosThesisTitle

A latex package which provides a title page matching (and extending) the [example title](https://www.sheffield.ac.uk/polopoly_fs/1.463911!/file/Sample_thesis_title_page.pdf) page provided by the [Research & Innovation Services](https://www.sheffield.ac.uk/ris) of the [University of Sheffield](https://www.sheffield.ac.uk/).

## Warning 

> Although usable this package is still under development and changes may/will break backwards compatibility for now (see `@todo` comments)

## Usage

1. Copy the `uosThesisTitle.sty` into a directory onto a directory on your `TEXPATH` (i.e. the same directory as your `.tex` files)

2. Include the package in your preamble
    ```
    \usepackage{uosThesisTitle}
    ```

3. Input your title page details as required
    ```
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

### Note

The University of Sheffield logo can be found on the University's Marketing team website > [Downloadable logos for use in print and on screen](https://www.sheffield.ac.uk/marketing/help-yourself/visual-identity/downloads/logos)

## @Todo

+ [ ] Provide correct comment in the head of the sty file
+ [ ] Correctly make parameters optional
    + [ ] By providing arguments to the package?
+ [ ] Improved documentation


## Licence

See [LICENSE](LICENSE) file
