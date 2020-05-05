# Bourne Again Shell (BASH)

The BASH shell is the de-facto standard for manipulating files, peforming system calls, getting system information, and above all the best way to manage your computer. 


## Introduction 

When you login to the Syzygy server you will be directed to the homescreen. Here you can see a panel with three tabs. Files, Running, and Clusters. The files panel contains all the files currently located on your home directory. As you can see I have several files already on here. Some of them have the "books" icon, others have a directory icon.

I believe most of you do not have files already on syzygy. So now we will create one. First we must be introduced to the BASH shell. To create a BASH shell click on "new" and then go to terminal. You will se a black screen with white lettering. This is the terminal shell. This is the point of contact for a computer. 

## Abstraction Explaination
On all your computers, we have our desktop environment. However our desktop enviornment is simply an abstraction for all this code running in the background. For example if I go to my own personal computers terminal, you can see I have a similar prompt. For example if I run the command "say hello" my computer says hello. If type in open . this will open the files on my mac. In Reality your computer is running everything you are doing behind your back in these terminal shells. These shells are what computers were like in the 80s and 90s until Bill Gates and Steve Jobs revolutionized everything. 

## Simple Commands
So anyways back to our lesson. If you go to your syzygy terminal. The first commmand we are going to learn is called "ls" ls, lists all the files in your currently directory. Here we can see that I have some files. Lets type in ls -l for a "list view". This lists the files in a convenient way for us to read. This gives information on when these files were created. So most of you dont have files on here so we are going to create one. 
```bash
ls 
ls -l
```

## Creating Files
To create a file we are going to use the "touch" command. touch creates an empty file with a name you have provided. For example if type in touch hello.txt it creates a text file on the server. if you type in ls again you can see the hello.txt file exists, and it has 0 bytes of information. Lets go back to your home directory. We can now see that hello.txt exists! 

If we click on it we can open it up. I am going write some stuff inside of it!. Lets go back to the terminal. Now you can see that our terminal is a little messy, so what we are going to do is actually clear it. To clear our terminal we are going type in clear.

```bash 
touch hello.txt
```

## Creating Directories

Now our terminal is clear we are going to learn the next command, this one is called "mkdir". mkdir creates a directory with a specific name. So we are going to name our directory hello. If you go back to our home directory we can see a folder has been created. You see commands you type in the terminal, has an effect on the system! 
```bash 
mkdir hello
```
## Moving Files

Lets say we want to move our hello.txt file into our new directory called hello. So what we will do is use the "mv" command. mv command requires arguements, the first is what file am I moving, the second is where am I moving it too

```bash

mv hello.txt hello 

```


Now if we go back to our home directory and go into hello, we see that hello.txt is indeed in the folder! 

## Renaming Files

We can use mv to rename files and directories as well! 
Let say we will want to rename our directory hello to hello2, then we can use the mv command again! 
```bash
mv hello hello2
```

and poof, we have renamed our original directory. If your home directory doesnt update the name, we can click the refresh icon on the right hand side. 





