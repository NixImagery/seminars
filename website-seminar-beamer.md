---
title: "How to make a website"
subtitle: "from quick and easy to complex with data"
author: Nick Hood
institute: IETL, Moray House
bibliography: website-seminar.bib
csl: styles/chicago-author-date-with-ibid.csl
date: 15th June 2023 at 11:00 a.m. # \today
theme: Singapore
colortheme: sidebartab
# fonttheme: structuresmallcapsserif
# topic: "Pandoc how-to"
mainfont: "Roboto Light"
fontsize: 11pt
urlcolor: red
linkstyle: bold
aspectratio: 169
titlegraphic: images/UoE_EducationAndSport-letterhead-200.png
logo: images/UoE_EducationAndSport-logo-80.png
lang: en-GB
section-titles: false
toc: false
# 
# usage
# 
# $ pandoc -o website-seminar-beamer.pdf --citeproc -t beamer -s website-seminar-beamer.md
# $ pandoc -o website-seminar-beamer.pdf --citeproc -t beamer -s website-seminar-beamer.md --filter mermaid-filter
# 
---

# Introduction

## Resources

:::::{.columns}
:::{.column width="70%" }

Seminar files are available at [github.com/NixImagery/seminars](https://github.com/NixImagery/seminars). 

---
This is a github repository used to store and manage documents and code. There are two other github repositories that might be useful to you, which are small working examples for [mkdocs]((https://github.com/NixImagery/SWE-mkdocs)) and [bookdown]((https://github.com/NixImagery/SWE-bookdown)) websites. Download these to get a starting point for your own site.

:::

:::{.column width="30%"}

![](images/qrcode_github.com.png){width=150}

:::
:::::

## Getting started

:::::{.columns}
:::{.column width="50%" }

This one-hour seminar will show you some ways to set up a website for your project or personal profile using free resources. It is based on my own experience as a professional creator of web suites and communities, which I now use in my work at Moray House and as a part-time PhD researcher. There will be an additional half hour for Q & A at the end of the session.

:::

:::{.column}

We start with a quick statement of intent and assumptions for today with permission to leave once you have what you came for, and an invitation to stay for Q&A at the end.

:::
:::::

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
* [Introduction] (5 minutes)
* [Choosing a platform] (10 minutes)
* [Making a site] (40 minutes)
<!-- * [Enhancing and maintaining your digital profile (10 minutes)] -->
* [Next steps][Next steps and Q & A] (5 minutes)
* [Questions and Answers][Q & A] (30 minutes)

## Rationale

Having a professional website can help in sharing research, networking, and career opportunities. 

Key options we will be looking at in this seminar: 

* [Google Sites]
* [Substack]
* [GitHub Pages]
* [Bookdown] (for quant/data)
* static site generators like [mkdocs]

# Choosing a platform

## WYSIWYG

:::::{.columns}
:::{.column width="50%" }

* WordPress (easy to use but can pressure you into paid upgrades and extras) 
* Wix and Weebly (very simple but limited customization and locked into their systems)
* [Google Sites] -- quick and dirty
* [Substack] -- quick and clean

:::

:::{.column}

> "Google Sites and Substack are both great options for PhD students to quickly set up an academic website or digital presence." -- Claude [@Claude], May 4th 2023

:::
:::::

Ask yourself how they make their money? If it's free, then "you are the product" [@serra1973], unless you can see how they make money. Importantly for the present purpose is how the content of your website is going to be exploited.

## The quick start

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

# Making a site

## WYSIWYG examples

Fastest set up using [Google sites] and [Substack]

- Walk through setting up a free Google Sites website or Substack 
- Using the [IDL Network], show how to choose a theme, add content like About and blog posts
- Discuss benefits of Substack as a personal newsletter to share research updates, etc.
- Mention these require no coding and can be set up in less than an hour

## Markdown and why

* The power and simplicity of John Gruber's [Markdown] (you don't need to learn \LaTeX)
* How I made this document and its beamer with [pandoc]
* How to do citations
* docx, websites and whatever with [pandoc]

||
|:-:|
|Second Exit Point|

* First principal of coding: back up your work.
* GitHub -- repository set up and examples from [Niximagery]

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

# Next steps and Q & A

## Where do I start?

- Google Sites or Substack for a quick start, Bookdown for data-driven and technical focus, GitHub Pages for growth

## Q & A

## Q & A

||
|:-:|
|Third Exit Point|

# Extras

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

# Claude

## Claude and the development of this seminar I

I was short of time to produce this seminar, so the structure was developed in part through a dialog I had on May 4th 2023[^dv] with Claude [@Claude], an AI assistant created by Anthropic[^asf] "to be helpful, harmless, and honest." Claude is powered by a technique called Constitutional AI [@Bowman2022] which aligns language models via natural language feedback. Claude's knowledge comes only from what it has been exposed to and learned based on public data sources and conversations. There are gaps and limitations in its knowledge and abilities but these can be taken into account through conversation.

## Claude and the development of this seminar II

Claude's first attempt was to use tools like WordPress, Wix or Weebly, which I suggested were very poor choices, given their monetisation pressures on users and complexity. Prompting for a response that included GitHub pages or Markdown solutions like mkdocs, Claude revised the outline, after these remorseful remarks:

&nbsp;

> "You make an excellent point. GitHub Pages and MkDocs (or other static site generators) are much better options for academic websites than WordPress. I should not have focused so exclusively on WordPress in my initial responses."

more...

## Claude and the development of this seminar III

> "You're right, my initial response was too heavily biased toward more commercial solutions. For PhD students building an academic presence, static site generators and GitHub Pages are much more appropriate platforms with no pressure to monetize or lock-in users. I appreciate the feedback to improve my knowledge and recommendations on this topic."

After a further challenges, the poor bot finally agreed that "Google Sites and Substack are both great options for PhD students to quickly set up an academic website or digital presence." The revised outline, now more in line with my own first outline sketch, was used to construct the seminar and this resource. I hope they are useful.

[^asf]: Anthropic, PBC, the creators of Claude, is an AI safety startup based in San Francisco, founded in 2021.

[^dv]: May the Fourth, aka "Star Wars day". "I find your lack of faith disturbing." -- Darth Vader [@starwarsIV]

# References
## References

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