# Two Day Workshop on Insights of Data Science


##RStudio is an integrated development environment (IDE) for R. 
It includes a console, syntax-highlighting editor that supports direct code execution, as well as tools for plotting, history, debugging and workspace management.

####How to Install R Studio
In order to run R and R-studio on your system, you need to follow the following three steps in the same order.

1. Install R
2. Install R-Studio
3. Install R-Packages (If needed)

###Install R
Follow the steps below with respect to the operating system you are using

#####For Windows :
-----
Download the binary setup file for R from the following link.

[R for Windows](https://cran.r-project.org/bin/windows/)
Open the downloaded .exe file and Install R


#####For Mac :
-----
Download the appropriate version of .pkg file form the following link. 

[R for Mac](https://cran.r-project.org/bin/macosx/)
Open the downloaded .pkg file and Install R


#####For Linux :
-----
For complete R System installation in Linux, follow the instructions on the following link 

[R for Linux](https://cran.r-project.org/bin/linux/)
For Ubuntu with Apt-get installed, execute sudo apt-get install r-base in terminal.

###Install R Studio
On the following link Download R Studio choose the appropriate installer file for your operating system, download it and then run it to install R-studio.
[R-Studio](https://www.rstudio.com/products/rstudio/download/)

###Install the packages (Optional)
If your need to use R requires a particular package/library to be installed in R-studio. You can follow the instructions below to do so

1. Run R studio
2. Click on the Packages tab in the bottom-right section and then click on install. 
3. The dialog box will appear
4. In the Install Packages dialog, write the package name you want to install under the Packages field and then click install. 
5. This will install the package you searched for or give you a list of matching package based on your package text.

##Installing Anaconda 

Download the Anaconda [installer](https://www.continuum.io/downloads)

#####Windows install
-----

Double click the Anaconda installer and follow the prompts to install to the default location.

#####OS X graphical install
-----

Double click the .pkg file. Answer the prompts on Introduction, Read Me, and License screens.
And proceed as normal setup.

#####OS X command line install
-----

+ Go to the [DOWNLOAD ANACONDA NOW](https://www.continuum.io/downloads) page. Beneath the “Graphical Installer” buttons for Anaconda for OS X, there are command-line text links for Python versions 2.7 and 3.5.
+ Download the command line installer for Anaconda with Python 2.7 or Anaconda with Python 3.5.
+ Python 2.7: Open the Terminal.app or iTerm2 terminal application and enter the following:
`bash ~/Downloads/Anaconda2-4.0.0-MacOSX-x86_64.sh`
Or for Python 3.5 enter the following:
`bash ~/Downloads/Anaconda3-4.0.0-MacOSX-x86_64.sh`
    + NOTE: Replace `~/Downloads` with your actual path and `Anaconda3-4.0.0-Linux-x86_64.sh` with your actual file name.

+ The output of a successful installation will include the messages “Installation finished.” and “Thank you for installing Anaconda!”

#####Linux install
-----

+ Open a terminal window and type the following:
`bash ~/Downloads/Anaconda3-4.0.0-Linux-x86_64.sh`
    + NOTE: Replace `~/Downloads` with your actual path and `Anaconda3-4.0.0-Linux-x86_64.sh` with your actual file name.

+ Follow the prompts on the installer screens, and if unsure about any setting, simply accept the defaults, as they can all be changed later.

#####Configuring R for NoteBooks
-----
Install the R Essentials package with the conda install command.

For Linux, OS X and Windows

If you have conda installed, you can easily install the R programming language and over 80 of the most used R packages for data science with one command. Conda helps you keep your packages and dependencies up to date. You can also easily create and share your own custom R packages.

R-Essentials works very much like Anaconda:

+ Installs all of the most popular packages with all of their dependencies with one command: 
`conda install -c r r-essentials`
+ Update all of the packages and their dependencies with one command: 
`conda update -c r r-essentials`
+ Update a single package in R-Essentials (if a new version of the package is available in the R channel) with the command:
`conda update r-XXXX`

#####Native R kernel for Jupyter
-----
Install IRkernel package via the devtools package:

`install.packages(c('repr', 'IRdisplay', 'crayon', 'pbdZMQ', 'devtools'))`
`devtools::install_github('IRkernel/IRkernel')`
`IRkernel::installspec()  # to register the kernel in the current R installation`

Per default `IRkernel::installspec()` will install a kernel with the name “ir” and a display name of “R”. Multiple calls will overwrite the kernel with a kernel spec pointing to the last R interpreter you called that commands from. You can install kernels for multiple versions of R by supplying a `name` and `displayname` argument to the `installspec()` call (You still need to install these packages in all interpreters you want to run as a jupyter kernel!):


# Data set are availabe:
- [Link](https://vincentarelbundock.github.io/Rdatasets/datasets.htmldsfasd) 
- R provides few data sets available at [Link](http://stat.ethz.ch/R-manual/R-devel/library/datasets/html/00Index.html)
