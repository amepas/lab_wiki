# Lab Policies

blah

## Confidentiality

## External Collaborations

## Communication

# Lab Roles

## 2022-23 Academic Year Assignments

Birthday Chair: Andre
Wiki Chair: Andrea
Socials Chair: Constance
Cluster Chair: Abib
Food Chair: Cindy
YouTube Chair: Jenny
Twitter: Liyi and Daniel

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

## Writing Help

For support on writing, especially academic or scientific writing, Princeton has a great resource called the Writing Center which is here to support you by providing workshops and opportunities to get feedback on your writing. For more information, please visit their website: https://writing.princeton.edu/ 

## Learning

Continuously learning and staying up to date with the most recent advancements in the field is a must in a successful research lab. There are a number of different ways to learn, but one would be regularly reading recent papers (such as those posted on academic Twitter accounts listed below). 

If you feel you do not understand a particular paper or article, feel free to post about it in the Vertaix lab Slack workspace for a discussion with other lab members. 

## Academic Twitter

Please follow the Vertaix Twitter account at: https://twitter.com/Vertaix_.

Some additional Twitter accounts that would be good to follow are listed below. 

## Creating a Website

If you would like to create your own academic website, you can clone this repository: https://github.com/jonbarron/website

Once you have cloned it, feel free to add your own research projects and previous experience in your repository. Some additional sections you may want to add could include: Honors & Awards, Teaching, Leadership. 

To deploy the website, you may use GitHub Pages: https://docs.github.com/en/pages/quickstart

## Delivering Presentations

## Writing a CV

A Curriculum Vitae (CV) is a document that summarizes all of your prior academic and professional achievements. A LaTeX template for CVs can be found in this repository, titled "CV-Template.tex". You may also view the CVs of lab members linked from the Vertaix website for reference. 

## Conferences & Workshops

# Coding

This section describes all things related to coding within the lab. The Vertaix Github repository can be found here: https://github.com/vertaix

## Vertaix Cluster & Computing Resources

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

