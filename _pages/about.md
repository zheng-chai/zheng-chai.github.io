---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a CS Ph.D. candidate at [George Mason University](https://www2.gmu.edu/), where I am supervised by [Prof. Yue Cheng](https://cs.gmu.edu/~yuecheng/).

My research interests are distributed machine learning systems, federated learning, high-performance computing. Specifically, my current research focuses on using serverless computing to expedite the training of graph neural network (GNN) without compromising performance.

# Publications
## Preprint
1. [Distributed Graph Neural Network Training with Periodic Historical Embedding Synchronization](https://arxiv.org/pdf/2206.00057). **Zheng Chai**, Guangji Bai, Liang Zhao, Yue Cheng.  arXiv preprint arXiv:2206.00057 (2022)
2. [Towards Quantized Model Parallelism for Graph-Augmented MLPs Based on Gradient-Free ADMM framework](https://arxiv.org/pdf/2105.09837). Junxiang Wang, Hongyi Li, **Zheng Chai**, Yongchao Wang, Yue Cheng, Liang Zhao. arXiv preprint arXiv:2105.09837 (2021)
    
## Published
1. [Asynchronous federated learning for sensor data with concept drift](https://arxiv.org/pdf/2109.00151.pdf). Yujing Chen, **Zheng Chai**, Yue Cheng, Huzefa Rangwala. 2021 IEEE International Conference on Big Data (Big Data). 
2. [FedAT: A Communication-Efficient Federated Learning Method with Asynchronous Tiers under Non-IID Data](https://dl.acm.org/doi/pdf/10.1145/3458817.3476211). **Zheng Chai**, Yujing Chen, Ali Anwar, Liang Zhao, Yue Cheng, Huzefa Rangwala. The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC 2021).
3. [Toward Model Parallelism for Deep Neural Network basedon Gradient-free ADMM Framework.20th IEEE Internation](https://arxiv.org/pdf/2009.02868). Junxiang Wang, **Zheng Chai**, Yue Cheng, Liang Zhao. 20th IEEE International Conference on Data Mining (ICDM). IEEE, 2020.
4. [Federated Multi-task Hierarchical Attention Model forSensor Analytics](https://arxiv.org/pdf/1905.05142). Yujing Chen, Yue Ning, **Zheng Chai**, Huzefa Rangwala. In 2020 International Joint Conference on Neural Networks (IJCNN). IEEE, 2020.
5. [Tunable Subnetwork Splitting for Model-parallelism of Neural Network Training](https://arxiv.org/pdf/2009.04053). Junxiang Wang, **Zheng Chai**, Yue Cheng, Liang Zhao. Workshop on ”Beyond first-order methods in ML systems” of the 37 th International Conference on Machine Learning(PMLR). 2020.
6. [TiFL: A Tier-Based Federated Learning System](https://arxiv.org/pdf/2001.09249). **Zheng Chai**, Ahsan Ali, Syed Zawad, Stacey Truex, Ali Anwar, Nathalie Baracaldo, Yi Zhou, Heiko Ludwig, Feng Yan, Yue Cheng. In Proceedings of the 29th International Symposium on High-Performance Parallel and Distributed Computing(HPDC). ACM, 2020.
7. [Towards taming the resource and data heterogeneity in federated learning](https://www.usenix.org/system/files/opml19papers-chai.pdf). **Zheng Chai**,Hannan Fayyaz, Zeshan Fayyaz, Ali Anwar, Yi Zhou, Nathalie Baracaldo, Heiko Ludwig, Yue Cheng. Conference on Operational Machine Learning (OpML 19). USENIX, 2019.
8. [Characterizing co-located datacenter workloads: An alibaba case study](https://arxiv.org/pdf/1808.02919.pdf?roistat_visit=120946). Yue Cheng, **Zheng Chai**, Ali Anwar. Proceedings of the 9th Asia-Pacific Workshop on Systems (APSys). ACM, 2018.

<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->

<!-- A data-driven personal website
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
