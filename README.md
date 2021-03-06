This is the R script repository of the "[Data Analysis 1a: Foundation of Data management in R](https://economics.ceu.edu/courses/data-analysis-1a-foundation-data-management-r)" course, part of the [MSc in Business Analytics](https://economics.ceu.edu/program/master-science-business-analytics) at CEU. For the previous years, see the [2016](https://github.com/daroczig/CEU-R-lab/tree/2016) and [2017 Winter](https://github.com/daroczig/CEU-R-lab/tree/2017) branches.

## Syllabus

Please find in the `syllabus` folder of this repository.

## Technical Prerequisites

Although the required software is already installed on the computers in the School Lab, but if you plan to use your own laptop, please make sure to install the below items **before** attending the first class:

1. Register an account at https://github.com
2. Install `git` from https://git-scm.com/
3. Install `R` from https://cran.r-project.org
4. Install `RStudio Desktop` (Open Source License) from https://www.rstudio.com/products/rstudio/download
5. Verify that in RStudio, you can see the path of the `git` executable binary in the Tools/Global Options menu's "Git/Svn" tab -- if not, then you might have to restart RStudio (if you installed git after starting RStudio) or installed git by not adding that to the PATH on Windows. Either way, browse the "git executable" manually (in some `bin` folder look for thee `git` executable file).
6. Create an RSA key (optionally with a passphrase for increased security -- that you have to enter every time you push and pull to and from GitHub). Copy the public key and add that to you SSH keys on your GitHub profile.
7. Create a new project choosing "version control", then "git" and paste the SSH version of the repo URL copied from GitHub in the pop-up -- now RStudio should be able to download the repo. If it asks you to accept GitHub's fingerprint, say "Yes".
8. If RStudio/git is complaining that you have to set your identity, click on the "Git" tab in the top-right panel, then click on the Gear icon and then "Shell" -- here you can set your username and e-mail address in the command line, so that RStudio/git integration can work. Use the following commands:

    ```
    $ git config --global user.name "Your Name"
    $ git config --global user.email "Your e-mail address"
    ```
    Close this window, commit, push changes, all set.

Find more resources in Jenny Bryan's "[Happy Git and GitHub for the useR](http://happygitwithr.com/)" tutorial if in doubt or [contact me](#contact).

## Contact

File a [GitHub ticket](https://github.com/daroczig/CEU-R-lab/issues).
