# Being Awesome at GitHub

Find this document at https://github.com/utcsmad/github-workshop-f15

---

# Putting your code online

Pushing your code online lets teammates easily get a copy of what you've done.

In Terminal, navigate to your project. 
Run the following:

````
git push origin master
````

# What just happened?

_What did that line do?_

`git push` is used to "push" the changes you've made locally to the online repository (on GitHub). 

_What is origin?_

`git` needs to know which online repository to push to. By convention, git automatically creates this and names it 'origin' [when you ran git clone]() earlier.

Run `git remote --verbose` if you're curious.

_What is master?_

`master` is the name of the **branch** we pushed to. _What's a branch?_ We'll get to that in a bit.


## Go online and see what's changed

* Visit your GitHub repo. (ex: mine was https://github.com/nishanths/hacktx-project).
* You should see your new file and code if everything went right!