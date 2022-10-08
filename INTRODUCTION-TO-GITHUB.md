# Introduction To GitHub
## The table of content
### Introduction
### What is GitHub
### Why GitHub
### Git vs. GitHub
### Clone (Show how to do cloning)
### Pull request (Show how to do a pull request)
### Commit (Show how to do a commit)
### GitHub Desktop vs. Github CLI
### Conclusion

the beauty of open source is the oppurtunity it provides to tech euthiasist all alroubd the world, the possibilty of having people from different part of the world contribute to a particular prokect is real time is 
And one tool that makes these contributions possible is Github, in the article we will be going through some basics things you need to know about githbu to get up and runnung and start contributing to projects.

What is Github
Github is a hosting platform that allows you store, version or track changes and also collaborate on software projects. 

You may be asking what all these means, let me explain; Imagine I started a project on my local machine, but I want a place where I can save this project online so that i can easily retrieve it incase anything happens to my local machine (Store), Let's also imagine that I want to save each change I make to the project as I make progress, so after making changes I send it to Github to store. Now what Github does is that it is able to track changes made to that project, this is important because you can easily revert to any point a change was made incase there was an error. Github also allows you collaborate on projects, After storing my code on Github, if I made the project repository public, anybody from anywhere in the world can also make contributions to that projects.

Why Github?
I think this question is relative, the reason is because each person you ask might have a different platform they prefer. However Github seems to be more popular amongst the developer community. And personally I was introduced to Github first and overtime I have discovered that it's easier to use.

What is the difference between Git and Github
This is one question lots of newbies ask, and maybe becasue often times they have held people mention Git and Github in the same sentence but however they couldn't be more different. Git is a version control system that answers questions like: when was a change made, who made that change, what folder or file was the change made and why the change was made. While Github is a platform that uses the power of Git to help your manage Git repository that is why you can track changes made on a repository in Github.

How do I clone a Repository?
Cloning, just like the name suggest is creating a copy of a remote repository in your local machine, with the repository was created by you or not, you can clone it. And how do you do this? you can either use the Github Desktop or the command line. I will work you through how to do both.

Cloning with Github Desktop
You will need to have the Github Desktop application installed in your local machine. If you have that installed, here are the steps to take:

Go to the repository you want to clone on Github
click on the code buttton, a drop down menu will appear
click on Open with Github Desktop
If you have Github installed, a prompt will appear asking you for permission to open the Github desktop Application, But if you don't have it installed, Github will ask you to download it.
After granting the permission, the Github Destop application will be opened, showing the interface below

click on clone

If the cloning is successfully, it means you now have acopy of that repository in your local machine. Search for that repository in your local machine and you will find it inside a Github folder.

There is another approach you can take in cloning using the Github Desktop application.
to do this, follow these steps
Open the Github Desktop application
Click on file, a drop down will appear
Click on Clone repository
A modal will pop up. where you can either use Github.com, Github Enterprise or URL.
Under Github.com, you will see a list of all repositories you have created or forked, you can choose any of the repository and click on clone.

Under Github Enterprise, you will need to have a Github Enterprise to use it.
Under URL, you will need to copy the URL of the Github repository you want to clone and paste it on the empty field, After that, click on clone.


Cloning with the command line
Before you can clone the repositry in your local machine, you will forst need to get the URL of the repository in question. you can do that by following these steps

Go to the repository you want to clone on Github
Click on the COde button, and a drop down menu will appear
copy the URL of the repository
Open your command line and cd into any folder of you choice
use the command below
git clone [Paste the URL of the repository here]
click enter
when you go to the github reposotory you want to clone, 

How do I make a Pull request
After forking a reposistory and making your contribution to a project, you need a way to be able to tell the owner or maintainer of that projects that you have made a contribution and that you will want them to merge it to the main project reposistory. Pull request is the way to do that.

So two things happen when you fork a repository on Github, Github watches both your repository and the repository you forked from. Through that, Github notifies you when changes has been made to the original repository you forked from asking you to updating branch, It is important you ensure that your branch is in sync with the original branch before raising a pull request. 

Github also tells you when you forked branch is ahead of the original branch, under the contribute option, you will see an active button telling you to open a pull request.


## How can I fork a repository?
When you want to contribute to a project that isn't yours, before cloning the first thing you need to do is to fork that repository. By forking that repository, you are creating a personal copy of that repository on your Github, after forking, you will notice that the repository will be added to your list of repositories on github.

### Why do I need to fork a repository?
If you go ahead to clone a repository you don't have access to without first forking it, you won't be able to make contributions to that repository because it is not yours. But when you fork the repository first, you have a copy you can make changes to, and after making your desired change, you can push (store) that change(s) to github and then make a pull request to the original repository.

To fork a repository, follow these steps:
- Go to that repository on Github and click on fork ![fork repository](images/fork.png)

- you will see a new screen like the one below
- Click on create fork (You can also change the name of the repository if you want to)
If the forking is successsful, you will notice you now have a repository by that name, you will also see that it will point you to the original repository it was forked from.

## How do i make a commit
As you work on your projects or contribute to other projects, for each bug you fix or addition you make, you should write a commit message, describing in simple, short, and clear terms what changes you made.This commit message helps you know when and what change you made at a particular time, and if its a project you are contributing to, it helps the maintainer of that project know what changes you made even before looking at the code.
So how do you make commits on Github? Before making a commit, you should first stage the changes you have made. 
either by using
`git add [name of file]`
To stage a particular file
or
`git add .`
to Stage all the changes you made.

After staging your changes, you can then proceed to commiting your changes by running the command below
`git commit -m "[commit message]"`
example is
`git commit -m "Added dashboard pagination"`


## GitHub Desktop vs Github CLI
Github Desktop is a graphical user interface that helps you interact with Github without using the browser. From the Github Desktop, you can perform actions such as creating a repository, cloning a repository, making a pull request, and committing just with a few clicks.
Github CLI is a command-line tool that helps you access various Github features without having to leave your terminal. you can make a pull request, open an issue, and so on. You can see the list of Github CLI commands [here](https://cli.github.com/manual/gh).

## Conclusion
Knowing how Git and GitHub work is important for a developer or technical writer who is looking to collaborate with others and work on amazing projects. It is also an important criterion if you want to be employable.
In this article, we have been able to cover some aspects of Github, like how to make a pull request, how to fork a repository, and how to clone a repository. We even touched on the difference between Git and GitHub and the difference between GitHub desktop and Github CLI. But that is not all. There is still more to learn, and for that reason, I will be suggesting relevant resources you can use to learn more about Git and Github.

## Other Relevant Resources
- [Github Docs](https://docs.github.com/en/get-started/quickstart)
- []()
- []()