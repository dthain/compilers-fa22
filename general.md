# General Submission Instructions

## Build Environment

To ensure a consistent environment between development and grading,
please use the standard CSE student machines (RHEL8) to build and test your code.
These machines are using gcc-8.5.0, flex-2.6.1, and bison-3.0.4.
Use `which gcc` to double check that you are using the standard `/usr/bin/gcc`
and have not otherwise modified your PATH for another class.

## Code Organization

To ensure that you get off on the right fit (and we are able to understand your code)
you will be required to use the standard [starter code](http://github.com/dthain/compilerbook-starter-code)
which defines structures like `decl`, `expr` and so forth.  You are welcome to add files,
fields, and functions as you like, as long as the general purpose of these structures remains.

Your code must include a `Makefile` such that when you type `make`, the entire compiler (so far)
is built and produces a program called `bminor`. Each assignment page will specify what arguments are required to call it.
Likewise, `make clean` should remove all intermediate object files, automatically generated code, and so forth.

## Getting Started with Git

[Git](https://git-scm.com/) is a version control tool that allows you to save and collaborate on programming projects. In Git, your code is saved in two different locations--the local copy and the remote copy.

**Step One: Remote Copy**. 
1) First make sure you are logged into Github then go to the [starter code](http://github.com/dthain/compilerbook-starter-code) and click the green "use this template" button. If you don't see the button you likely aren't logged in.

2) Use your netid followed by whatever you'd like as the repository name. Here is an example: `nziems2-compiler`

3) Make sure your repository is **PRIVATE** not public, then click the green "Create repository from template" button.

4) Copy the url of the created repository. The URL should look something like this:
`https://github.com/Ziems/nziems2-compiler`

5) Go into your repository settings on the right side of the screen then click on "Collaborators". Add both me and Dr. Thain as contributors. Our usernames are `dthain` and `ziems`.

6) Open slack and reply to Noah's post in the class channel with a link to your repository(the url you copied)


**Step Two: Local Copy**.
1) In a terminal, navigate where you'd like the project directory to be.

2) Using the url you copied run the following command. Because the repository is private you will have to enter your GitHub username and password:
`git clone <url>`

3) Navigate into the directory and open the README.md file with your favorite text editor. Make a change to the title then save the file.

4) In your terminal run `git add README.md`

5) Run `git commit -m "Edit readme"`

6) Run `git push -u origin master` 

## Turning In Code to Github

1) Go back to the link of your github repository. Make sure you refresh your page. **If everything went well you should see the changes you made to the README.md file.**

2) On the righthand side under "Releases", click "Create new release"

3) Click "Choose a new tag", type "scanner", then click "Create new tag"

4) Click "Publish release" at the bottom and you're done!

## Double Checking Your Submission

There are two ways to check your submission: on GitHub and locally.

### On GitHub
To double check your submission on GitHub, you can navigate to the repository on GitHub and make sure the files you changed locally are also changed on GitHub.

### Locally
To double check your submission locally:

1) Copy the url of your GitHub repository

2) In a terminal, navigate where you'd like the clean project directory to be

3) With a new name for the repository, run `git clone <url>`. **If a directory with the repository name already exists, you'll have to run `git clone <url> <name>` where `<name>` is a different from the original repository name.**

4) Navigate into your newly cloned repository and double check all the files are correct for your submission.

## Setting Up Custom Environment
For those who need to do not wish to work on the student CSE machines, here are the instructions to setup the environment locally. Please know that you are responsible for setting up the environment properly and ensuring your work still functions on the student CRC machines.

1) First, [install conda](https://docs.conda.io/en/latest/miniconda.html)

2) Create a conda environment by running `conda create --name compilers-env`

3) Activate the environment: `conda activate compilers-env`

4) Install 