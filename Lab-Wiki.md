# Lab Policies

## Confidentiality

## External Collaborations

## Communication

# Lab Process for projects

1. Start a GitHub repository: 
- Add the supervisor and collaborators on the project
- Update this repo with code and push to it as the project progresses
2. Start an Overleaf file:
- Share it with the supervisor and collaborators on the project
- Add the initial "project roadmap" to it: a set of todos to complete the project
3. Start a Slack channel:
- Add the supervisor and collaborators on the project
- Bookmark the GitHub repo and the Overleaf on the channel for easy access
- Keep the channel alive with discussions (questions, comments, link to a ref you find     interesting)

# Lab Roles

## 2022-23 Academic Year Assignments

Birthday Chair: Andre
Wiki Chair: Daniel
Socials Chair: Constance
Cluster Chair: Abib
Food Chair: Cindy
YouTube Chair: Jenny
Twitter: Liyi

## Birthday Chair

## Wiki Chair

This person is responsible for maintaining and updating the lab wiki (this document) throughout the year, and adding to it as needed. 

## Socials Chair

## Cluster Chair

## Food Chair

## YouTube Chair

## Twitter Chair

# Thriving in Graduate School

These topics are generally related to how to have a great graduate school experience. 

## Mental Health & Self-Care

Maintaining a work-life balance is essential to having a positive graduate school experience. Though research and classes can get busy, always remember to leave some time for other activities you enjoy and that help to keep you happy and healthy. Also, remember to form a community of peers that will be with you throughout the ups and downs of your graduate program!

If you do experience mental health concerns and want to seek additional help, Princeton has a great, free counseling service for students (CPS). You can find details here: https://uhs.princeton.edu/counseling-psychological-services

Appointments may be scheduled via your MyUHS portal, under the "Appointments" tab. This counseling service is great for any short-term concerns, such as stress/anxiety, imposter syndrome, social life and relationships, etc. They also offer many group counseling sessions, which can be a great way to connect with others who share some aspects of your identity or experience and gain support together. 

For longer term therapy and off-campus providers, CPS can provide referrals to therapists that accept your Student Health Plan. 

## Community

Forming a strong, diverse network at Princeton and beyond is a very important step in your graduate career. Especially for researchers not at Princeton, but who work on things that also interest you, building a network can help you find new collaborators, formulate new reearch ideas, and help you get your foot in the door for opportunities after graduate school, including employment in industry and in faculty roles. 

One great tool for helping maintain a professional network is LinkedIn (https://www.linkedin.com/). LinkedIn is a professional platform where industry and academia professionals alike come together. It can be used to stay in touch with the work of others in your field, and can also be used as a unifying platform to stay in touch with professional connections. 

Forming a strong support network is also important during your time at Princeton. You can meet new people both within and outside Vertaix or the department by participating in social activities (such as those organized by the GSG and in the D-Bar in Old Graduate College) and joining clubs or teams centered around activities you enjoy (such as club swimming, climbing team, board games club). Graduate school doesn't have to make you feel isolated, so reach out to others and have some fun!

## Time Management & Productivity

Managing your time effectively is an important part of graduate school. It is important to stay on top of your work, whether in classes or research, and be able to make continuous progress towards your goals. It is especially important to be intentional about all this, because graduate school can often be a very unstructured environment and requires a large amount of self-motivation. 

Some tools/ideas you can take advantage of for productivity are the following:
- Using a planner to keep track of all your deadlines and goals. 
- The Pomodoro studying technique, which involves taking regular short breaks to help reduce burnout. A great tool that can be used as a timer is: https://pomofocus.io/
- Using a calendar (digital or physical) to keep track of all meetings, conferences, classes, etc. 
- Ask a lot of questions! If you are stuck or don't understand something, your peers and lab mates are here to help. Don't waste too much time trying to figure everything out alone. 

# Resources

This section includes a number of helpful resources that you can use throughout your time at Princeton. 

## Writing
### Princeton Writing Center

For support on writing, especially academic or scientific writing, Princeton has a great resource called the Writing Center which is here to support you by providing workshops and opportunities to get feedback on your writing. For more information, please visit their website: https://writing.princeton.edu/

### Style guidelines for paper writing
This is a brief list of points to remember when writing scientific papers. They are guidelines, not hard rules; there will always be exceptions.

- Make sure bib entries are consistent and correct. preferred style is **[Author, Title, Venue, Year]** with optional **[Vol, Page]** if it is a journal.
- Bib entry for conferences is **@inproceedings** with just "International Conference on Blah" (drop the "Proceedings of the 8th Annual" junk)
- Bib entry for journals is **@article**. drop publisher garbage.
- Use **\citet** when referring to a paper as a noun.
- Order the citations appropriately (i.e. alphabetical or chronological depending on bibstyle)
- Equations are part of the sentence, so they always need punctuation after and never get a new paragraph
- Don't start a sentence with math. e.g. never say **"$\alpha$ is ..."**; instead, say **"The hyperparameter $\alpha$..."**
- Every symbol has a human-understandable name
- Don't break up a single equation into multiple lines. even try keeping inline symbols close: `hyperparameter~$\alpha$`
- Use cref (cleveref package)
- Period after parhead
- Consistent section header capitalization
- If you have 1 subsection, you must have 2
- Scrutinize all adjectives. imagine for instance:
    - adjectives cost $100
    - adverbs cost $500
    - weasel words cost $1000
- Don't subjectively describe related work; e.g. other work is not *"unnatural"* (this also is an unnecessary adjective). if you write it, think about why it's true, write that down, then delete the adjective because you've just explained it better than an adjective.
- same goes for saying you are the *"first"* to do something: that's a sort of extrinsic motivation. This is important because it solves a problem which is important, not because you did it before anyone else was able to do it.
- Ban "to the best of our knowledge" and its ilk
- Avoid things like "we note that" -- just say what you mean instead. this is a flag to restructure the sentence to say it clearly.
- Limit orphaned words at the end of a paragraph. i.e. try not to have just 1 or 2 words on their own line at the end of a paragraph (it does give you a nice randomized treatment of forcing you to say your point more concisely). apparently you can end a paragraph by doing `~\looseness=-1` and it will do this for you??
- Avoid using the word *"our"* like "our method" "our approach" --- it implies ownership and sounds like you're a kindergartener who can't share. often **"our"** can be replaced by **"the".**
- Avoid the phrase "real-world" when possible-- we argued over this a lot. Basically think of "real-world" as costing $10. may be necessary, but often it's spurious.
- Clearly articulate the contributions of the paper
- Make sure white space is beautiful on everything-- fonts, equations, etc. spurious white space looks ugly and conveys a poor paper
- No margin overflow on equations and figures
- Captions on figures should start with the punchline, not a detailed description of the figure: "Figure 1. The IRT and OSFT outperform other methods when controlling for FDR. red=IRT, blue=OSFT,...."
- Captions regarding results should have a short ending like **higher is better.**
- Figure fonts and font sizes should be consistent and beautiful
- Empirical studies should state clearly i) questions ii) data iii) methods iv) results in easy-to-find style
- Prefer *goodisms* to *bestisms.* You do not need to argue that your method is the best possible thing. it's a thing, and it's good, here's why.
- Easy-to-follow sentences put expected things at the beginning and new things at the end. "In addition to being model-agnostic, the method is also computationally efficient" >> "The method is also computationally efficient, in addition to being model-agnostic."
- You missed a reference. Always take a last chance to go over related work and find it.


## Learning

Continuously learning and staying up to date with the most recent advancements in the field is a must in a successful research lab. There are a number of different ways to learn, but one would be regularly reading recent papers (such as those posted on academic Twitter accounts listed below). 

If you feel you do not understand a particular paper or article, feel free to post about it in the Vertaix lab Slack workspace for a discussion with other lab members. 

## Academic Twitter

Please follow the [Vertaix Twitter](https://twitter.com/Vertaix_) account.

Some additional Twitter accounts that would be good to follow are listed below. 

## Creating a Website

If you would like to create your own academic website, you can use the template from Jon Barron's website. Once you have created/logged in your github accunt, you are encouraged to follow the steps below:

### Step 1: Fork the repository template
This action allows you to save the website template amidst your personal public repositories. While forking the template, you are allowed to enter your preferred repository name and an optional description for the website. It is advisable to attribute the name according to the following format **persweb**.github.io (Where **persweb** corresponds to the GitHub username used for the purpose of this tutorial). 

### Step 2: Make the website publishable 
The next step is making sure the website is publishable as a GitHub page. This is achieved by modifying the **Pages** subsection from the **Settings** sections.
Within the **Pages** subsections, adjusting the branch from **None** to **Master** will result in creating a live website directory from the master branch of the forked website template that had been created. Waiting a few minutes, a link to your personal website will be created. In our case, the following notice will be displayed: **Your site is live at** https://persweb.github.io/ 

### Step 3: Edit the website details
Upon completion of the previous step, the website is released as a GitHub page. Subsequently, one could apply some changes to the README.md file. Also, the website description and link can be added by **editing repositories details** from the **About section** of the forked template. Now, further changes can be made from the main branch of the source code in order to edit the content that will be displayed on the website.

### Step 4: Edit the source code
This is the step that might take longer to complete and thanks to this it is possible to customize the website according to one’s personal profile. Changes are applied by editing the code source from the **index.html** file. In addition to modifying the name and the biography to be displayed on the website, the template suggests adding a link to one’s email address, CV/Resume, Google Scholar profile, Twitter account, LinkedIn, Github, and/or a short bio. 
Prior to doing this, it is necessary to upload into the **data** and **images** folders, the CV/Resume as well as all the images that be displayed on the the website.
A typical academic website might be constituted of the following sections:  **News, Invited Talks, Research (Publications), Academic Services, Teaching and Outreach.** More sections can be added (or deleted) depending on the information one wants to be displayed on the website.
Although not mandatory, the **stylesheet.css** file can be edited as well according to the styles willing to be shown on the website. Additionally, the **mipnerf** and **mipnerf360** folders could also be exploited for style purposes.

### Step 5: Add a link to Jon Barron’s website
This is the last step to be done. It is not advisable to scrap the HTML code from the deployed instance at http://jonbarron.info. Using the GitHub code is sufficient for setting up your personal academic website.

### Step 6: Share your website 
You know that your academic website is ready to be published when you are completely satisfied with all the adjustments. Now you can share the link to your website with your network. 

## Delivering Presentations

## Writing a CV

A Curriculum Vitae (CV) is a document that summarizes all of your prior academic and professional achievements. A LaTeX template for CVs can be found in this repository, titled "CV-Template.tex". You may also view the CVs of lab members linked from the Vertaix website for reference. 

## Conferences & Workshops

## Computing ressources: A Practical Guide

This section describes all things related to coding within the lab. The Vertaix Github repository can be found here: https://github.com/vertaix
Computation often follows [cloud computing]([https://en.wikipedia.org/wiki/Cloud_computing]). At Princeton, we use the university’s machines to store and compute. We call these machines ‘computing clusters’. This tutorial discusses how to use the Ionic clusters provided by the computer science department.

### Framework
After getting started, a day-to-day procedure will typically look like:

1. ssh into the clusters
    - Type `ssh [uni]@cycles.cs.princeton.edu`
    - Type CS account password and duo factor as the window requests
2. Now you are in the clusters, to navigate to your disk space,
    - Type `cd ../../n/fs/[disk name]`
3. Treat this as your own folder. Clone GitHub repository, if needed:
    - Type `git clone [repo https]`
        - Here it prompts password. This is personal access token (accessible from GitHub website), not GitHub login password.
4. Run programs.

### Getting Started
#### Request Project Disk Space
This is achieved via the computer science website here : https://csguide.cs.princeton.edu/cs_request_forms_project
#### Install Anaconda 
1. The clusters use the Linux system. Here is the installation guide for Anaconda: https://conda.io/projects/conda/en/latest/user-guide/install/linux.html
2. This link will give you the Anaconda installer. Put the installer on the cluster*. Then, follow steps in the link above.
3. After Anaconda installation, add the path to conda into variable $PATH. To do this, type: echo 'export PATH=/path/to/anaconda3/bin:$PATH' >> ~/.bashrc
4. In case the cluster does not use bash by default, type: exec bash.
*: Since Anaconda is large (~5G), to put it on the cluster, an idea is to request a project space and put Anaconda (and installer) in there. Activities in other project disk spaces can also use this Anaconda.

#### Run a Program
Now the clusters are ready to use. We will often use slurm to run programs. To run one file:
1. Prepare a slurm file `job.slurm`
    - Guide on how to create a slurm script: https://researchcomputing.princeton.edu/support/knowledge-base/slurm
2. Navigate to the folder in cluster (following section 1).
3. Upload `job.slurm` to the folder in cluster (see section 3.2).
4. Type `sbatch -A vertaix job.slurm`. -A vertaix means using Vertaix machines. If not using Vertaix machines, remove ‘-A vertaix’.
5. However, replacing point 4 above, a better way is to do `python -A vertaix sweep.py`. The `sweep.py` file has a slurm script as a Python string inside, along with other functions that submit multiple slurm scripts with different hyperparameters. This way allows one to run many machines simultaneously. 
    - Guide on how to create something like the [`sweep.py`](http://sweep.py) script is to be finished…

### Other Relevant Things
#### Virtual Environment
To create, activate, and deactivate a conda virtual environment, type:

`conda create -n [envname] python**=**x.x anaconda`
`conda activate [envname]`
`conda deactivate`

#### Upload to and Download from the Clusters

This section outlines how to upload and download things from the cluster.

1. Prepare Terminal locally (not in the cluster)
2. Upload
    - File(s), type `scp path/to/my_file_1 ... path/to/my_file_n [uni]@cycles.cs.princeton.edu:/n/fs/[disk name]/path/to/`
        - The `path/to/my_file_i` are separated by a space each
    - Folder, type `scp -r path/to/my_folder/ [uni]@cycles.cs.princeton.edu:/n/fs/[disk name]/path/to/`
        - Now `my_folder/` and its contents are inside the folder `to/`. This command also creates `to/` if `to/` was not already there. 
3. Download, similarly: `scp -r [uni]@cycles.cs.princeton.edu:/n/fs/[disk name]/path/to/ path/to/`; `scp [uni]@cycles.cs.princeton.edu:/n/fs/[disk name]/path/to/my_file path/to/`

## Libraries

The Vertaix lab uses PyTorch for the majority of its machine learning computing needs. For a list of official PyTorch tutorials, please visit this page: https://pytorch.org/tutorials/ 

Instructions for installing PyTorch can be found here: https://pytorch.org/get-started/locally/ 

## Coding Guidelines

Below are some general best practices for coding, as well as established lab coding conventions, that you should follow as a member of the lab. 

### General Guidelines
- More descriptive names, less comments. 

Though comments can sometimes help (ex. Javadocs-style method headers) to understand what a complex chunk of code does, it is usually better to make code readable in other ways, such as using descriptive variable/method names. 

Comments can become outdated as the code base changes and evolves, and having old comments that no longer apply can lead to a lot of confusion. 

- Single Responsibility Principle. 

Every function, Jupyter notebook cell, or other “chunk” of code should do one conceptual “thing” and nothing else. This makes the same function both much simpler (and thus, easier to maintain and debug) as well as much more reusable (individual “steps” in a process are often much more reusable than the entire process). 

For example, if you want to read from a file, clean the data, perform some computations, and write out a cleaned dataset to a new file, these 4 steps should each be their own function. 

### Git Usage
- Create a new branch for every person working on a project, and for major changes, do pull requests instead of directly pushing to main. 

For example, if you have a project repository where you plan to work with 3 other collaborators, all of whom are doing different things, it can be really helpful to segment the work by person instead of working directly with the mainline branch (which can cause a lot of very messy merge conflicts). 

An additional benefit of pull requests is that others can review major changes before they are integrated with the repository. This can be especially important to help catch mistakes before merging if the repository is public and/or widely used. 

- Use "git rebase" instead of "git merge". 

Rebase is much more streamlined than "git merge" because it results in a commit history that looks linear, rather than messy and all over the place (which makes it difficult to revert to previous commits, or see the natural progression of a repository over time). As a side effect, this also helps avoid many common errors and conflicts that can occur when trying to maintain a multi-contributor repository. 

- Use "git commit -amend" instead of "git commit" if you are just making a minor change/fix to the most recent commit. 

For example, let's say you just made a big change and committed it, but then realized you left a few debugging print statements that you want to remove. Instead of creating a tiny commit just for that one change, simply running "git commit -amend" will allow you to include the change with the previous commit, to not clutter the git history too much. 

### PyTorch

