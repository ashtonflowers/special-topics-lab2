# Special Topics Git/GitHub Lab

## Objective

For this lab, you will learn a little more about using Git for version control, and using GitHub as your Git repository server.  Git can be used for versioning lots of things, not just software.

You will play two different roles, one being the role of maintainer (receiving pull requests to your repo, reviewing them and giving feedback, and eventually accepting the pull request).  The other role will be that of a contributor to someone else's repo (your partner's, or my repo).

## Prerequisites

* Create a "labs" directory if you don't already have one by opening a terminal
and typing:
``mkdir ~/labs``

## Getting Started:
- For this lab you will need to work as a team, so pick a partner.  You can work with more than one partner, but at least one partner is required.
- There will be two parts to this lab.  The first part is for each team member to create an interview for your partners.  Your interview should have at least 3 questions.  The questions can be anything reasonable (please nothing offensive or overly personal - you should work with your partners to find something amenable to everyone if your partner would prefer not to answer one of your questions).

## Interviewing Partners

1. First, you need to create the interview:
    1. Once you've decided on your interview questions, you should create a subdirectory under the ``labs/`` directory called ``<username>-interview-lab`` where ``<username>`` is your CSCC username.  In that directory you should create an `Interview.md` markdown file.
        - [Markdown](https://daringfireball.net/projects/markdown/) is a standard syntax for marking up text with special characters to tell markdown renderers to render the text with special effects (like bold, italics, or font size). GitHub's markdown syntax is described [here](https://guides.github.com/features/mastering-markdown/), and you should use it as a reference to format your interview appropriately.  IntelliJ has markdown support, and when you push your markdown files to GitHub, it renders them appropriately so you can see what your users will see.  
        - Your interview should include instructions on how you want interviewees to include their responses (a couple examples could be inline as a list item, or by adding a separate ``<user>.md`` markdown file with a link in the ``Interview.md``).  
        - Whatever method you ask interviewees to respond _must_ involve updating your repo, and only updating your repo (no links to a SurveyMonkey, for example).
    1. When you're happy with your ``Interview.md`` you should use `git init` to make your `<username>-interview-lab` version controlled by Git, and then make an initial commit that includes your `Interview.md` markdown file.
    1. After you have committed your `Interview.md`, [upload your repository to GitHub](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line).
1. With your repository uploaded to GitHub, send a link to it to your partner, and ask your partner to fill out your interview.  Your partner should submit their interview answers as a  [pull request](https://help.github.com/articles/creating-a-pull-request/).
    - You _must_ review your partner's pull request, and suggest at least one change be made (it can be a grammar fix, formatting fix, asking for more info, etc.).  
    - When you are happy with your partner's interview response, you should [merge their pull request](https://help.github.com/en/articles/merging-a-pull-request). 
1.  Since you are doing this as a team, you will also be acting as an interviewee for your partner's interview question, so your roles will be reversed.  When your partner sends you their repo, you should submit your responses as a pull request for your partner to review.  Make the proposed changes and update the pull request.  Continue the process until your partner is happy and merges your pull request.

## Answering my interview questions
1. Part 2 of this lab involves you answering my interview questions.  I will send a link to my repo through BlackBoard.  You will answer the questions (formatting as I specify) and submit the answers as a pull request to my repo.  

## Submitting Your Work
For part one of this lab, please e-mail me links to all partners' repos.  I will review your repos and pull requests to ensure you performed the steps outlined above.

For part two, you are finished when I have merged your pull request into my repo.

