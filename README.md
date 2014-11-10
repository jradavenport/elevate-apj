elevate-apj
===========

##Working to elevate the readability and design of astronomy journal articles.


### The problem...
They design for most journal articles in astronomy is a two-column, highly condensed layout. This format makes efficient use of paper, which in turn reduces printing costs. The narrow columns are also easy to read/parse, like that of a newspaper. 

Nearly all journals are changing to an online-only form of publication. This raises two important issues:

1. The web versions of these articles are difficult to read, and so most people avoid them and use the PDF versions instead.
2. The PDF versions of the articles look great on paper, but are difficult to read on a computer screen due to their layout.

In effect journal articles are *not* becoming online-only, they're just outsourcing the printing job to their readers. **Paper is still the best medium to read astronomy journal articles today due to the article layout.**

![Old and Busted](old.png?raw=true)

### We can ~~fix~~ improve this!

By updating the layout of journal articles we hope to:

- increase use of web/PDF article versions on computers and tablet devices
- improve comprehension and scientific usefulness of articles themselves
- reduce use of paper, trees, ink, printer/photocopier maintenance...


To accomplish this we must:

- consider the screen size and shape of the devices people use.
- consider the human exerience with the article, top-to-bottom flow, avoiding unnecessary scrolling, etc.
- learn from the single-column layout/design of sites like medium.com, and just about every news website.
- make the PDF and web versions of articles as similar as possible.
- make figures/images, as well as tables, seamlessly integrated within the article.

### .astronomy6 Goals/Needs
- discuss and create a new design for journal articles
- hack together a really sloppy implementation of this design in LaTeX
- take the sources files for an article formatted with [emulateapj](http://hea-www.harvard.edu/~alexey/emulateapj/) (probably from the arXiv) and apply this new design
- (time/skill permitting) format the article for the web as well. 

I can sketch the design, but would love more people to discuss them with. Perhaps each person took a screenshot of an article or website they thought was a format inspiration? Design on a white board if possible

I can do some hacking in LaTeX, but other expertise/thoughts would be incredibly valuable. Should we start from the article class, or emulateapj package? This LaTeX design doesn't have to be robust, but the primary goal is to create a demo PDF that is more pleasing to read on a computer/tablet.

To do the web version I need people who have skills. Should we try to use Markdown and MathJax? Generate a Jekyll/CSS/somethingelse template? Brute force?


### Resources/Links
- http://www.paulolyslager.com/optimal-text-layout-line-length/