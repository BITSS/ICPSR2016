# ICPSR Transparency & Reproducibility Training
by [Garret Christensen](http://www.ocf.berkeley.edu/~garret),
UC Berkeley ([Berkeley Initative for Transparency in the Social Sciences](http://www.bitss.org) & [Berkeley Institute for Data Science](http://bids.berkeley.edu))

## Contents:
## Workshop Agenda
## Materials description
## Installation Instructions
-------------------------------

### Agenda
#### Tuesday July 5

8:30 Breakfast

9:00 Introductions

9:30 Intro to Research Transparency

10:45-11:00 AM Break

11:00-12:30 Registration & Pre-Analysis Plans

12:30-1:30 Lunch

1:30-2:30 Reg & PAP Activity

2:30-3:45 Data Sharing and Replication

3:45-4:00 PM Break

4:00-5:00 Data Sharing & Replication Activity

#### Wednesday July 6

9:00-10:30 Version Control with Git & Github I

10:30-10:45 AM Break

10:45-12:30 Version Control with Git & Github II

12:30-1:30 Lunch

1:30-3:00 Dynamic Documents in Stata
1. Stata + LaTeX
2. Stata + markdoc

3:00-3:15 PM Break

3:15-5:00 Dynamic Document in R
3. R Markdown + knitr


-------------------------


### Materials for the July 2016 Reproducibility Training at ICPSR

The numbered files/directories will take you through the workshop in order.

First, 1-Transparency-Intro features a set of slides (Beamer/LaTeX slides rendered as PDF) that discuss the reproducibility crisis in the social sciences.

Second, 2-Reg-and-PAP  is an introduction to registration and pre-analysis plans, which contains a set of slides, as well as a README describing an activity.

Third, 3-DataSharing-and-Rep contains slides and a README regarding data sharing a replication.

Fourth, 4-Tools-Intro contains slides introducing software tools for reproducibility: specifically version control and dynamic documents.

5-GitDemo.md is a set of tasks to work through to learn Git & Github.

Sixth is a set of materials to learn dynamic documents in different languages:
>6-StataLaTeX shows a two-step method of combining Stata and LaTeX.

>6-StataMarkdoc shows a one-step method in Stata using the markdoc add-on. It's still under development.

>6-Rmarkdown shows a complete one-stop-shop of version-controlled one-click analysis and final paper in R Studio.

7-Frontier includes a wrap-up description of some of the cutting edge programs, activities, and resources available in the transparency world.

-----------

## Installation Instructions (If you plan to use your own machine)
The workshop will introduce you to two major sets of tools that can help you make your workflow more reproducible: version control and dynamic documents. It will be helpful if you could install the following software programs before coming to the workshop, but I can assist you with it if you have issues, and most software should be installed on Michigan machines.

### 1. Version Control with Git and the Github Desktop app

Version control is a powerful way to carefully track revisions to your documents as well as to manage collaboration. Git and Github Desktop are packaged together [here](https://desktop.github.com/). Git is the command line tool, and Github Desktop is a GUI version of the same tool. There are actually [a whole bunch of GUI apps](https://git-scm.com/downloads/guis) that can act as front ends, so you might find later that you prefer another, but we'll stick with Github Desktop for the demo.

##### Optional: Specifics for Specifics Platforms

Note that Github Desktop only works on Mac and Windows. If you're a Linux user, you might try one of [these](https://git-scm.com/download/gui/linux). Also if you're a Windows user, the command line tool that comes with Github Desktop is not the greatest, so you might want to download [this alternative](https://git-scm.com/download/win). If you've never used the command line before or any of this is confusing, don't worry about it and I'll try to clear it up at the workshop.  

### 2. Dynamic Documents with R/R Studio and Stata

Dynamic documents allow you to write just one file that contains both your analysis code and your output (i.e. your final paper) so you can easily and reproducibly manage your work. The next time you return to a figure or table after six months and think "Where on earth is the code that generated this?" it will be obvious.

##### A Two-Step Workflow with LaTeX
Learning LaTeX for document production is a pretty daunting task, but it's quite powerful. Depending how many LaTeX users are in class, I'll describe a two-click workflow with LaTeX plus Stata/R/any stats package. You can get LaTeX [here](https://latex-project.org/ftp.html). Note that it's a large download.

##### Dynamic Documents in Stata

First, Stata isn't free, but you can get a temporary copy for the workshop [here](https://umich.app.box.com/v/stata). If you have any trouble with that install, e-mail [ICPSR IT](icpsr-sp-techsupp@umich.edu).

Although far less well developed in Stata than in R, dynamic documents can be created using the Markdoc ado created by E.F. Haghish. To install, run the following commands in Stata:

```
ssc install markdoc

ssc install weaver

ssc install statax

```
You may also get some links about installing Pandoc and wkhtmltopdf. You need to install those as well.

If you have ever installed these before, run ```adoupdate``` to see if you need to update.

##### Dynamic Documents in R

[R](https://www.r-project.org/) is an open source statistical analysis tool, and [R Studio](https://www.rstudio.com/products/RStudio/) is a very nice centralized tool for managing code and viewing data and output all in one program. Please download both. (At the R link, pick a location near you to download; at the R Studio link, pick R Studio Desktop.)


### 3. A good text editor

Writing good code is facilitated by a good text editor. You can get away without one because you almost certainly already have a program on your computer that can save simple ASCII text files (Notepad for Windows, or TextEdit for Mac--but change the default from Rich Text to Plain Text) but modern text editors do syntax highlighting, auto-complete, and a bunch of other cool stuff for you. I suggest [Atom](http://atom.io).
