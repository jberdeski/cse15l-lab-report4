# Using Vim to Edit Code

`vim` is a a free and open-source, screen-based text editor program.
> definition from wikipedia.com

## Demo Use of Vim

**_What is our task?_**

Our task is to download and clone code that has an error in it and use vim to fix that error.

**Step 1**
Logging in to ieng6:

If you have seen my other pages you will find a tutorial on [how to log in to a remote account](https://jberdeski.github.io/cse15l-lab-report1/report-steps.html).
However this case is slightly different as I have set it up to no longer require a password to log in,
so all I have to do is use:

`ssh cs15lsp23__@ieng6.ucsd.edu`

> __ is to be filled in with the leters specific to your account

![Logging In](1.Login.png)


**Step 2**
The next step is to clone your fork of the repository from your Github account:

In order to do this we will use the command:
`git clone ___________`
> ________  is to be filled in with a link to the forked repository
> depending on if you have it set up or not; you can use the HTTPS link or the SSH link

![Cloning the Repository](2.clone.png)


**Step 3**
Running the tests (they should fail right now):

First I wanted to make sure I was in the right directory so I did:
`cd lab7/`
Then I checked what files were in the directory by using:
`ls`
To run the tests I used:
`bash test.sh` 
since it was in the directory when I used `ls`.



`vim LabExamples.java`
1) /index1
2) press n 10 times to reach the last index1
3) right 5 times
4) x
5) i
6) 2
7) esc
8) :wq
9) 
