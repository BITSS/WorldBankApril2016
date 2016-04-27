# World Bank Reproducibility Training
Materials for the April 2016 Reproducibility Training at the World Bank

## Installation Instructions
The workshop will introduce you to two major sets of tools that can help you make your workflow more reproducible: version control and dynamic documents. It will very helpful if you could install the following software programs before coming to the workshop

### 1. Version Control with Git and the Github Desktop app

Version control is a powerful way to carefully track revisions to your documents as well as to manage collaboration. Git and Github Desktop are packaged together [here](https://desktop.github.com/). Git is the command line tool, and Github Desktop is a GUI version of the same tool. There are actually [a whole bunch of GUI apps](https://git-scm.com/downloads/guis) that can act as front ends, so you might find later that you prefer another, but we'll stick with Github Desktop for the demo.

##### Optional: Specifics for Specifics Platforms

Note that Github Desktop works on Mac and Windows. If you're a Linux user, you might try one of [these](https://git-scm.com/download/gui/linux). Also if you're a Windows user, the command line tool that comes with Github Desktop might not be the greatest, so you might want to download [this alternative](https://git-scm.com/download/win). If you've never used the command line before or any of this is confusing, don't worry about it and I'll try to clear it up at the workshop.  

### 2. Dynamic Documents with R/R Studio and Stata

Dynamic documents allow you to write just one file that contains both your analysis code and your output (i.e. your final paper) so you can easily and reproducibly manage your work. The next time you return to a figure or table after six months and think "Where on earth is the code that generated this?" it will be obvious.

##### Dynamic Documents in R

[R](https://www.r-project.org/) is an open source statistical analysis tool, and [R Studio](https://www.rstudio.com/products/RStudio/) is a very nice centralized tool for managing code and viewing data and output all in one program. Please download both. (At the R link, pick a location near you to download; at the R Studio link, pick R Studio Desktop.)

##### Dynamic Documents in Stata

Although far less well developed in Stata than in R, dynamic documents can be created using the Markdoc ado created by E.F. Haghish. To install, run the following commands in Stata:
>ssc install markdoc

>ssc install weaver

>ssc install statax

You may also get some links about installing Pandoc and wkhtmltopdf. Please install those as well.

### 3. A good text editor

Writing good code is facilitated by a good text editor. You can get away without one because you almost certainly already have a program on your computer that can save simple ASCII text files (Notepad for Windows, or TextEdit for Mac--but change the default from Rich Text to Plain Text) but modern text editors do syntax highlighting, auto-complete, and a bunch of other cool stuff for you. I suggest [Atom](http://atom.io).
