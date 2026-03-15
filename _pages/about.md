---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->



Hi, I’m Kai Yu, a Postdoctoral Researcher in the [Division of Computational Health Sciences](https://med.umn.edu/surgery/divisions/computational-health-sciences), [Department of Surgery](https://med.umn.edu/surgery), at the [University of Minnesota](https://twin-cities.umn.edu/). I work on multimodal AI for healthcare, with a focus on medical imaging, biomedical signal analysis, clinical natural language processing, and intelligent systems for clinical decision support.


## Work Experience

* **Apr. 2025 – Present:** **Postdoctoral Associate**  
  [Division of Computational Health Sciences, Department of Surgery, University of Minnesota, Minneapolis, MN, USA](https://med.umn.edu/surgery/divisions/computational-health-sciences)  
  Research on multimodal AI for healthcare, with a focus on medical imaging, clinical NLP, and foundation models for clinical decision support.

* **Apr. 2024 – Apr. 2025:** **Postdoctoral Researcher**  
  [Department of Radiology, University of Pennsylvania, Philadelphia, PA, USA](https://www.med.upenn.edu/cbica/)  
  Conducted research on AI methods for medical imaging and radiological data analysis, including image understanding, prediction, and clinical applications.

* **Sept. 2022 – Mar. 2024:** **Research Scientist & Innovation Lead**  
  [Institute of High Performance Computing (IHPC), A*STAR, Singapore](https://www.a-star.edu.sg/ihpc)  
  Led research and development on multimodal foundation models in ophthalmology and related medical domains, while collaborating with global technology partners to translate research into practical applications.

* **Aug. 2020 – Aug. 2022:** **Research Scientist**  
  [Children’s Hospital Zhejiang University School of Medicine, Hangzhou, China](https://en.zjuch.cn/)  
  Developed AI methods for screening and diagnosis of congenital heart disease using heart sound signals, ultrasound images and videos, and 3D CT data.

* **Jan. 2016 – Dec. 2019:** **Co-Founder, AI R&D Lead**  
  [Suzhou BigVision Medical Technology Co., Ltd., Suzhou, China](https://en.bigvisiontech.com/)  
  Led the development of AI algorithms for OCT and fundus imaging, including denoising, segmentation, classification, and report generation, and worked with partner hospitals on product development and medical device certification.


## Education
* **Ph.D. in Medical Image Processing and Analysis**, Soochow University, Suzhou, China, Sept. 2014 – Jun. 2020  
  Advisor: Prof. Xinjian Chen

* **B.S. in Electronic Information Engineering**, Zhejiang Sci-Tech University, Hangzhou, China, Sept. 2010 – Jun. 2014

<!--  -->
## Research Funding
* **2023–2026** — **Co-PI**, National Natural Science Foundation of China (**520K CNY**)  
  Study on visualization analysis and recognition of heart sound characteristics in congenital heart disease

* **2023–2025** — **Co-PI**, Science Translational & Applied Research (STAR) I Grant (**100K SGD**)  
  Embedding AI in detecting and classifying CT artifacts for initial quality and adequacy assessment

* **2022** — **PI**, AI3 Horizontal Technology Coordinating Offices Seed Fund 2022 (**300K SGD**, shortlisted)  
  Sparse-shot hierarchical entity graph learning for gigapixel digital pathology images

* **2022–2024** — **PI**, Natural Science Foundation of Zhejiang Province (**100K CNY**)  
  Key technology for quantitative retinal analysis of high myopia in children and teenagers based on dual-modality medical images

* **2022–2024** — **Co-PI**, Key Project of the Natural Science Foundation of Zhejiang Province (**1M CNY**)  
  Research and application of new technology for screening and diagnosis of congenital heart disease in newborns under the collaborative environment of edge cloud and chain

* **2022–2024** — **Co-PI**, Key Project of the Natural Science Foundation of Zhejiang Province (**100K CNY**)  
  Establishment and clinical study of a new AI-based ultrasound screening technology for congenital heart disease in newborns

<!--  -->
## Awards and Honors
* **2023** — Third Prize, Science and Technology Achievement Award, China Birth Defects Intervention Relief Foundation
* **2022** — Third Prize, Science and Technology Progress Award of Zhejiang Province
* **2020** — First Prize, CAAI Wu Wenjun Artificial Intelligence Science and Technology Award
* **2018** — National Scholarship for Doctoral Students
* **2018** — AI Challenger: Fundus Edema Lesion Automatic Segmentation Competition, 3rd place in the biweekly competition and 4th place in the final

<!-- 
## Highlight of Qualifications
* Extensive experience in medical signal and image processing (CT, PET, OCT, MRI, Heart Sounds, Echocardiography, etc.).
* Skilled in deep learning frameworks like Pytorch for medical imaging and equipped with advanced Python and C++ expertise, adept at addressing real-world clinical challenges.
* Research interests include Parameter-Efficient Learning, Federated Learning, Multimodal Foundation Models, and Large Language Models. -->

<!-- ## Skills
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->
