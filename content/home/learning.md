+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Learning"
subtitle = ""

# Order that this section will appear in.
weight = 30

+++

Here I am listing few materials that I utilized during my PhD. I have deep gratitude for people who develop Open-source softwares and those who provide knowledge for free, from [cooking hacks](https://www.youtube.com/channel/UCekQr9znsk2vWxBo3YiLq2w) to [app development](https://www.youtube.com/watch?v=5b91dFhZz0g) everything is just a Youtube search away.

Few basic tools required for bioinformatics research:

#### Programming
-----------------------------------------------------


 1. **R**

     When I started my PhD I started with languages that I thought will be enough: Perl, C, C++, English..(hah kidding). Within first two months I had to switch from PERL to R and I resisted heavily, but thanks to [StackOverflow](https://stackoverflow.com/tags) (and R tutorials ofcourse) the transition was easy. R <- didn't seem like a serious programming language in the beginning but later it became my goto language.

      - Ofcourse [R and R-studio](https://cran.r-project.org/) is an important requirement.
      - [Here](https://www.ebi.ac.uk/sites/ebi.ac.uk/files/content.ebi.ac.uk/materials/2013/131021_HTS/genesandgenomes.pdf) is an example of quick tutorial about R and genomics from EBI.
      - Getting well acquainted in the beginning with [Bioconductor](https://www.bioconductor.org/) packages saves a lot of time for biologists.
      - One of my favorites is to play around with [ggplots](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html). ggplots combined with [images](https://kohske.wordpress.com/2010/12/26/use-image-for-background-in-ggplot2/) were amazing to play with. - [Here](http://www.ggplot2-exts.org/gallery/) are some extensions of ggplots to play around. The [color palatte](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) I used mostly.
      - On a side note Reddit's [r/dataisbeautiful](https://www.reddit.com/r/dataisbeautiful/) is an amazing subreddit to explore and get ideas for Visualizations.
      - Small package big deal: [fread](https://www.rdocumentation.org/packages/data.table/versions/1.11.2/topics/fread) saves so much time, if working on large datasets.



2. **Python**

    Just beauty! I thank my short-term research stay at a university of Wurzburg in Germany, where I learned the basics from a passionate pythonista Dr. Konrad Forstner. In three-months or so, the first version of my python-based tool for DNA-motif search, [MoSEA](https://github.com/comprna/MoSEA) was born. The name literally means [first born](link:https://www.babynamespedia.com/meaning/Mosi/f], a unisex name) and the fact that it could expand to actually mean something (Motif Search and Enrichment Analysis) was just an icing on the cake.

    * Interactive tool for [basics](https://www.learnpython.org/) and [Code Fellows](https://codefellows.github.io/sea-python-401d4/index.html) for almost everything else.

    * Plots in Python: only in worst circumstances when somebody needs to render plots from python scripts, [Matplotlib](https://codefellows.github.io/sea-python-401d4/index.html)

    * Pandas: Just why? I don't even feel like adding a link for this one.

    * [SciPy libraries](https://www.scipy-lectures.org/): Bread and butter for scientific analysis.

    * [Scikit](http://scikit-learn.org) for Machine learning in Python. It is thorough and comprehensive but perhaps intimidating for beginners, I learned basics from one of the Python Meetups in Barcelona, I can't recall the name of the package unfortunately. However, there are many other cool packages with easy documentation.

    * The [Jupyter Notebook](http://jupyter.org/): It works with both R & python kernels. Good for documenting + executing code + rendering plots + creating pipelines + sharing & collaborating + parallel computing. One advice, start early on this.


3. **Editors**


    * [Atom](https://atom.io/): As if all geeks from different editors came together and finally acknowledged, we must stop the [war](https://en.wikipedia.org/wiki/Editor_war), we have an editor problem. Atom works like a charm for all operating systems, with embedded git control, supports almost ALL programming languages and required extending packages are open-source as well.

    * [Sublime](https://www.sublimetext.com/) text Editor : Most of my python coding was done on either Jupyter or Sublime. I prefer using Sublime perhaps because I started on it. But as Buddha said once, 'emotional attachment is a crime, if you're a programmer'[1](https://imgur.com/a/RO0q5ab).

    * [Nano](https://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/) and [Gedit](https://wiki.gnome.org/Apps/Gedit), cute little editors like all purpose flour.



4. **Version control**

    * [Why use version control?](https://hackernoon.com/in-defense-of-version-control-f8d8a0d7e23f)
    * [Github/Bitbucket](https://jaxenter.com/github-gitlab-bitbucket-code-repo-138308.html) : Open source, enforcing the practice of version control, collaborative tool building, tracks changes, even hosting this [webpage](link) for free. What more can one ask for? ~~Veni~~ ~~vidi~~ ~~vici~~ Add commit push.
    * Learn how to write with [Markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) and [Latex](https://www.latex-project.org/). Honestly, I lazied out for Latex but it's a one time learning thing and it stays with you forever.



5. **Database Development**

    I learnt database development using [LAMP](https://en.wikipedia.org/wiki/LAMP_(software_bundle)([XAMPP](https://www.apachefriends.org/download.html) for Windows) Apache webservers. The knowledge comes in handy to play around ororganize and store your work..or work professionaly.
    LAMP uses MySQL (or NOSQL) as relational Database system and traditionally PHP as application programming language, but also PERL and Python. I only worked with PHP and CGI-PERL..back in the days when PERL was still a thing. For now, I am using [Hugo server](https://gohugo.io/getting-started/quick-start/) to develop this site, and I am amazed how swiftly it works.


    Here is for a quick start using LAMP servers.
    * [Install and start](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04)
    * Learn about [databases](https://www.codecademy.com/learn/learn-sql)
    * [Make a Website](https://projects.raspberrypi.org/en/projects/lamp-web-server-with-wordpress/5)
    * [HTML](https://www.w3schools.com/html/), [CSS](https://www.w3schools.com/css/), [Javascript](https://www.w3schools.com/html/html_scripts.asp) : All these seem unnecessary these days when there are 1000s of built in templates, unless your job is to make those templates) but it will make you notice the effort done behind a good website template..and a powerful skill when you need to customize.





6. **Others**

    * [AWK](https://www.cheatography.com/tme520/cheat-sheets/awk-english/pdf/), [GREP](http://www.ericagamet.com/wp-content/uploads/2016/04/Erica-Gamets-GREP-Cheat-Sheet.pdf) and [SED](https://haiboyugroup.github.io/pdf/misc/sed.pdf) are the Curly Larry and Moe of programming, old and funny. The more you dive in, more you are taken aback by their power. They can literally save you in situations like [these](https://twitter.com/EduEyras/status/772459387063504896) or screw you when you [least expect](https://twitter.com/lianafaye/status/89096490819133441). Funny.



### Biology
--------------------------------------------

  When we talk about biology, we talk about life. From dead virus to a living cancer cell to this whole ensemble of nervous system, bones and muscles working nonstop for one purpose only..'to survive'. This strong drive to survive, exactly how depicted in the movie [Life](https://www.imdb.com/title/tt5442430/) is fascinating and biology in a nutshell is to study this. [Here](https://www.youtube.com/watch?v=wENhHnJI1ys) is a map of different fields of biology and each tops another on how deeper biology can go.

  I graduated with Life Sciences (Zoology and Botany), then moved to molecular biology and then to bioinformatics. I continued with bioinformatics and genomics as my main field of interest. Later, I specialized in cancer genomics, RNA biology to be precise. In RNA biology, I studied a specific mechanism called 'alternative splicing' process which is described in detail under the section 'publication'.

  It is a difficult task to put resources about biology here in this small segment, an interesting mind game I like to play is to pick an organism and find out how they've tweaked themselves to survive and reproduce. One level up becomes to alter (theoretically) their internal or external environment and study the impact...well basically pretty much that's how biologists work anyways. [We all fix radios](https://www.cell.com/cancer-cell/pdf/S1535-6108(02)00133-2.pdf).

  1. Basic Biology
  [Khan Academy tutorials](https://www.khanacademy.org/science/biology) on Youtube is amazing.
  2. All about [Molecular Biology](https://www.ncbi.nlm.nih.gov/books/NBK21054/)
  3. Genes and Genetics
  [The Gene : An intimate History](https://www.goodreads.com/book/show/27276428-the-gene) by Siddharth Mukherjee is a good book to start.
  4. Followed by [Epigenetics](https://www.goodreads.com/book/show/12414734-the-epigenetics-revolution)
  5. Cancer Biology
  [The Emperor of All Maladies: A Biography of Cancer] https://en.wikipedia.org/wiki/The_Emperor_of_All_Maladies by Siddhartha Mukherjee is a good book to start with.
  As my thesis specializes in cancer biology, works of so many scientists all over the world enhanced my understanding, here are couple of papers that are always helpful. The Hallmarks of Cancer [1](https://www.cell.com/abstract/S0092-8674(00)81683-9) and [2](https://www.sciencedirect.com/science/article/pii/S0092867411001279) by Hanahan and Weinberg.
