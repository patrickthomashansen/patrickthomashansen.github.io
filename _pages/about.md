---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a machine learning and computer systems researcher. My research interests focus on the co-optimization of deep learning models and their target hardware platforms.

I finished my undergrad degree in Electrical Engineering and Computer Science in 2018. There I conducted research into low power neural network inference with the [Architecture, Circuits, and Compilers](https://vlsiarch.eecs.harvard.edu/) group. I was a Teaching Fellow for CS141: Computing Architecture.

Since graduating, I have been working as a research engineer for [Arm](https://www.arm.com/) in the Machine Learning and Perception group. Here, my research has focused on developing optimization techniques for computer vision models and investigating optimizations to their target platforms. Projects I have worked on at Arm range from utilizing neural architecture search to learn the structures for state of the art models, to developing novel architectures for hardware accelerators.


<!-- ----
I'm a CS PhD student at UC San Diego. I research the security and performance of complex systems. My advisor is Alex Snoeren and I'm a member of the SysNet Group.

I finished my undergrad degree in CS at Harvard in 2020. There I conducted research on serverless computing and browser security. I was a Teaching Fellow for the Systems Programming and Machine Organization class, and led the Harvard Political Review's tech team for two years.

Off campus, I served on the City of Cambridge's Open Data Review Board. I've also been a Research Intern at Google and a Software Engineering intern at Slack and Google.

You can contact me at aukani [at] ucsd (dot) edu.
----

I am a computer systems and architecture researcher. My research interests focus on improving the performance, efficiency, and environmental sustainability of computer systems and architecture by co-designing solutions across the computing stack.

My research optimizes the at-scale deployment of deep learning based personalized recommendation in order to enable next generation recommendation systems. Personalized recommendation is central to many Internet services we use on a daily basis including social media, search, video and movie streaming, and e-commerce platforms. Our work demonstrates that recommendation not only accounts for a majority of all AI cycles in data centers but also poses unique challenges to efficient execution that limits new modeling capabilities. Tackling these challenges we outline an in-depth analysis and characterization of the architectural implications of recommendation models across production data centers. Building on the characterization, we accelerate recommendation systems with  novel near memory processing systems, inference schedulers, and data center-scale specialized hardware for a wide set of neural recommendation models. Some of these solutions have been deployed in production data centers, demonstrating performance improvements at-scale. To enable future work into datacenter scale recommendation inference, we have open-sourced the proposed infrastructure, DeepRecSys and host the Personalized Recommendation Systems and Algorithms (PeRSonAl) workshop.

Given the growing demands for AI, emerging applications, and computing overall, I am also passionate about investigated new techniques to enable environmentally sustainable computing. We show that sustainable mobile and data-center scale computing requires reducing both operational energy consumption and embodied carbon from hardware manufacturing (Chasing Carbon). From a computing perspective this means we must rethink research and development across the computing stack (applications, systems, hardware, and devices) in order to build sustainable computer systems of the future. To this end, we host the Computing Landscapes for Environmental Accountability and Responsibility (CLEAR) workshop at ISCA 2021.

My past work has also included designing hardware accelerators for sparse RNNs, building and integrating a DNN accelerator into mobile SoC taped-out in 16nm, lossy compression techniques for DNNs, and quantifying the fault tolerance of DNNs.

I am an active steering committee member of the Computer Architecture Student Association, where I hope to build a more diverse and inclusive student community in computer architecture.

My work has received an IEEE MICRO Top Picks Honorable Mention (2020), as well as best paper nominations at the Parallel Architectures and Compilation Techniques (PACT 2019) and Design Automation Conference (DAC 2018).

I am a PhD student studying Computer Science in the Harvard Architecture, Circuits and Compilers group at Harvard University working with Professor David Brooks and Professor Gu-Yeon Wei. I have also been fortunate to collaborate with Facebook AI Research's (FAIR) SysML team where I am advised by Dr. Carole-Jean Wu. -->

<!-- 
This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
