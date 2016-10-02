# icsme2016-presentation

This repository contains the LaTeX source code and additional resources for a presentation that I, [Colton
J. McCurdy](http://coltonmccurdy.com/) gave at the 32nd IEEE International Conference on Software Maintenance
and Evolution (ICSME 2016).  The presentation's source code uses a wide variety of LaTeX packages, such as `beamer` and
`pgftikz`, in order to create each slide.  I have developed a custom theme for the display of the slides and the use of
progressive revealing of technical diagrams.

You are welcome to use these slides as inspiration for your own presentation. If you find this example useful, could I
trouble you to star this repository and then acknowledge it in your own presentation slides?

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/mccurdyc/icsme2016-presentation.git
```

Then, if you want to compile the presentation to a PDF, you should type the following commands.

```shell
cd icsme2016-presentation
pdflatex icsme2016-mccurdyc.tex
pdflatex icsme2016-mccurdyc.tex
```

Please note that this has been tested on an Arch Linux 4.7.5 workstation running a very recent version of LaTeX that was
manually installed using the TeXLive installer. It is worth noting that you can also compile the paper using other LaTeX
development tools, such as `latexmk`. Additionally, you may find that the placement of certain `pgftikz` diagrams
requires manual adjustment depending on your LaTeX development environment and other settings. If you are unable to
compile the presentation with your development tools and your execution environment, then please open a new issue and I
will attempt to resolve your concerns.
