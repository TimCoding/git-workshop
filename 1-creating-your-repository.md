# Being Awesome at GitHub

Find this document at https://github.com/utcsmad/github-workshop-f15

---

# Starting a project

## Create an online repository

(At HackTX, just one person on the team should do this.)

* Visit https://github.com and sign in
* Then visit https://github.com/new
* Fill in the details
* Check "Initialize this repository with a README"
* Hit [Create repository]

## Adding files to your project

Do the following locally on your computer.

First we need to get the project from GitHub locally on to our machines:

* Open Terminal
* Get the url for the repo and run `git clone ..` as described [here]().


Let's add our first file:

* Open your favorite text editor (vim, Sublime Text, Notepad?)
* Add some lines of code (or anything you feel like).
* Save the file in the location where you downloaded the repo to.

Back at the terminal, run this command to tell `git` to start **tracking** the file you just created:

````
git add -A
````

**Store** the changes you made:

````
git commit -m "<a message describing what you did>"
````
