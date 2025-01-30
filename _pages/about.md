---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<p>
    I am a 👨‍💻 computer vision engineer with a 🎓 PhD in Image and Signal Processing from 🏛️ CEA Paris-Saclay, currently working at Capgemini Engineering in Paris.  
    My focus is on enabling computers to 👀 see and interpret our probabilistic world.  
    I have developed expertise in various areas, including computer vision, 🤖 machine learning,  
    deep learning, 🏞️ image and 📡 signal processing, uncertainty analysis, advanced statistics,  
    simulation, and 🔬 physics-based models.  
    I am particularly interested in applying these skills within the 🚗 automotive, ⚡ energy,  
    and 🏥 medical sectors, utilizing both embedded and ☁️ cloud platforms.
</p>
<p>
    In my last two years at Capgemini, I have worked on real-time perception for autonomous systems  
    as part of the 5G Open Road project and on developing Advanced Driver Assistance Systems (ADAS).  
    My work concentrates on 🔄 sensor fusion, 📡 LiDAR-camera data processing, and 🛠️ perception algorithms.
</p>

Current work
------
### 5G Open Road – Computer Vision and Perception Development

### Project Overview:

The [5G Open Road](http://5gopenroad.com/) project is a consortium initiative aimed at developing real-time perception systems for a World Model, leveraging 5G connectivity for connected and autonomous vehicle applications. The project involves multiple stakeholders, including Renault, Stellantis, and Valeo, and tests are conducted at various locations such as Vélizy, UTAC, Saclay, and École Polytechnique.

| Lidar detection  Vélizy | Camera detection at Saclay |
|---------|---------|
| ![Lidar](images/LidarDetection.gif){:width="500px"} | ![Camera](images/Saclay.png){:width="550px" height="50px"} |


My role was to lead the development of the **World Model**, ensuring accurate **object detection, tracking, and localization** through efficient sensor fusion algorithms. I worked on optimizing the system for **real-world deployment**, making it robust across various environments. We conducted extensive testing at **Velizy, UTAC, Saclay, and École Polytechnique**, where I played a key role in debugging and refining the system. Additionally, I managed **client interactions** with major stakeholders like **Renault, Stellantis, and Valeo**, ensuring their requirements were met.  My contributions also included **real-time debugging and system optimization**, which were critical during live deployments. You can know more work by me [here](https://sanjay-iisc.github.io/sanjay-SHARMA.github.io//portfolio/portfolio-3/) 

### CADMoS – Internal Project
------
As part of my work in **CaDMOS**, I fine-tuned a **dual-branch LANNET deep learning model** to enhance **lane detection accuracy** and enable **real-time lane number estimation** for autonomous driving applications. This involved optimizing the network for improved robustness across various road conditions. Additionally, I implemented a **stereo matching algorithm** for **stereo camera systems** on **NVIDIA Jetson AGX**, generating high-precision **disparity maps** for **depth estimation** in autonomous vehicle perception. This work contributed to improving the **spatial awareness** of the system, enhancing its ability to detect and interpret road structures in real time.

| LANE detection | Depth estimation| AGX |
|---------|---------|---------|
| ![Lidar](images/Lannet.gif){:width="500px"} | ![Camera](images/Depth_lannet.gif){:width="400px" height="50px"} |![AGX](images/IMG_0697.jpg){:width="200px" height="50px"}

Extra work (En chômage)
------
There was a four-month interval between the completion of my PhD and my commencement at Capgemini. During this time, I was engaged with a postdoctoral researcher at CEA-List in the **development of federated learning techniques, backdoor attacks and defense mechanisms using Robust Learning Rate (RLR)**. This work was applied to four datasets: German Traffic Sign, Fashion MNIST, EMNIST, and MNIST. 


| Before defense | After defense |
|---------|---------|
| ![RLRB](images/RLR_B.png) | ![RLRB](images/RLR_B.png) |


PhD work
------
I hold a Ph.D. in **Image and Signal Processing** from [CEA-LIST](https://list.cea.fr/fr/), [Université Paris-Saclay](https://www.google.com/search?client=ubuntu-sn&channel=fs&q=universit%C3%A9+paris+saclay), completed in October 2022. My [Ph.D. research](https://theses.hal.science/tel-04318941) focused on structural health monitoring, drawing parallels with human health monitoring. I used machine learning and statistical methods to improve defect detection in structures like airplanes and bridges.
![SHM - Structural Health Monitoring](images/SHM.png "Structural Health Monitoring"){: .align-center width="500px"}

My primary focus was on developing a **probability of detection (POD) curve**, which is a statistical method used to identify the minimum size of a defect that can be missed by an inspection algorithm while taking into account constraints on the limited availability of samples from the inspection structure. I achieved this by utilizing Bayesian probabilistic models to effectively evaluate and quantify performance differences across various use cases in terms of the POD curve. Additionally, I successfully conducted an experimental campaign involving thirteen aluminum plates to gather sufficient samples, along with a simulation study with uncertainty propagation, in order to provide a comprehensive convergence study and **decision making of "YES" or "NO" of presence of defect in the structure**. 

Furthermore, I implemented machine and deep learning models to predict performance based on experimental data, using classification and regression analysis on images reconstructed through imaging algorithms based on first principles. This work has contributed significantly to the advancement of guided wave SHM, and the corresponding paper is currently under writing.


| Four sensors time domain signals | Defect image reconstraction |
|---------|---------|
| ![SHM - Defect detection](images/ImageReco.png "Image reconstraction"){:width="700px"} | ![Experiment](images/experiment_dig.gif){:width="400px"} |

Lastly, I have also worked on developing a hybrid piezoelectric sensor model that utilizes the dynamics of the actuator to simulate higher frequency ultrasonic guided waves. This model serves as a computational tool for generating simulations to verify experimental results.

<!-- Currently, on weekends, we are actively collaborating on backdoor attack and defense strategies for the YOLO model, as well as working on a research paper. Please note that this experience is not included in my resume. -->


<!-- 





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
