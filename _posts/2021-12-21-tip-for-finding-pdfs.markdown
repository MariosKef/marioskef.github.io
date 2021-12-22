---
layout: post
title:  "Tip for searching in PDFs"
date:   2021-12-21 13:00:00 +0200
categories: tools
---

While writing a current publication which happened to have a lot of literature search with overlapping ideas, I realized that it became quite hard to remember which publications dealt with a particular subtopic of my current research. For example, I tried to cite in my text a particular topic addressed by multiple publications. Say the topic regarded was _uncertainty estimation_.
In this case I realized that using a commandline utility called [pdfgrep](https://pdfgrep.org/) (also available for [Windows](https://soft.rubypdf.com/software/pdfgrep-windows-version)) helped a lot. I cd-ed to my directory of publications and simply ran `pdfgrep -r 'uncertainty estimation' .`
and voila got back a list of publications in which that phrase appeared. 


There are probably more sophisticated tools out there that are also able to find relevant topics to the search query, but I wanted to share this tool as it's simple and quick. Not only did this help me organize my work, but also my mind in order to know in the future which publications to look at if I want to refresh/revisit the topic.