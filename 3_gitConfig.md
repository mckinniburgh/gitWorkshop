First, we're going to configure Git and GitHub in our command line. Then, we'll learn a little more about how to use and think about the command line as we build our repo. 

## Make sure you've signed up for GitHub at [http://github.com/](https://github.com/).
Keep your username and password handy. 

## Make sure Git is installed on your computer.

Open your terminal/bash:

Mac: press the space bar and the command key at the same time and type in "terminal."
Windows: launch the command prompt from the run window. 

Type `git`. If you get a nice list of things, you're good to go. If not, click on the following link and install as per the directions:

[http://git-scm.com/downloads](http://git-scm.com/downloads)

## Configure Git

Type the following into your command line, filling in the sections for your username and email. These must correspond to the name and email you used to sign up for GitHub.

`git config --global user.name "John Doe"`

`git config --global user.email johndoe@example.com`

`git config --global core.editor nano`

You don't have to use nano as your text editor; you can pick your editor of choice. 

To check your set-up, use:

`git config --list`

You'll get something that looks like this:

```user.name=Superstar Git User

user.email=gitsuperstar@gmail.com.

color.ui=auto

core.editor=nano -w
...```

If something seems wrong with your configuration but you just can't figure it out, go to your configuration file for a closer look. This tip courtesy of [story645](https://github.com/story645).

`nano .git/config`  

For more reading on `git config`, check out this [Git-SCM](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) tutorial, which was helpful reference in the making of this resource. 