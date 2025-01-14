# Edinburgh LaTeX

[![Report CI](https://github.com/Foggalong/edinburgh-math-latex/actions/workflows/report-ci.yaml/badge.svg)](https://foggalong.github.io/edinburgh-math-latex/example-report.pdf) [![Beamer CI](https://github.com/Foggalong/edinburgh-math-latex/actions/workflows/beamer-ci.yaml/badge.svg)](https://foggalong.github.io/edinburgh-math-latex/example-presentation.pdf)

LaTeX stylesheets for the [School of Mathematics](https://www.maths.ed.ac.uk) at the [University of Edinburgh](https://www.ed.ac.uk/) in Scotland. This includes:

- [**`edmaths`**](edmaths.sty ) ([_documentation_](https://foggalong.github.io/edinburgh-math-latex/edmaths-docs.pdf), [_compiled example_](https://foggalong.github.io/edinburgh-math-latex/example-report.pdf))<br>
  A report and thesis stylesheet for easier compliance with the [university’s typesetting rules](https://www.ed.ac.uk/academic-services/students/thesis-submission).

- [**`beamertheme-edmaths`**](beamerthemeedmaths.sty), ([_documentation_](https://foggalong.github.io/edinburgh-math-latex/beamertheme-edmaths-docs.pdf), [_compiled example_](https://foggalong.github.io/edinburgh-math-latex/example-presentation.pdf))<br>
  A beamer presentation theme which follows the [university's brand guidelines](https://communications-marketing.ed.ac.uk/marketing/brand).

To use, download the files and store them either with your `.tex` file(s) or in any directory that's findable by LaTeX (e.g. `$TEXINPUTS`).

## Authors

While [Josh Fogg](https://github.com/Foggalong) maintains these versions, they would not have been possible without the work of:

- [Thomas Köppe](https://github.com/tkoeppe), wrote the original `edmaths` style file;
- [Saturnino Luz](https://www.ed.ac.uk/profile/saturnino-luz), created the [Beamer template](https://www.overleaf.com/latex/templates/usher-beamer-theme-new/pwjqsqkzhtsy) for the [Usher Institute](https://www.ed.ac.uk/usher);
- [Ben Brown](https://github.com/bencwbrown), modified the Beamer theme for general UoE usage.

Issues can be flagged [on GitHub](https://github.com/Foggalong/edinburgh-math-latex/issues) by [by email](mailto:j.fogg@ed.ac.uk).

## Licenses

The stylesheets [`edmaths.sty`](edmaths.sty) and [`beamerthemeedmaths.sty`](beamerthemeedmaths.sty) and their documentation are provided under the [LaTeX Project Public License v1.3c](https://choosealicense.com/licenses/lppl-1.3c/) (LPPL). The examples [`example-presentation.tex`](example-presentation.tex) and [`example-report.tex`](example-report.tex) are provided under the [BSD Zero Clause License](https://choosealicense.com/licenses/0bsd/) (0BSD). The images [`edinburgh-logo`](Images/edinburgh-logo.svg) and [`white-tied-in`](Images/white-tied-in.svg) are registered trademarks; they are not to be used as part of derived or independent works without the permission of The University of Edinburgh. This does not affect use as part of compiled LaTeX documents using this stylesheet for the university.
