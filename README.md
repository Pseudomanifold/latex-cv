# latex-cv: A minimal curriculum vitæ template

This repository contains a template for typesetting your curriculum vitæ
in LaTeX. I am using the template to typeset
[my](https://bastian.rieck.me) curriculum vitæ&nbsp;(which is also
available [here](https://bastian.rieck.me/about/cv.pdf)). Since it is
mostly geared towards an academic CV, this repository contains [an
example](CV.pdf).

If you find this template useful, I would love to hear about it. Drop me
a line using a communication channel of your choice.

Here is a list of users of the template:

- [Dr. Corey Stephan](https://github.com/historical-theology/cv) did
  a great extension of the template for the humanities.

## Using the template

Rename `CV.tex` to whatever you deem appropriate and edit the file.
Adjustable or otherwise configurable parts have been marked with a
`TODO`. Look at these things if you are interested in adjusting the
look and feel somewhat.

To check that everything is working, you should try to build the
template via:

    lualatex CV

Note that `lualatex` is strongly recommended here because it makes the
font selection a breeze.

## Requirements

The template currently uses the following fonts:

- Adobe Minion Pro (serif)
- Cabin Regular (sans serif)
- Fira Mono (monospace)

You can either select a different font in the preamble or install them
using your operating system's package manager.

## License

The template uses the MIT license. Please see the file
[`LICENSE.md`](LICENSE.md) in the main directory of the repository for
more details.

## Contributing

If you require additional features, find some bugs, or just have some
generic inquiries, please just open an issue in this repository.
