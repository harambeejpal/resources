# Resources (running list)
*Wim Louw*
🐦 
## 0. General Useful Things!
- **Getting organized**  
  - [Dropbox Paper](https://www.dropbox.com/paper). I find this great for weekly agendas, notes or quick reports
  - [Airtable](https://airtable.com/) "Part spreadsheet, part database, and entirely flexible". I use this to track grants, hiring new staff members, &c. It integrates with Zapier, [JotForm](https://www.jotform.com), and other services. It's more flexibile and powerful than Google Sheets.
  - [Trello](https://trello.com/), see also ["Find Work-Life Focus: A Trello Insider's Guide To Personal Productivity"](https://blog.trello.com/work-life-focus-trello-insider-guide-personal-productivity?hs_amp=true) and ["How To Become A Project Management Master With Trello"](https://blog.trello.com/project-management-power-ups). The [Gmail add-on](https://help.trello.com/article/1120-trello-for-gmail-add-on) is also useful
  - [Asana](https://asana.com/). See also the [Gmail add-on](https://asana.com/guide/help/api/gmail-add-on)
  - [Zapier](https://zapier.com/) “Connect Your Apps and Automate Workflows”, see also [IFTTT](https://ifttt.com/discover). I use this to automate repetitive tasks.
  - [Slack](https://slack.com/) "Where Work Happens". Useful for coordinating discussions and todos around themes/topics on a project with a large-ish team. I think Slack can very very distracting/scattered though.  
- **Email/comms** 
  - [MailChimp](https://mailchimp.com/)
  - Previously had Streak and Boomerang here, but just not sure about them anymore
  - ["How to ask good questions"](https://jvns.ca/blog/good-questions/) by *Julia Evans*
  - ["Do you have time for a quick chat?"](https://medium.com/@treycausey/do-you-have-time-for-a-quick-chat-c3f7e46de89d) by *Trey Causey*
- **SMS and phone interactions** 
  - [EnageSpark](https://www.engagespark.com/) (flexible)
  - See also [SMSPortal](http://www.smsportal.co.za/#!home) (more rigid)
  - Bulk airtime purchases on [myairtime.co.za](https://myairtime.co.za/) (allows spread-sheet upload) [South Africa]
  - Recently seen on Random Help: [Telerivet](https://telerivet.com/), and [Echo Mobile](https://www.echomobile.org/public/main) 
  - [flickswitch](https://www.flickswitch.co.za) to manage airtime on multiple devices 
- **Websites** 
  - [Google Sites](https://sites.google.com/) "Google Sites is a free and easy way to create and share webpages"
  - [Wix](https://www.wix.com) 
  - [Weebly](https://www.weebly.com) 
- **Surveys/data-collection**
  - [SurveyCTO](https://www.surveycto.com/)
  - And for coding advice on SCTO see the World Bank's Development Impact Evaluation (DIME) unit's set of resources [here](https://dimewiki.worldbank.org/wiki/SurveyCTO_Coding_Practices) 
  - Using Google Forms and R with the [googlesheets and googleformr packages](https://github.com/jennybc/googlesheets#what-the-hell-do-i-do-with-this)
  - [formr](https://formr.org)
  - [Ona](https://ona.io/home/) 
- **Misc**
  - ["Best Practices for Using Google Sheets in Your Data Project"](https://matthewlincoln.net/2018/03/26/best-practices-for-using-google-sheets-in-your-data-project.html) by *Matthew Lincoln*
  - [How to use Google Drive's version control](https://sites.google.com/site/scriptsexamples/home/announcements/named-versions-new-version-history-google-docs)
  - [Google's "Data studio"](https://marketingplatform.google.com/about/data-studio/)
  - [Octoparse](https://www.octoparse.com/) (webscraping, no programming required)
  - [OpenRefine](http://openrefine.org/) "A free, open source, powerful tool for working with messy data" (no programming required)
  - [Tables Generator](https://www.tablesgenerator.com) for creating simple Markdown and LaTeX tables interactively
  - [Google Dataset Search](https://toolbox.google.com/datasetsearch)
  - [Tableau (public)](https://public.tableau.com/en-us/s/) "Visualize and Share Your Data in Minutes—For Free"
  - [QGIS](http://www.qgis.org/en/site/) “A Free and Open Source Geographic Information System” 
  
----------
## 1. Programming 

**General advice** 
> Whichever programming language you choose to use, here is some great advice on general good practice, building on the idea of “reproducible research”
- ["Good enough practices in scientific computing"](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510). Minimum must dos, by *Greg Wilson*, *Jennifer Bryan*, and others
- ["Practical Data Science for Stats"](https://peerj.com/collections/50-practicaldatascistats/)

**General resources**
- [J-PAL "Software & Tools"](https://www.povertyactionlab.org/research-resources/software-and-tools)
- [IPA "Research Resources"](https://www.poverty-action.org/researchers/research-resources)
- Coming soon: J-PAL research resources, collection topic-specific articles 
- [Setting up a data science “stack" full instructions + resources](https://ubc-mds.github.io/resources_pages/installation_instructions/) from the University of British Columbia’s Master of Data Science program. Great set-up guide! (git, pandoc, LaTeX, Make, Docker, R, &c., &c.)
----------
**Programming with R**
- [Install base R](https://www.r-project.org/); then
- [Install RStudio UI](https://www.rstudio.com/products/rstudio/download/) (highly recommended) 
- Useful RStudio add-ons
  - [datapasta](https://github.com/MilesMcBain/datapasta)
  - [styler](https://github.com/r-lib/styler)
- Learn R in R with [Swirl](http://swirlstats.com/) 
- See the [RStudio Cheat Sheet, and others](https://www.rstudio.com/resources/cheatsheets/#ide)
- Read [R for data science](http://r4ds.had.co.nz/). Intro to the tidyverse and coding with dplyr and pipes %>% by *Garrett Grolemund* and *Hadley Wickham* 
- [The tidyverse style guide](http://style.tidyverse.org/) by *Hadley Wickham*
- ["Tidy Data"](https://vita.had.co.nz/papers/tidy-data.pdf) by *Hadley Wickham*
 
> I prefer the [tidyverse](https://www.tidyverse.org) approach to coding in R, but knowing base R is important  
- [An introduction to R](http://colinfay.me/intro-to-r/). Intro to base R
- [R Language Definition](https://cran.r-project.org/doc/manuals/r-release/R-lang.html#Introduction) by the R Core Team 
> For writing, sharing use R Markdown
- See [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/) by *Yihui Xie*, *J. J. Allaire*, and *Garrett Grolemund*
- [knitcitations](https://github.com/cboettig/knitcitations). Dynamic citations on R Markdown
- ["RMarkdown Driven Development"](https://emilyriederer.netlify.com/post/rmarkdown-driven-development/) by *Emily Riederer* 

**Dataviz in R**
- [Data Visualization for Social Science: A practical introduction with R and ggplot2](http://socviz.co/index.html) — Note: more general than just R
- See also [R Graphics “Cookbook”](http://www.cookbook-r.com/Graphs/)
- [BBC Visual and Data Journalism cookbook](https://bbc.github.io/rcookbook/)

**Trouble-shooting in R**
- Trouble-shooting: Join/search [Stackoverflow](https://stackoverflow.com/) 
- [The R Studio Community Page](https://community.rstudio.com/)
- Reproducible examples ("reprex"): ["So you’ve been asked to make a reprex"](https://www.jessemaegan.com/post/so-you-ve-been-asked-to-make-a-reprex/) by *Jesse Mostipak*
- ["How Do I?"](https://smach.github.io/R4JournalismBook/HowDoI.html)by *Sharon Machlish*

**Misc R**
- [Video resources](https://www.rstudio.com/resources/) from RStudio 
- [Rstats on twitter](https://twitter.com/hashtag/rstats) 
- [Jenny Bryan slides](https://speakerdeck.com/jennybc). Many useful things here
- ["Introduction to GIS with R: Spatial data with the sp and sf packages"](https://www.jessesadler.com/post/gis-with-r-intro/)

----------
**Git**
- ["Excuse me, do you have a moment to talk about version control?"](https://peerj.com/preprints/3159/) by *Jennifer Bryan*
- [Happy with Git (focus is on R here)](http://happygitwithr.com/) by *Jennifer Bryan*
- [Git in Practice](https://github.com/GitInPractice/GitInPractice#readme) by *Mike McQuaid*
- [Git troubleshooting](http://justinhileman.info/article/git-pretty/?utm_content=buffer125f2&utm_medium) 
- Git with a shared Dropbox folder, [see here](http://jetheis.com/blog/2013/02/17/using-dropbox-as-a-private-github/)
- GitHub [Learning Lab](https://lab.github.com/courses)
- [GitLab](https://about.gitlab.com)
- ["Setup Git RStudio GitLab"](https://gitlab.com/HeidiSeibold/setup-git-rstudio-gitlab) by *Heidi Seibold*

----------
**Python** 
- [The PySD Cookbook](https://pysd-cookbook.readthedocs.io/en/latest/index.html) "Simple recipes for powerful analysis of system dynamics models"
- [R Interface to Python](https://rstudio.github.io/reticulate/index.html)
- [Getting and Installing Python](https://ubc-mds.github.io/resources_pages/installation_instructions/#getting-and-installing-python)
- [Learning Python](https://docs.python.org/3/) 
  - See also [here](https://www.python.org/about/gettingstarted/)  
- Getting started with [Rodeo](http://rodeo.yhat.com/docs/) 
- [Statistics in Python](https://people.duke.edu/~ccc14/sta-663/IntroductionToPythonSolutions.html) 
- [Python graph gallery](https://python-graph-gallery.com/) 
- [Data analysis in Python](http://www.data-analysis-in-python.org/index.html)  
- ["Automate the Boring Stuff with Python"](http://automatetheboringstuff.com)

----------
**Stata**
- [World Bank's GitHub page](https://github.com/worldbank/stata/tree/master/docs)
  - [Ietoolkit](https://worldbank.github.io/ietoolkit/). Stata Commands for Impact Evaluations
  - [Stata-IE-Visual-Library](https://worldbank.github.io/Stata-IE-Visual-Library/)
- [IPA's GitHub page](https://github.com/PovertyAction)
- [Convert dynamic Markdown documents to HTML with dyndoc](https://www.stata.com/new-in-stata/markdown/)
- [Use Stata in Atom](https://atom.io/packages/language-stata)
- [Stata FAQ](https://www.stata.com/support/faqs/resources/statalist-faq/)
- [Stata Cheatsheets](https://geocenter.github.io/StataTraining/portfolio/01_resource/) 
- [Dictionary: Stata to R](https://github.com/EconometricsBySimulation/RStata/wiki/Dictionary:-Stata-to-R)
- [The Stata Lasso Page](https://statalasso.github.io/slides/)
- [reghdfe](http://scorreia.com/software/reghdfe/). Linear Models With Many Levels of Fixed Effects

----------
**LaTeX**
 - [The Not So Short
Introduction to LATEX 2ε](https://tobi.oetiker.ch/lshort/lshort.pdf) by *Tobias Oetiker*,
*Hubert Partl*, *Irene Hyna* and *Elisabeth Schlegl*
- Try [Overleaf](https://www.overleaf.com/blog/654-overleaf-v2-launch-announcement#.W6ku-GgzbIU) if you're working with collaborators 
- [Mathpix](https://mathpix.com) "Convert images to LaTeX"

----------

**Code Editors**
- [Visual Studio](https://visualstudio.microsoft.com/)
- [Atom](https://atom.io/)

----------
## 2. Fun  
- **Blogs**
  - [J-PAL newsfeed](https://www.povertyactionlab.org/news)
  - [VoxDev](https://voxdev.org/)
  - [Development Impact](http://blogs.worldbank.org/impactevaluations/)
  - [R-Bloggers](https://www.r-bloggers.com/)
  - [Yihui Xie's blog](https://yihui.name/en/)
  - [Running Randomized Evaluations](http://runningres.com/), Rachel Glennerster's blog 
- **Podcasts**
  - [Not so standard deviations](http://nssdeviations.com/) 
  - [Data Stories](http://datastori.es)
  - [Becoming a data-scientist podcast](https://www.becomingadatascientist.com/category/podcast/) 
  - [Linear Digressions](http://lineardigressions.com/)
  - [Credibly Curious](https://soundcloud.com/crediblycurious)

----------
## 3. Courses
- [Data Analysis for Social Scientists](https://www.edx.org/course/data-analysis-social-scientists-mitx-14-310x-2)
- [DSCI 521: Computing Platforms for Data Science](https://github.com/UBC-MDS/public/tree/master/courses/521_platforms)
- ["Chromebook Data Science - a free online data science program for anyone with a web browser."](https://simplystatistics.org/2018/10/01/chromebook-data-science-an-online-data-science-program-for-anyone-with-a-web-browser/)
- [CS50's Introduction to Computer Science](https://www.edx.org/course/cs50s-introduction-computer-science-harvardx-cs50x)
- ["Learning Statistics on Youtube”](https://www.r-bloggers.com/learning-statistics-on-youtube/) — various courses 
- [Machine learning](https://www.coursera.org/learn/machine-learning) — taught by *Andrew Ng*
- [Beginning Bayes in R](https://www.datacamp.com/courses/beginning-bayes-in-r?tap_a=5644-dce66f&tap_s=10907-287229)
- [Coursera data science specialization](https://www.coursera.org/specializations/jhu-data-science)

----------

## 4. Other (Uncategorized)

- [Declaring and diagnosing research designs](https://blogs.worldbank.org/impactevaluations/declaring-and-diagnosing-research-designs). See the [website](https://declaredesign.org/) "DeclareDesign is an R package full of tools to help researchers “declare” and “diagnose” designs before implementing them."
- Build regular expressions interactively with [RegEXr](https://regexr.com/)  
- ["Packaging data analytical work reproducibly using R (and friends)"](https://peerj.com/preprints/3192/) in *PeerJ Preprints*
- ["Prime Hints For Running A Data Project In R"](https://kkulma.github.io/2018-03-18-Prime-Hints-for-Running-a-data-project-in-R/) by *Kasia Kulma*
- ["Add a Generated Table of Contents Anywhere in R Markdown"](https://www.garrickadenbuie.com/blog/2018/02/28/add-a-generated-table-of-contents-anywhere-in-rmarkdown/) by *Garrick Aden-Buie*
- ["The Plain Person’s Guide to Plain Text Social Science"](https://kieranhealy.org/publications/plain-person-text/) by *Kieran Healy*
- ["Stata-style regression summaries"](https://gist.github.com/leeper/eef9682ec2118716eb8781303464a7e3) by *Thomas J. Leeper*
- ["Intro to set theory in R"](http://snip.ly/zxtnh#http://www.aaronschlegel.com/introduction-set-theory-r/)
- ["String Encoding in R"](https://kevinushey.github.io/blog/2018/02/21/string-encoding-and-r/)
- ["R syntax comparison" cheat sheet](http://www.science.smith.edu/~amcnamara/Syntax-cheatsheet.pdf)
- ["Vectors and lists"](https://jennybc.github.io/purrr-tutorial/bk00_vectors-and-lists.html#atomic_vectors) by *Jenny Bryan*
- ["15 Types of Regression you should know"](https://www.r-bloggers.com/15-types-of-regression-you-should-know/)
- [Reproducible Research with Stata using version control, GitHub, and MarkDoc](https://www.stata.com/meeting/switzerland16/slides/haghish-switzerland16.pdf) 
- ["Causal Models and Learning from Data Integrating Causal Modeling and Statistical Estimation"](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4077670/) by *Maya L. Petersen* and *Mark J. van der Laan*
- ["The workflowr R package: A framework for reproducible and collaborative data science"](https://jdblischak.github.io/workflowr/), slides [here](https://speakerdeck.com/jdblischak/the-workflowr-r-package-a-framework-for-reproducible-and-collaborative-data-science?slide=25) from John Blischak's useR! 2018 talk
- [Demystifying data science videos](https://www.thisismetis.com/demystifying-data-science-recordings) 
- ["Generating data to explore the myriad causal effects that can be estimated in observational data analysis"](https://www.rdatagen.net/post/generating-data-to-explore-the-myriad-causal-effects/)
- [Judea Pearl, Madelyn Glymour, Nicholas P. Jewell
"CAUSAL INFERENCE IN STATISTICS: A PRIMER", Chapter 4: "Counterfactuals and Their
Applications"](http://web.cs.ucla.edu/~kaoru/primer-ch4.pdf)
- [Hernán MA, Robins JM (2019). "Causal Inference". Boca Raton: Chapman & Hall/CRC, forthcoming.](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)
- [data.table and dplyr side-by-side](https://atrebas.github.io/post/2019-03-03-datatable-dplyr/)
- ["From Data to viz"](https://www.data-to-viz.com)
- ["All our ideas"](https://www.allourideas.org) --- to look into
- ["Empirica"](https://empirica.ly) --- to look into
- ["xaringan"](https://github.com/yihui/xaringan) --- alternative way of generating slides in R
- ["webshot"](https://github.com/wch/webshot) ---  "makes it easy to take screenshots of web pages from R"
- ["diffobj - Diffs for R Objects"](https://github.com/brodieG/diffobj) --- "Generate a colorized diff of two R objects for an intuitive visualization of their differences."

