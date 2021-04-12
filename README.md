# Reflections - Sprint 1

## Command Line

This was the first topic of our course at Dev Academy.

The command line is a tool or software where you can interact with you computer in a similar way you would on your file explorer or "finder", however on the command line, instead of clicking and dragging your files and directories, you write commands to interact with them.

On each section of the course they provide a timebox, where they suggest the amount of time you need to complete each section. In this particular case I didn't stick to the time box because I've decided to customize my command line a bit more, using iTerm2 and Oh My Zsh!, both tools have its own particular features, such as themes, autocomplete, show brach and directories in a much more fun way.

I've learnt a variety of commands, such as:

- `mkdir`= create or make a directory
- `touch` = create a file
- `ls` = list the files and directories in a directory
- `rm -r` = remove a directory
- `cd`= change directory

## Version Control with Git

In this section we've leant about git and Github.

These two are very distinctive from each other. Git is a Version Control software where you have the ability to have multiple people working on the same project allowing them to contribute in a very organized way without overwriting each other. And Github is where you'd be publishing your projects, either privately or publicly, where your team can see the changes and versions of your project.

Since I was very familiar with this topic from previous studies, I don't think I will be revisiting this material to understand the difference between git and Github.

This time I stuck with the timebox, I was slightly faster because I was familiar with the topic.

## Install and Explore Git

On this section we've installed git and covered some basic commands and features of it.

When working on the same project as a team, with many people making different changes, we need to follow the Github work flow, which is a way to collaborate to the project in a way where the changes don't get overwritten by each other.

On the GitHub work flow we follow some basic steps:

- First create a remote repository on Github website
- On your local project directory, you initialize a git folder with the command `git init`
- Add the files to your local repo to start the project with the command `git add . `
- Commit the first changes with a readable and instructive message using: ```git commit -m '<message>'
- Add a remote repository by using `git remote add origin https://...`
- And finally push those files from your local repo to the remote repo `git push -u origin master`

After doing all that, everyone from your team will have access to that repository and you can start working together. They can clone the repository to their local and create a branch of the project and start making their changes, after making the changes they can merge their branch with the main branch so the project can be updated.

There is a lot more to this work flow, but the main point here is to understand that, working with git and github will allow your team to have less conflicts when working on the same project, because these tools allow you to have a history of changes letting you and your team keep track of everything.

My learning on this stage was relatively easy, since I was already familiar with the basic work flow, although I have learnt a lot of new things with the content provided.

I was just a bit confused with the choice of terminal, I've been using zsh for quite some time and this section of the course they suggested the usage of bash, but I decided to stick with zsh since I was already used to it.

The learning exploration was very intuitive and informative, I wouldn't change a thing. I'm very happy with the content the course is proving.

## Track and Commit

On this section, we've covered the concepts of stage and commit.

When you commit a file you are concluding the changes you've made on the code and getting ready to be push to the remote repo. Commits are always followed by a descriptive message.

Stage is basically prepare your files to be committed, so whenever you make a change to your code you will first add or stage those files and then commit with a message to describe the changes you've made.

## Branch, Pull, Merge

This is the fundamental topic of the GitHub work flow.

You create a branch of the repo, make modifications and make a pull request to the "owner" and merge your branch with the main branch.

That is the basic flow of most of the collaborative projects.

By definition, "main" is the original project created by someone and pushed to github, and a "branch" is a "copy" of the main project where you can make modifications and test without changing the original.

This concept was very intuitive and easy to understand, and I find it fascinating when I remember the old days where you would have to save all those files (project-version-1, project-version-2, final-version etc...), it would've been a mess. Version control and github have changed the game.
