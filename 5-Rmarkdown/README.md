**Dynamic Documents Introduction**

Garret Christensen 

Berkeley Initiative for Transparency in the Social Sciences/Berkeley Institute for Data Science

----------

This directory contains several files designed to familiarize you with the basics of dynamic documents. The most important files are:

1. RMarkdownExample.Rmd
2. StataSimple.do
3. TeXPaper.tex
4. WASHBpublic_mock.dta

RMarkdownExample.Rmd is an R Markdown file for use in R. When successfully run, it will load data (the WASHpublic_mock.dta file) and run three basic regressions. You can output these regressions as html or pdf. This output will take the name RMarkdownExample.html or RMarkdownExample.pdf.

StataSimple.do is a Stata do file that will load the WASHpublic_mock.dta file and will run the same regressions as above, only in Stata. The regression will output to a .tex file that can be used in LaTeX. (The regression output will also be output to a .txt file which could be used in Excel or any other spreadsheet program.)

TeXPaper.tex runs takes the output produced by both the Stata analysis file and the R Markdown file, and compiles it into a pdf. Although this is a two-step process (creating the table in R/Stata, and compiling it into the final paper in LaTeX) this does have the advantage of being able to access the full flexibility and power of LaTeX document processing. 