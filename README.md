# Special Topics Git/GitHub Lab

## Objective

For this lab, you will learn a little more about using Git for version control, and using 
GitHub as your Git repository server.  Git can be used for versioning lots of things, not just 
software.  One of the fundamental advantages of Git over other VCS is its distributed nature. 
 You can maintain repositories in many ways and this lab will explore two popular options.

You will play two different roles, one being the role of maintainer of a private repository
(receiving pull requests to your repo, reviewing them and giving feedback, and eventually
 accepting the pull request).  This style is common amongst enterprises, as they don't want to 
 make their repositories public.
  
Your other role will be that of a contributor to someone else's public repo (my repo).  This 
style is common amongst open source projects, where a wide range of contributors is desirable 
and the whole point is to make the software publicly available.

## Getting Started:
- There will be two parts to this lab.  
  - The first part is for you to be a contributor to my "open source" project.  I will host an "interview" repo, and you will attempt to contribute your answers as a pull request.
  - The second part is for you to be a maintainer of a private repository.  You will create a  private repo where you host an interview, and you will ask interview questions to me.  Your interview should have at least 3 questions.  The questions can be anything reasonable (please nothing offensive or overly personal).  You will then add me as a collaborator to your repository and will review my responses.

## Part One: You as the Contributor
1. Part 1 of this lab involves you answering my interview questions.  I will send a link to my repo through BlackBoard.  You will answer the questions (formatting as I specify) and submit the answers as a pull request to my repo, following my instructions.

## Part Two: You as the Maintainer

1. First, you need to create an interview in a repo on GitHub:
    1. Once you've decided on your interview questions, you should create a subdirectory under the ``labs/`` directory called ``<username>-interview-lab`` where ``<username>`` is your CSCC username.  In that directory you should create an `Interview.md` markdown file.
        - [Markdown](https://daringfireball.net/projects/markdown/) is a standard syntax for marking up text with special characters to tell markdown renderers to render the text with special effects (like bold, italics, or font size). GitHub's markdown syntax is described [here](https://guides.github.com/features/mastering-markdown/), and you should use it as a reference to format your interview appropriately.  IntelliJ has markdown support, and when you push your markdown files to GitHub, it renders them appropriately so you can see what your users will see.  
        - Your interview should include instructions on how you want interviewees to include their responses (a couple examples could be inline as a list item, or by adding a separate ``<user>.md`` markdown file with a link in the ``Interview.md``).  
        - Whatever method you ask interviewees to respond _must_ involve updating your repo, and only updating your repo (no links to a SurveyMonkey, for example).
    1. When you're happy with your ``Interview.md`` you should use `git init` to make your `<username>-interview-lab` version controlled by Git, and then make an initial commit that includes your `Interview.md` markdown file.
    1. After you have committed your `Interview.md`, [upload your repository to GitHub](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line).
1. With your repository uploaded to GitHub, add me (`jschmersal-cscc`) [as a collaborator](https://help.github.com/en/articles/inviting-collaborators-to-a-personal-repository), and send me an email (`jschmersal1@cscc.edu`) asking me to fill out your interview.  I will submit my interview answers as a [pull request](https://help.github.com/articles/creating-a-pull-request/).
    - You _must_ review my pull request, and suggest at least one change be made (it can be a grammar fix, formatting fix, asking for more info, etc.).  Your suggestion needs to be made as part of the pull request workflow, not as a separate email.  This will give you an idea of how pull requests work.  
    - When you are happy with ymy interview response, you should [merge my pull request](https://help.github.com/en/articles/merging-a-pull-request). 

## Submitting Your Work
For this lab, please submit in Blackboard links to the two pull requests after they have been
merged into their respective repositories.  Screenshots of each pull request dialog are also appreciated.

