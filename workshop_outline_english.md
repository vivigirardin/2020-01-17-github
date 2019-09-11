Writing and Publishing on the Web Together Using Github
========================

You may be familiar with GitHub as a plattform for software and code. But, did you know that:

* GitHub can also be used to work on text documents?
* GitHub enables collaboration on documents and software entirely through the web interface?
* you can create a simple webpage with a few clicks through GitHub?
* you don’t need any knowledge of the command-line version control tool `git` to do all this?

Also:

* Many researchers and developers in many different disciplines put their code and projects on GitHub – or its sister GitLab.
* You can find many useful – or just fun – projects here; e.g. for creating your personal website without having the hassle of finding a webhosting service and for no hosting cost [academicpages](https://github.com/academicpages/academicpages.github.io), or for making interactive presentations [reveal.js](https://github.com/hakimel/reveal.js/).
* You can also use GitHub for collaborating with your team and managing your projects!

This workshop will teach you how to do these things, and more. The workshop is aimed at researchers and tailored towards those with very little to no experience in the subjects taught. Experience with git or GitHub or similar programs/services is not necessary, but it doesn’t hurt either.

-------------

## Introduction

* What is GitHub?
* What is in it for Me?

## Sign up and Setup

* create a GitHub account
  * chose right setup
  * make an informed decision about which email address to use
  * make an informed decision about what information you want to share with GitHub
* create a repository called "historical-recipes"
* IMPORTANT:
  * Before clicking the "Create Repository" button, add a 'README.md' file
  * Address licenses - why they are important & useful (show https://choosealicense.com/)
* Tailor info about Open Science to local / national rules
  * [University of Oslo guidelines for research data and research software](https://www.uio.no/english/for-employees/support/research/research-data-management/)

## Backdrop

* Historical Recipes project (see [here](https://github.com/arockenberger/github_collab_workshop/blob/master/story.md))

## Add Files to a Repo

* Create a file called `ingredients.txt`
  * add one ingredient "eggs"
  * explain commit action
    * show a good commit message
    * add description; commit
* Edit `ingredients.txt` by adding butter, cream, chives; commit
	* Show diff
* Edit `ingredients.txt` by removing cream; commit
	* Show diff
* Create a file called `instructions.txt` and add:
	* scramble eggs
	* mince chives
	* melt butter
	* whisk in cream; commit

## Collaborate directly

### Group-work Setup
* Divide into groups of four
  * "project lead" \#1 gets yellow sticky note
  * \#1 repo will be used
  * \#2, \#3, \#4 close the window with their repo
  * \#1 add \#2, \#3, \#4 as collaborators
    * navigate to 'Settings' tab,
    * click 'Collaborators' in left panel
    * use GitHub username without @
  * \#2, \#3, \#4 check their email and accept invitation

### Making Changes to Repository  
* \#2 makes a change to repository
	* add *heat skillet to medium-low* to `instructions.txt`; ```commit```
  * \#1 click on commit message
	* \#1 add comment to commit (scroll down)
	* \#2 respond to comment

* \#1 convert `ingredients.txt` to `ingredients.md`
	* quick intro markdown
  * google "markdown cheat sheet"
	* convert into markdown list
	* add `* salt`
	* look at rendered version

### Explain Issues and Pull Request Principles

* \#4 submit an issue
	* "We need to convert `instructions.txt` to `instructions.md`"
	* \#1 check email

* \#3 submit an unrelated issue
	* "Change "chives" to "Allium schoenoprasum" as ingredient"
	* \#1 check notifications

* \#4 prepare a pull request to address issue #1
	* make branch
	* make changes
	* commit to new branch
	* submit pull request
	* add link to issue in pull-request
	* \#1 check email / notifications

* \#3 prepare a pull request to address issue #2
	* this time, do not start from a new branch
	* instead, commit to new branch when finished
	* also include a typo in the change (!)

* \#1 add comment to pull request, 'fix typo!'
	* \#3 check email / notifications

* \#3 fix typo, thus adding a commit to the pull-request

* \#1 merge pull-request

* Exercise: do another cycle of an issue by one, and a PR by the other, include comments and merge PR

## Prevent conflicts

* \#2 create branch with change
	* call branch collab
	* wait with the PR

* \#1 commit change on same line in same file in master (!) branch

* \#2 submit PR --> conflict
	* \#1 & \#2 communicate through 'code review'
	* \#1 resolve

* \#1 merge PR

## Collaborate by 'suggesting' changes

* no commit rights
* explain forking
* instructor makes new repo for biographies
* second instructor, demonstrate adding bio as PR
	* for the repo
	* add a new file in fork
	* find 'submit PR' button on forked repo
	* follow PR steps
* first instructor accept PR
* each participant: add a new file with two or three lines to describe yourself (can be made up), add as PR
* Exercise: in pairs
	* add issues to the other person's biography file
	* and/or add PR, comments to PR, fixes etc
	* discuss through Github
	* add 'OK to merge' when ready
* instructor merges
	* merge PRs and close issues
* update your fork with the changes from the repo you forked from
	* in the fork, click the 'compare' button (right)
	* switch the base
	* check changes
	* click 'pull request'
	* now it is OK to merge your own pull request

## Real world example

* look at <https://github.com/swcarpentry/make-novice/>
* issues and pull request, conversation
* e.g. <https://github.com/swcarpentry/make-novice/pull/43>

## Building a simple website using GitHub

* back to Historical Recipes repo
* add `index.md` with a few lines of text
* on the 'Settings' tab of the Github repo, enable find "Select a source below to enable GitHub Pages for this repository" and select 'master branch' from the pulldown
* find your webpage
* in `index.md`, add (markdown) links to `ingredients` and `instructions`
* Exercise: customise your recipe website

## Another demo: Norwegian Correspondences project website

* <https://arockenberger.github.io/NorKorr/>

## Example of the final result



------

## instructor notes

* Co-instructor is number 2
* Laptop switching between them, make second laptop look different
