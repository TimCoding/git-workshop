# Being Awesome at GitHub

Find this document at https://github.com/utcsmad/github-workshop-f15

---

# Getting code your team wrote

First, you should [clone the repo]() using the <url> from the team member who made the repo.

Then, [add and commit]() any changes you made.


Run the following at the terminal to get the changes from online :

````
git fetch
````

Then, apply the changes to your local working copy:

````
git merge origin/master
````

# Dealing with merge conflicts

* Edit the file to change conflicting lines.
* Run `git add -A`
* Then run `git commit -m "<a short description of changes>"`