In advance of our coding bootcamp, there are a few tools you should set up so we can hit the ground running in class.

# I.  Set up a GitHub account
We are going to track and share our code using *git* (a version control software) and **GitHub** (a website that hosts code repositories, using *git*).

1. If you do not already have a GitHub account, sign up for one.
A basic free account is fine, but you can also sign up for a free education account and get access to some perks here: https://github.com/education

2. Download and install GitHub desktop: https://desktop.github.com/download/

3. Log into the GitHub desktop app using your GitHub credentials. The desktop app is a nifty graphical interface for using git that is more user-friendly than interacting with git through the command line, and I highly recommend it.

*Optional (but recommended) reading on git and GitHub: https://github.blog/developer-skills/github/github-for-beginners-your-roadmap-to-mastering-the-github-essentials/*

At our bootcamp, we will start by creating a new repository to hold your code for this course. This repository will be where you push (upload) code from each day so that I can see what you have done. I will also share code with you through this GitHub repository.

# II. Install Anaconda & Python and run Jupyter 

We will use **Anaconda** to manage the installation of Python and Python packages. See the installers here: https://www.anaconda.com/download/success

There are two options:
1. The full **Anaconda Distribution**, which is very beginner-friendly but also huge (4.5GB on Mac OSX) because it ships with many popular packages pre-installed.
2. The much smaller **miniconda** which you interact with through the terminal / command line to install packages as needed.

I recommend miniconda, but feel free to choose the installer that you prefer. 

Start up Jupyter before bootcamp to make sure that you have it set up properly.
To start up Jupyter, follow these steps, depending on which conda distribution you are using...

## Using the full **Anaconda Distribution**
1. Open Anaconda
2. Select jupyter-lab in the Anaconda interface - look for a little card that says JupyterLab and press the "Launch" button

## Using **miniconda**
*Note text in a `code block` should be entered into your terminal (Mac OSX) or command prompt (Windows)*
1. Install jupyter using pip, the python package manager
`pip install jupyter`

2. Start jupyter-lab by entering
`jupyter-lab`


