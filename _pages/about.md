---
permalink: /
title: "Marion Walton"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an expert in digital research methods and instructional design who develops technological infrastructure and data literacy for Humanities researchers. I have 25 years of experience in teaching and research in Higher Education, with a special focus on curriculum development and student learning at both undergraduate and postgraduate levels.

My research focuses on developing methods, theories and ethical approaches to the study of digital, mobile and social media. I have collaborated with researchers on international research projects and published about the development of digital and mobile media in South Africa, with a particular focus on digital inequalities, research ethics, young people’s identities, literacies, and their creative and social agency.  

Over the past decade, my research and teaching in the Centre for Film and Media Studies have focused on training Humanities students in data analysis and coding skills. My current goal is to establish a curriculum and strong supportive infrastructure for the training of the next generation of researchers from the Humanities as they engage with computational methods, multimodal social media data and machine learning. 

My strength is in developing young researchers and helping scholars to use technology to accomplish key research goals. I have supervised 5 PhDs and over 20 MA students to completion. I have also played a leading role in research methodology training in the Centre for Film and Media Studies, developing courses in visual analysis, social network analysis and digital methods. As chair of the Humanities Faculty Research Ethics Committee I helped to update ethical approaches to social media data case studies and build expertise in ethical decision making around the use of social media data in the Faculty.

At the university level, I serve on the Advanced Computing Committee, where my priority has been to ensure equitable access to information technology within the Faculty of Humanities and to assist colleagues in developing their skills in accessing advanced computing resources. 

The groundwork for digital methods is laid at the undergraduate level, where I established courses in Multimedia Journalism and Interactive Media. These led to a joint degree in Digital Media and Informatics for Information Systems and Media Studies majors. Further curriculum projects have established numeracy and data skills in the second year curriculum, and a digital foundation introducing students to media and cultural studies in the first year.


Current project - Global South Ad Analysis
======

This umbrella project investigates a range of global and localised advertising and marketing campaigns which use social media to address audiences in South Africa in particular, and in the Global South more broadly. The goal of the project is to document online advertising and hold advertisers and platforms to account. identify the multimodal strategies of representation and localisation currently in use by commercial and non-profit organisations in relation to social and political issues in these regions (2018-2024) on Meta platforms and Twitter. This project explores the semiotic strategies used in geotargeted advertising and marketing campaigns addressing South African audiences (2018-2024) on Meta platforms and Twitter. Particular attention will be paid to advertisers’ choice to address social issues, elections or politics, and to identify trends in the dominant issues broached by advertisements which appeared in these categories, or which failed to appear with a disclaimer during the period under investigation.



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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
