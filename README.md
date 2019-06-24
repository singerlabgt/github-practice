## github-practice ##
**example repo to practice using GitHub as a lab**

## Overview ##
this folder contains template files and exercises to practice using Git and GitHub
  * template files
    * [README.md](README.md) - this can be used as an example, edit as needed for your repo
    * [.gitattributes](.gitattributes) - this can be copied directly to any repo using Matlab code
    * [.gitignore](.gitignore) - this can be copied directly to any repo using Matlab code
    * [github-etiquette.md](github-etiquette.md) - this is an outline of etiquette and rules when using the lab GitHub page
    * [coding-etiquette.md](coding-etiquette.md) - general guidelines for writing code in the lab
  * exercises
    * setting up Git and GitHub
    * uploading your code to the lab github page
    * using code from lab repos and pulling/pushing updates
    * interfacing Git with Matlab

## Exercises ##
### Exercise 1 - setting up Git and GitHub ###
  1. Install Git on your computer
   * Mac: [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 
   * Windows: [Install Git with Git Bash](https://www.sitereq.com/post/easiest-way-to-install-git-bash-commands-on-windows#git-bash-windows-installation)
  2. Make a GitHub account
  3. Configure settings on your computer - enter the following on the command line.
      ```shell
      git config --global user.name "Your Name"
      git config --global user.email "youremail.edu"
      ```
      
### Exercise 2 - how to upload your code to GitHub ###
 1. Go to the [Singer Lab GitHub](https://github.com/singerlabgt) and click the green 'Create New Repository' button on the right. 
 2. Follow the setup instructions provided. For more details on the different options, [this page](http://swcarpentry.github.io/git-novice/07-github/index.html) provides a great explanation.
 3. Add the .gitignore, .gitattributes files found in the [github-practice folder](https://github.com/singerlabgt/github-practice).
 4. Write a README.md to document your code and how it works!
 
### Exercise 3 - getting code from lab GitHub repos and pulling/pushing updates ###
 1. Clone the remote repository to your computer/the neuro-cloud server
    ```shell
      cd neuro-cloud/labs/singer/yourname/directorywhereyouwanttokeepthecode
      git clone https://github.com/singerlabgt/github-practice
    ```
 2. Link the repository webpage so you can get updates later
    ```shell
      git remote add origin https://github.com/singerlabgt/github-practice
    ```
 3. To get updates added by other lab members, you can 'pull' them from the lab github page. Make sure any work you had done is committed before you do this (also see fetch/merge commands).
    ```shell
      git pull origin localbranchname
    ```

## References and Helpful Resources ##   

Tutorials
* [Software Carpentry Version Control with Git](https://swcarpentry.github.io/git-novice/) 

Git and GitHub for research
* [Our Coding Club's Git for Labs](https://ourcodingclub.github.io/2017/05/15/git-for-labs.html)
* [Matt Malishev's GitHub presentation for Emory](https://github.com/darwinanddavis/githubpres)
* [Blischak et al., 2016 Intro to Git for Research](https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1004668&type=printable)

Other helpful tools
* [Common Git Commands Cheat Sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)

### Maintainer ###

Contact Steph Prince if you have any questions or would like help using this code
