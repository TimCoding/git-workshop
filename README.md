# Being Awesome at GitHub and Git

* Find this document: https://github.com/utcsmad/github-workshop-f15
* @nshanmugham

# What is git?

* Source control
* Recover when you make a mistake
* Share code with others (remotely using GitHub)

![](http://i.imgur.com/a0oAzuq.png)

# What is GitHub?

* Host your source code using git
* Contribute to open source software
* Collaborate with teams


![](http://i.imgur.com/p8LV8o1.png)

# Setting up git

## Install

Mac

* Type `git` into Terminal
* Install from the Xcode dialog

Windows

* Download from https://git-for-windows.github.io/
* Use default options during setup

Ubuntu

* `sudo apt-get install git` into Terminal

## Configure

* From the command line, run:
(Use the email you use on GitHub)

````bash
git config --global user.name "<your name>"
git config --global user.email "<your email>"
````

* Next, run:

````bash
ssh-keygen -C "<your email>"
````

Hit [Enter] to use the defaults. 

* Finally:

````bash
cat ~/.ssh/id_rsa.pub
````

You should see:

![](http://i.imgur.com/V7d07We.jpg)

Copy everything from the beginning to the end.

* Go to https://github.com/settings/ssh; click on [Add SSH Key]
* Fill in the Title (example: Home Lenovo Thinkpad)
* Paste what you copied in the previous step into the Key
* Hit the green [Add Key] button.

## Verify it works (Optional)

````
ssh -T git@github.com
````

Continue past warnings (if any).
You should see a message with your GitHub username if things went well.

# Setting up GitHub

* Visit https://github.com
* Sign in or Create a new account
* Username can be changed later

