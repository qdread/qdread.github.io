---
title: 'An uphill battle to open and reproducible science at USDA'
date: 2022-10-16
permalink: /posts/2022/10/open-reproducible-science-USDA/
tags:
  - open science
  - open data
  - reproducibility
  - USDA
---

Data and code need to be freely and publicly available for science to have its fullest impact. USDA is working on it but is still playing catch-up.

<!--break-->

For science to have any use, it has to be open science. A critical component of open science is reproducibility: that means making all data and code available that are needed to reproduce statistical analysis. Ideally, this would be done from day one, with intermediate outputs being made publicly available before an "official" publication. That is usually not feasible, so at the very least, analyses in a published manuscript need to be reproducible by other researchers. It isn't enough to put a glossy finished product out there and hope everyone else will take your word for it that the analyses underlying it are valid. And saying "code and data are available upon request" totally doesn't cut the mustard. Who knows what will happen to your email contact information in the future? And who will make sure you still have the data ready at hand in a well-organized, documented, and accessible format when someone asks you for it? 

The acronym [FAIR](https://www.go-fair.org/fair-principles/) is a list of principles to follow for scientific data and code to truly be open. FAIR stands for Findable, Accessible, Interoperable, and Reusable. These are useful guidelines for researchers when deciding how best to make their data and code available. *FAIR* stands for findable, accessible, interoperable, and reusable. Not worrying about the "interoperable" piece of it for now, data clearly needs to be put in a place where people can find it with a reasonable amount of effort, download it free of charge or other barriers, and put it to new uses.

## Making US government research open

I have been thinking about this for two reasons. First, the White House recently came out with a mandate to make all federally funded science immediately publicly available. A groan was heard from academic publishers everywhere. Nightmarish visions of fat 40% profit margins flying out the window appeared to executives at Wiley, Springer, and Elsevier. But making the science available does not just mean making the papers available. We also have to have all the code and data be available. Unfortunately, this is not as simple as it seems. Federal researchers work under a bunch of constraints. You cannot just throw stuff up on the cloud because there are (understandably) a lot of rules about data security. For instance, you have to guarantee that no data is stored on an overseas server. Obviously it is very commonplace for servers to be hosted on machinery that's physically located anywhere in the world. For that reason and others, a lot of things that academic scientists can do without thinking twice cannot be done by federal researchers.

## Disconnect 

Another problem, unfortunately, is that there is some disconnect between federal scientists and the administrators that run the agencies. Policies are often not clearly communicated. I recently experienced this when I completed an analysis in collaboration with a USDA scientist for a manuscript that was about to be submitted for publication. Being a good employee, I asked whether it was allowable to publish code and data associated with the analysis. I wanted to put it on a permanent online repository and give it a "DOI," or permanent link that anyone could use to access it and potentially reproduce our results on their own computer. These results have to do with using a technique called genomic selection in sugarcane. Genomic selection is a powerful tool for conventional breeding (basically the closest you can get to genetic engineering without actually modifying the DNA... a cross between traditional plant breeding methods and the new school). So it is something that could potentially be of interest to a lot of people. Unfortunately it wasn't that simple. There are a lot of restrictions. It is a little bit of a double bind because we are encouraged to share our science, but we run up against the restriction that some of the modern tools, that are now considered open science best practices, are not available to us because it takes a long time for the federal government to approve things. People are afraid, justifiably, of breaking the rules so they feel the easiest way out is just not to share the data. In the end, I did manage to publish the code as a supplement to the paper, but this is a subpar solution compared to putting it on an online repository where it is fully documented and can be accessed on its own without the paper.

## A possible path forward

Luckily, after asking around about it a little bit, I found out that some folks at USDA have already been working on this. The National Agricultural Library has its own in-house data repository called Ag Data Commons, which USDA researchers can use to submit data and code to a permanent, stable online repository. Currently, everything still has to be done manually, but in the near future it will be integrated with the code-sharing platform GitHub so that users can automatically release new versions of their code to the stable repository when it is updated. I am very happy that the NAL is doing this important work. I have started to use this platform for other projects I'm working on, and I'm very appreciative of the hard work folks at NAL are putting in to help format and document everything according to the FAIR principles.

Overall, I think that USDA has a way to go to catch up with other government agencies like [CDC](https://github.com/CDCgov), [NOAA](https://github.com/NOAAGov), and [USGS](https://github.com/usgs) that are doing a great job making their work available to the taxpayers that funded it, following the principles of open science. I'm hoping to help lead the effort to make USDA's science more open, now and in the future!
