# Github and Documentation
A practical guide for learning how to **use Github to document your open source project**, that is for learning how to **gitument**.

This guide provides you with a short introdution to the main elements that are necessary to start gitumenting/using Github as a documentation tool (that is documentation, Github, Markdown, the Readme and the Wiki page), as well as with hyperlinks redirecting you to useful webpages created by the Github team itself that will help you in your task. 

Our objective is twofold
- to convince you of documenting your project on Github
- to help you save as much time as possible in your "Gitumentation" learning process

We also plan to provide you with a concrete example of documentation on our wikipage. But the example is not avalable yet.

![Image one](Not-documented-not-done.png)

### Table of contents 

- [About](#about)

- [Introduction to documentation: THEORY](#introduction-to-documentation-theory)
    - [Why should I document my project?](#why-i-should-document-my-project)
    - [How difficult is it to document my project on Github?](#difficulty-of-documenting-on-github)
    
- [Introduction to documentation with Github: PRACTICE](#introduction-to-documentation-with-github-practice)
    - [Start using Github](#start-using-github)
    - [Start documenting your project on Github with your Readme and wiki pages](#start-documenting-your-project-on-github-with-your-readme-and-wiki-pages)
    - [Start using Markdown](#start-using-markdown)
    
- [Introduction to documentation: PRACTICE](#introduction-to-documentation-practice)
   
### About
Started in the SDG solution space in Geneva, we aim to provide potential makers with a guide as well as an example of how to use Github to document their projects and activities. New makers might indeed not be familiar with the notion of documentation, the tools available to that purpose and the way of using those tools efficiently. Well, this is exactly the reason this project has been designed for.

For those who have only few experience in documentation and who might feel anxious at the idea of using and struggling with Github: **no worries**. As a non-technical person, I already found myself in this situation, which consequently slowed down the progression of the project I needed to document at that time. 

By following this guide, you should be able to reduce substantially your *documentation learning time*, that is the hours you should spend to become aware of the importance of documentation (1), to look for an effective way to document your project (2) and to learn how to use a tool that allows you to do so (3).

This guide is divided in three parts: Introduction to documentation (theory), Introduction to Github/Markdown and a concrete example of documentation (see wikipage).

<p align="center">
  <img width="397" height="124" src="time-to-think.png">
</p>

## Introduction to documentation THEORY

### Why I should document my project
To answer this question, let me quote an inspiring webpage from [projectconnections.com](https://www.projectconnections.com/knowhow/burning-questions/what-is-project-documentation.html):

    When your business focuses on efficiency, cost minimization, and speed-to-market, creating lots of documentation can seem counterproductive. If the documentation doesn't directly support a deliverable, why do it? Project documentation covers documents created during and for the project itself. The documentation process has a deeper purpose than merely creating piles of paper.
    - Documentation *stimulates and structures critical thinking* in planning the project's goals, risks, and constraints. The document is the evidence and chronicle of this critical thinking.
    - It *provides memory containers* for managing a level of detail that cannot be kept in people's heads. This includes the small details easily overlooked during day-to-day project work, as well as the larger things easily remembered today, but potentially lost or forgotten due to the passage of time or critical personnel changes.
    - It *keeps the team and other stakeholders synced up and informed about project changes, issues, and progress.*
    
    In many projects, the documentation is often done late, done poorly, or not done at all—usually because the documentation is perceived as having little or no value. And, in fact, this is true if the documents are created as an afterthought or a necessary evil. Even documents with adequate content will lose value if they are created at the wrong time during the project, or aren't used in the project management process. Here are some examples:
    
    - Timing: If the project documentation is created at the wrong project stage, it may have little or no value, even if its content is quite good. **Examples**: a vision document created late in the project; a detailed schedule created before the stakeholders have agreed on an overall project vision.
    
    - Use: If the plan, vision, or risk analysis documents are created and then rarely or never referenced, they will likely have little or no value except for generating some initial critical thinking during their creation. **Examples**: a risk analysis that isn't referenced to measure progress on mitigations, or updated with newly discovered risks as they occur; a requirements document that isn't referenced later as a design completeness checklist.
    
    - Content: Inadequate or incomplete content decreases a document's value, even if it is created on time and used correctly. Examples: a status report for product development that doesn't track the product costs; a risk analysis that doesn't include risk mitigations.

### Difficulty of documenting on Github
Technical difficulties and obstacles may well make up one of the reasons preventing makers from documenting their project on Github. This is especially the case for those who, like me, have almost no technical or coding background. Some attention, efforts and time are therefore needed by some people to get used to Github and its "readme-language" called *[Markdown](https://en.wikipedia.org/wiki/Markdown)*. 

But this is no sufficient reason to make you abandon documentation. Github, thanks to some of its features (in particular to its version control system), is in fact a really good tool for documentation since it automatically records all the changes people have done as well as the steps they have taken during their projects. Soon after starting your github documentation, you'll realize how useful and beneficial it can be for you and your team.

## Introduction to documentation with Github PRACTICE

Why is Github even interesting for someone who'd like to document its project? 
Github, through its version control system, is indeed a more than relevant tool for keeping track of one's project and letting people (within *and* outside of your team) know about *what is and has been going on*: it automatically records all the changes that have been done and stores the steps that have been taken throughout any project that it hosts.

Github provides you with a [guide](https://guides.github.com) presenting you the main aspects of Github through many chapters. No need to read them all. You'll mainly be dealing with three of them: [**Hello world**](https://guides.github.com/activities/hello-world/), [**Documenting your project on Github**](https://guides.github.com/features/wikis/) and [**Mastering Markdown**](https://guides.github.com/features/mastering-markdown/)

<p align="center">
  <img width="275" height="183" src="time-to-start.png">
</p>

### Start using Github
  
#### 1) Sign up on Github:

>  [**Github.com**](https://github.com)

#### 2) Create your first repository:

> [**Hello world**](https://guides.github.com/activities/hello-world/), in its **step 1.**, will guide you on how to create your first [repository](https://help.github.com/en/articles/about-repositories):
>    1. Log in to your Github account and go to the main page of your account
>    2. Click on `Repositories` (next to "overview") and then, in the upper right corner, on the `green button "New"`
>    3. Name your repository `hello-world` and select `public`and `initialize it with a readme`
>    
>       *This is just a try, so let's name it "hello world". No need to write a short description. Make sure each time you create a new repository to **select "public repository" and "initialize it with a readme"*
>    4. Great, you've created your first repository!

#### 3) Create your Readme:

> If you followed step 3., Your README.md file was automaticly created and is now available for editing in your new repository.
    
### Start [Documenting your project on Github](https://guides.github.com/features/wikis/) with your Readme and Wiki pages
  
The guide [Documenting your project on Github](https://guides.github.com/features/wikis/) provided by Github is one of the most interesting for us; it clearly mentions the role of Github as a documentation tool as well as the tools Github provides you to achieve a good documentation, namely (1)the README (a first and overall presentation of your project) and (2) the WIKI page (the page where you'll be able to document your project and all your activities in detail)
 
    Good documentation is key to the success of any project. Making documentation accessible enables people to learn about a project; making it easy to update ensures that documentation stays relevant.
    Two common ways to document a project are README files and wikis:
        - README files are a quick and simple way for other users to learn more about your work.It’s a good idea to at least have a README on your project, because it’s the first thing many people will read when they first find your work.
        - Wikis on GitHub help you present in-depth information about your project in a useful way.

To edit your Readme and write down all this information, you'll have to start using Markdown and learning how it works (see next chapter). To accelerate this learning and editing process, I already designed a **template** for you:

#### 4) Create a second repository using the template:

> All you'll need to do to **[use this template](https://help.github.com/en/articles/creating-a-repository-from-a-template)** is 
>    1. Opening the repository of the template in just a [click](https://github.com/JonDavMartin/SummerSchool-projects-Template)
>    2. Clicking on the `green Use this template button` (near the top right corner)
>    3. Typing the name of your project as the name for your new repository and adding a small description of it
>       
>       *Make sure your to select `public repository` and `initialize it with a readme`*
>    4. Finally clicking on `Create repository from template`
>
>       *You should now possess a second repository on Github that is based on my template. You are now able to freely start documenting your project on Github on the basis of my template. You now just have to modify the code that is already existing according to your own project and documentation*

#### 5) Start formatting and editing a README:

Now, it is time to start gitumenting/documenting on Github by writing down the main information concerning your project in your Readme, that is:
- **the name of your project**: Your project’s name is the first thing people will see upon scrolling down to your README, and is included upon creation of your README file.
- **a description**: A description of your project follows. A good description is clear, short, and to the point. Describe the importance of your project, and what it does.
- **A table of Contents**: Optionally, include a table of contents in order to allow other people to quickly navigate especially long or detailed READMEs.
Please note that your Readme can serve as your first webpage/site for your project that Github will be hosting **for free** (I'll give you more information on this later on).

> In order to do that, just...
>   1. Go to the main page of your repository
>   2. Click on `Readme` and on the `edit button in the form of a pen` on the right of your screen (next to the "rubish button")
>   3. Start writing done your informations and text! 
>
>       *the template already gives you a basis to facilitate your start. Still, it is now time for you to start learning some simple Markdown language in order to carry on editing your Readme properly:
    
### 6) Start using Markdown

------ A FINIR -----

Documentation (Readme and Wiki pages) on Githbub is based on Markdown, also defined on Wikipedia as
> *a [lightweight markup language](https://en.wikipedia.org/wiki/Lightweight_markup_language) with plain text formatting syntax [...] with the goal of enabling people "to write using an easy-to-read and easy-to-write plain text format"* 

Github precisely provides us with a guide on how to use Markdown to start wrinting your readme/wiki page:

... [**Mastering Markdown**](https://guides.github.com/features/mastering-markdown/): this chapter shows you how to start using the Markdown language. It is a basic introduction. For more information and further learning, I'd recommend you to check out [this webpage](https://help.github.com/en/categories/writing-on-github).
 

## Introduction to documentation EXAMPLE

for the documentation of our small example-project, please have a look at our [wiki page](https://github.com/JonDavMartin/GITHUB-and-DOCUMENTATION-a-practical-guide/wiki)!
 
<!-- in case I want to indent sth: "&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;" --> 
