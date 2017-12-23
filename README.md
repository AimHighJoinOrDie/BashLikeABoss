# Bash Like A Boss
Quick guide on how to get the most out of VIM / Bash / GitHub (according to a high school student and help from [Mr. McKinstry](https://github.com/RobbieMcKinstry))

## Student Upgrade for GitHub 
Applying for a student pack gets you free unlimited private repositories (and lots of other stuff)

Go to -> [GitHub for Education](https://education.github.com/)


![](https://aimhighjoinordie.github.io/BashLikeABoss/assets/GitEdu.png)


Apply for the pack and wait a few hours for the upgrade.  

## Step 1 (To Upgrade Vim)
Install Vundle (Plugin Manager)

Go to -> [Vundle](https://github.com/VundleVim/Vundle.vim)

Follow Quick Start instructions

## Step 2 
Visit Vim Awesome and add useful plugins

Go to -> [Vim Awesome](https://vimawesome.com/)

The Nerd Tree is the most useful plugin of all; it allows for easy navigation. 


![](https://aimhighjoinordie.github.io/BashLikeABoss/assets/NT.png)


Remember to run :PluginInstall in vim after you add plugins (type "vim" in Bash and run from there)

## Step 3 
Can you run / compile java programs? Add:
```markdown
export PATH=$PATH:"/C/Program Files/Java/jdk-9.0.1/bin/"
```
to the end of your .vimrc or .bashrc . 
This is the command for my particular computer / directory; it could vary for you.  
(Just find where the JDK is and its name.)
Now, you can run:
```markdown
javac HelloWorld.java
java HelloWorld
```
## Additional Info. 
I have also installed Bash-It on one of my laptops.  

Go to -> [Bash-It](https://github.com/Bash-it/bash-it)

It significantly slows Bash, but it is pretty cool.
Bash-It can add features like a clock or battery life meter to your Bash command line. 
It is also an alternative location to add export statements (like with the JDK path).

## Feel free to contact me with Questions
Email: Sean.hazlett2@gmail.com 
