# Step 1: Set Up and Initialize Your Project

A *project* is just one or more files that you want to apply Git version control to. Often this includes files in several directories and subdirectories, but for now you'll just use one directory and one file.

**A: Install Git**

First, ensure Git is installed on your system. You can download it from [git-scm.com](https://git-scm.com/), and it’s available for Windows, Mac, and Linux.

**NOTE**: If you're familiar with using package managers like [Homebrew](https://brew.sh/) (MacOS), _apt_ (Linux), or [Chocolatey](https://chocolatey.org/) (Windows), feel free to use that installation method instead.

**B: Create Your Project Directory**

Create a new directory on your computer, and move to that directory.

1. `mkdir example-project`
2. `cd example-project`

**C: Initialize Git**

'Initializing' Git means setting up Git in your project's directory to create a _repository_. A repository is the entire working environment that's being tracked with Git. It includes your project files and the `.git` directory you're creating below.

`git init`
    
This command creates a new `.git` directory in your project folder, which Git uses to track project changes.

**IMPORTANT**: don't delete or otherwise modify this directory while working on your project, or you'll lose all of the project history that Git tracks.


<div style="page-break-after: always; break-after: page;"></div>
