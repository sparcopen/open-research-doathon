Exploring reproducible research tools
======

>**Can't code?**
>The (*) ideas in the 'Ideas for the do-athon' list below are especially for you!
> Or take your first steps into coding today: R might be a good place to start. [Note from Naomi - this is my very first Markdown document; if I can, you definitely can!]

##**Tools to try**

**Binder**
*"Have a repository full of Jupyter notebooks? With Binder, you can add a badge that opens those notebooks in an executable environment, making your code immediately reproducible by anyone, anywhere."*
Supports: JuPyter notebooks; requires that your data and code are on Github

+ Try it out: http://mybinder.org/
+ Background info and examples:
 + https://elifesciences.org/elife-news/toward-publishing-reproducible-computation-binder
 + http://ivory.idyll.org/blog/2016-mybinder.html
+ New to JuPyter notebooks? Learn more and make your own at http://jupyter.org/


**R-Shiny**
*"Turn your [R] analyses into interactive web applications. No HTML, CSS, or JavaScript knowledge required."*
Supports: R

+ Try it out at https://shiny.rstudio.com/
+ Discover the Shiny cheatsheet at https://www.rstudio.com/resources/cheatsheets/ and tutorial at http://shiny.rstudio.com/tutorial/
+ Turn your Shiny into a web app with http://www.shinyapps.io/
+ Export your R script into a notebook using Knitr https://yihui.name/knitr/

**Stencila**
*A document and sheets editor to bridge the gap between coders and clickers*
Note: it's in beta
Learn more: https://stenci.la/

**CodeOcean**
*"Code Ocean is a cloud-based executable research platform"*
Note: it's in beta, and not open source (or free above threshold usage)
Supports: C/C++, Fortran, Java, Julia, Lua, MATLAB, Octave, Perl, Python and R
Learn more: https://codeocean.com/learn/

**nteract**
*"nteract is a desktop application that allows you to develop rich documents that contain prose, executable code (in almost any language!), and images"*
Supports: multi-language, apparently [can you help fill this out?]
Try it out: https://nteract.io/

**SuperSet**
*SuperSet is a data analytics dashboard from Airbnb for Python users*
Supports: Python
Learn more: https://github.com/airbnb/superset and
https://medium.com/airbnb-engineering/caravel-airbnb-s-data-exploration-platform-15a72aa610e5#.xm99tzjc4
Try it out: http://airbnb.io/superset/installation.html

####Maintaining analysis scripts:
Warning: codespeak alert. If you're new to this, ask!
An essential part of ensuring your reproducible notebook persists is good dependency management. 

**Packrat** is a dependency management tool for R that enables reproducibility of an R script
Try it out: https://rstudio.github.io/packrat/

**pip + virtual env** are your friends for dependency management in Python
Read more: https://tech.knewton.com/blog/2015/09/best-practices-for-python-dependency-management/

**Nix** and **Guix** are package managers for Linux and other Unix programs
Try them out: https://nixos.org/nix/ and https://www.gnu.org/software/guix/ 

##**Some points to consider**
+ How easy is it to use?
+ What can I use it for?
+ Do I need to download anything?
+ Where is my data stored? 
 + Do I trust that?
 + Is there sufficient space?
 + Will my data be preserved?
 + Better still, can I link in data from a known repository?
+ Do I need to convert any of my research file types in order to use it? If so, is this easy?
+ Is my reproducible artefact sustainable?
 + Will my visualisation/webapp/notebook persist or are there dependencies that are likely to deprecate?
 + Should I plan for continuous integration? If so, what burden will this place on resources?
+ Is my reproducible artefact fit for publishing AND for reproducibility?
 + Can I create a snapshot to match the peer-reviewed version, for version of record, then freely build on that in a new version?
 + Is my data auditable? Is there a trail of meaningful version history for someone else to validate?
+ Can I track how popular my reproducible artefact is?
+ Would I use this to communicate my own research?
+ Would I like to explore research in my field deeper using this kind of interactive tool?
+ What other features would I like to see?
+ Are there others ways to do this?
 
##**Ideas for the do-athon**
+ Write a workflow for a typical life sciences and biomedical researcher to make their data reproducible using these tools
+ Write a blogpost about how you found using these tools (see 'Some points to consider' above) - did you need any help to use them? If so, what did you learn and how?
+ Convert some of your own data into reproducible data. Can you share it with the world?
+ (*) Tell your own story about how you process your data from collection to publication
+ (*) How could existing bioinformatics tools and processes feed into reproducible analysis workflows?

 + Bioinformatics tools list: http://bioinfotraining.bio.cam.ac.uk/postgraduate/services 
 + [your favourite list here]

+ (*) Add more resources to this document! Do you know of any other tools for reproducible analysis, biology data analysis and visualisation, data analysis notebooking, and/or data dependency management?

(*) No coding skills required

###**And once I've finished?**
Please submit your feedback on these tools via the do-athon github, by tweeting a link to your doc using #odd4r @npscience, or by email to innovation@elifesciences.org
 

> Written with [StackEdit](https://stackedit.io/).
