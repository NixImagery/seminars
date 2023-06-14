---
title: "How to set up a free website"
subtitle: "A seminar for PGR students"
author: Nick Hood
keywords: 
    - PGR
    - communicate
    - website
    - community
bibliography: website-seminar.bib
csl: styles/chicago-author-date-with-ibid.csl
date: 15th June 2023 at 11:00 a.m. # \today
venue: Room 2.03, Charteris Land
toc: true
toc-depth: 2
documentclass: scrartcl
# header-includes:
#   - \usepackage{draftwatermark}
lang: en-GB
pagestyle: empty
papersize: a4
fontsize: 10pt
geometry: margin=1.5cm #, bindingoffset=0cm
fontfamily: roboto
fontfamilyoptions: sfdefault, light
link-citations: yes
colorlinks: true
linkcolor: MidnightBlue
urlcolor: RoyalPurple
toccolor: MidnightBlue
# 
# usage
# 
# $ pandoc -o website-claude.pdf website-claude.md
# $ pandoc -o website-claude.pdf --citeproc website-claude.md
# $ pandoc -o website-claude.pdf --citeproc website-claude.md --filter mermaid-filter
# $ Rscript -e "rmarkdown::render('website-claude.Rmd')"
---
<!-- \SetWatermarkText{draft copy} -->
\newpage

# Resources

Seminar files are available at [github.com/NixImagery/seminars](https://github.com/NixImagery/seminars). This is a github repository used to store and manage documents and code. There are two other github repositories that might be useful to you, which are small working examples for [mkdocs]((https://github.com/NixImagery/SWE-mkdocs)) and [bookdown]((https://github.com/NixImagery/SWE-bookdown)) websites. Download these to get a starting point for your own site.

# Introduction (5 minutes)

## Statement of assumptions

* you have brought a laptop and possibly your lunch
* you are interested in being able to make a website
* you haven't got money to throw at it
* you haven't got time to go on a course on python (or whatever)...
* ... but you can google and install software if you need to
* your website needs to be public
* you will leave once you have what you need (suggested exit points will be signposted)

## Outline of seminar

<!-- - What you will cover -->
* [Introduction (5 minutes)]
* [Choosing a platform (10 minutes)]
* [Making a site (40 minutes)]
<!-- * [Enhancing and maintaining your digital profile (10 minutes)] -->
* [Choosing the right solution (5 minutes)]
* [Questions and Answers (30 minutes)]

## Rationale

Having a professional website can help in sharing research, networking, and career opportunities. 

Key options we will be looking at in this seminar: 

* [Google Sites]
* [Substack]
* [GitHub Pages]
* [Bookdown] (for quant/data)
* static site generators like [mkdocs]

\newpage
# Choosing a platform (10 minutes)

## WYSIWYG

* WordPress (easy to use but can pressure you into paid upgrades and extras) 
* Wix and Weebly (very simple but limited customization and locked into their systems)

> "Google Sites and Substack are both great options for PhD students to quickly set up an academic website or digital presence." -- Claude [@Claude], May 4th 2023

* [Google Sites] -- quick and dirty
* [Substack] -- quick and clean

Ask yourself how they make their money? If it's free, then "you are the product" [@serra1973], unless you can see how they make money. Importantly for the present purpose is how the content of your website is going to be exploited.

> "For getting PhD students started quickly with an online presence for their research, Google Sites and Substack are superior options to WordPress or even static site generators. They require almost no technical skills but provide flexible platforms to build an academic profile website or newsletter." -- Claude [@Claude], May 4th 2023

||
|:-:|
|First Exit Point|

## Static site generators

* Static site generators like [MkDocs], Hugo, etc. (powered by Markdown, fully customizable, no database required)
* [Bookdown], built on R Markdown, is for data-driven pages useful for visualisation and code sharing
* GitHub Pages (free, open source, can use a Markdown-based generator like [MkDocs])
* Note ease of use and time to set up ([Google sites] vs. [Bookdown], for example) - choose what suits your needs and skills

## Recommendation

> "For the PhD students, I would then recommend GitHub Pages or a static site generator like MkDocs as the next options, given their flexibility, full control, and lack of commercial interests." -- Claude [@Claude], May 4th 2023

Some key benefits of Markdown static sites include:

* Fast loading with no database (i.e. static -- cf. dynamic)
* Focus on content and minimalist design
* Easy to update - just edit Markdown files
* Fully open source and future proof

\newpage
# Making a site (40 minutes)

## WYSIWYG

Fastest set up using [Google sites] and [Substack]

- Walk through setting up a free Google Sites website or Substack 
- Using the [IDL Network], show how to choose a theme, add content like About and blog posts
- Discuss benefits of Substack as a personal newsletter to share research updates, etc.
- Mention these require no coding and can be set up in less than an hour

## Markdown and why

* The power and simplicity of John Gruber's [Markdown] (you don't need to learn \LaTeX)
* How I made this document and its beamer with [pandoc]
* How to do citations
* docx, websites and whatever with [pandoc] (second exit point)
* First principal of coding: back up your work.
* GitHub -- repository set up and examples from [Niximagery]

||
|:-:|
|Second Exit Point|

## Static site generators -- MkDocs

- Create a GitHub account and repository
- Install MkDocs and set up a basic configuration file
* Example [MkDocs] for pretty websites like [this one][1] (check out the source)
- Develop Markdown files for the content (show [VS Code])
- Building and previewing the site locally before deploying 
- Deploying the site to [GitHub pages] for publishing to the web

## Static site generators -- Bookdown

* Demonstrate Bookdown PhD site and data sources
* Markdown to [R Markdown][rmarkdown] and another IDE
* Using R to do work for you [^ex1]

[^ex1]: using examples of CLIL paper and PhD site

# Choosing the right solution (5 minutes) 
- Google Sites or Substack for a quick start, Bookdown for data-driven and technical focus, GitHub Pages for growth

# Questions and Answers (30 minutes)

## If time -- some technical tips

* The integrated development environment, or IDE
* Self-hosting and git pull

## If time -- enhancing and maintaining your digital profile

- Options like buying a custom domain name, using an email list, starting a newsletter
- Tips for posting new content, engaging readers, and keeping the site updated
- Use the site on CVs, email signatures, and academic networking profiles
- Creating a consistent profile across platforms, regular posting and sharing updates, using social media to extend reach
- Offer general tips and best practices, e.g. consistent profiles, regular social sharing, email newsletters, etc.
<!-- - For Bookdown sites, also cover interactive features, open data/code, community engagement
- Mention that Google Sites/Substack are great starters, but GitHub Pages provides a path for expansion as their needs and skills grow -->

# Claude and the development of this seminar

I was short of time to produce this seminar, so the structure was developed in part through a dialog I had on May 4th 2023[^dv] with Claude [@Claude], an AI assistant created by Anthropic[^asf] "to be helpful, harmless, and honest." Claude is powered by a technique called Constitutional AI [@Bowman2022] which aligns language models via natural language feedback. Claude's knowledge comes only from what it has been exposed to and learned based on public data sources and conversations. There are gaps and limitations in its knowledge and abilities but these can be taken into account through conversation.

Claude's first attempt was to use tools like WordPress, Wix or Weebly, which I suggested were very poor choices, given their monetisation pressures on users and complexity. Prompting for a response that included GitHub pages or Markdown solutions like mkdocs, Claude revised the outline, after these remorseful remarks:

> "You make an excellent point. GitHub Pages and MkDocs (or other static site generators) are much better options for academic websites than WordPress. I should not have focused so exclusively on WordPress in my initial responses."

> "You're right, my initial response was too heavily biased toward more commercial solutions. For PhD students building an academic presence, static site generators and GitHub Pages are much more appropriate platforms with no pressure to monetize or lock-in users. I appreciate the feedback to improve my knowledge and recommendations on this topic."

After a further challenges, the poor bot finally agreed that "Google Sites and Substack are both great options for PhD students to quickly set up an academic website or digital presence." The revised outline, now more in line with my own first outline sketch, was used to construct the seminar and this resource. I hope they are useful.

[^asf]: Anthropic, PBC, the creators of Claude, is an AI safety startup based in San Francisco, founded in 2021.

[^dv]: May the Fourth, aka "Star Wars day". "I find your lack of faith disturbing." -- Darth Vader [@starwarsIV]

# References

[1]: https://cullaloe.com/family/Bourne/1903-06-13-Norah-Brennan/
[Bookdown]: https://bookdown.org/yihui/bookdown/
[GitHub Pages]: https://pages.github.com/
[Google sites]: https://sites.google.com/
[IDL Network]: https://idlnetwork.substack.com/
[Markdown]: https://daringfireball.net/projects/markdown/syntax
[MkDocs]: https://www.mkdocs.org/
[Niximagery]: https://github.com/NixImagery
[pandoc]: https://pandoc.org/
[rmarkdown]: https://rmarkdown.rstudio.com/
[Substack]: https://substack.com/
[VS Code]: https://code.visualstudio.com/