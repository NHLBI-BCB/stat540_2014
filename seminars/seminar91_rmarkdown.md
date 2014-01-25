Markdown and R Markdown
=======================

Getting Started
===============

Open RStudio, and install the *knitr* package.

```r
install.packages('knitr')
```

Markdown
========

Markdown is a simple plain text markup language for formatting
documents. It's usually rendered to HTML, which is easy to view in a
web browser or to publish on the web. It can be rendered to other
document formats as well using a tool such as [Pandoc][pandoc].

- GitHub's [Markdown Basics][basics] describes the Markdown format
- GitHub has a few extensions to the Markdown syntax, called
  [GitHub Flavored Markdown][gfm]
- Daring Fireball, the creator of Markdown, gives a more detailed
  description of the [Markdown syntax][df]

Markdown documents have the file extension *.md*. This is the
canonical file extension. *Don't get creative here.*

[basics]: https://help.github.com/articles/markdown-basics
[gfm]: https://help.github.com/articles/github-flavored-markdown
[df]: http://daringfireball.net/projects/markdown/syntax
[pandoc]: http://johnmacfarlane.net/pandoc/

Example Markdown documents
--------------------------

GitHub automatically renders Markdown files with the *.md* extension.
Select *Raw* to view the raw Markdown.

- [A simple example][simplemarkdown], including a mathematical formula in LaTeX
- [This document][thisdocument]
- Open RStudio, and select *RStudio File > New File > R Markdown*.
  Ignore or delete the chunks of R code, for now.
- Find one on the Internet
- Write one for yourself!

[simplemarkdown]: https://github.com/jennybc/2013-11_sfu/blob/master/simple-markdown.md
[thisdocument]: https://github.com/jennybc/stat540_2014/blob/master/seminars/seminar91_rmarkdown.md

Rendering a Markdown document
-----------------------------

### RStudio

Open a Markdown document in RStudio. Click the *Preview* button.

Whenever you have a Markdown or R Markdown file open in the editor,
the button bar of the editor will have special powers. Click on the
question mark `?` to display the *Markdown Quick Reference* in the
*Help* panel.

### R command line

```r
library(markdown)
markdownToHTML('README.md', 'README.html')
```

### Shell command line

On Mac OS, install the *markdown* program using [Homebrew](http://brew.sh).

```sh
brew install markdown
markdown README.md >README.html
```

R Markdown
==========

R Markdown intermingles documentation in Markdown format and chunks
of R code in fenced code blocks. When the R Markdown document is
*knit* (that is to say, compiled), the chunks of R code are run, and
the results, which can be text or figures, are inserted in the
rendered document. R Markdown documents have the file extension *.rmd*.

RStudio has some nice documentation on R Markdown.

- [Using R Markdown with RStudio][rstudiomd]
- [Equations in R Markdown][equations]

[rstudiomd]: http://www.rstudio.com/ide/docs/authoring/using_markdown
[equations]: http://www.rstudio.com/ide/docs/authoring/using_markdown_equations

Example R Markdown documents
----------------------------

- [A simple example][simplermarkdown]
- Open RStudio, and select *RStudio File > New File > R Markdown*.

GitHub does not render R Markdown documents automatically,
sadly.

[simplermarkdown]: https://github.com/jennybc/2013-11_sfu/blob/master/simple-r-markdown.rmd

Rendering a R Markdown document
-------------------------------

### RStudio

Open a R Markdown document in RStudio. Click the *Knit HTML* button.

### R command line

The R function *knit2html* first calls *knit* to generate a Markdown
file and then *markdownToHTML* to generate a HTML file.

```r
library(knitr)
knit2html('simple-r-markdown.rmd')
```

Publishing a R Markdown document on RPubs
-----------------------------------------

RMarkdown documents can be published and shared on [RPubs][rpubs].

- Create an account on [RPubs][rpubs]
- Open the RMarkdown file in RStudio
- Click the *Knit HTML* butotn
- Click the *Publish* button

RPubs publishes the rendered document, but sadly does not also publish
the raw R Markdown code. The *rmd* file can be published on
[GitHub](github) or as a [GitHub gist](gist).

[rpubs]: http://rpubs.com
[github]: https://github.com
[gist]: https://gist.github.com