# Installation and Setup Guide for Python and JupyterNotebooks/JupyterLab

<span style="color:gray"> This guide is just to help you setup your computer for CRIPT's API. It does not cover 
how to install CRIPT API, that will be covered in the first tutorial.</span> 

CRIPT requires Python (>=3.9), and the tutorials for CRIPT are writing in JupyterNotebooks/JupyterLab. If you already
have Python (>=3.9) and JupyterNotebooks/JupyterLab, you can skip this and move directly onto the JupyterNotebook
tutorials. Start with the tutorial labeled: [“Part_1_CRIPT_tutorial.ipynb”]()

## Contents

1. **Novice guide** (Never installed python; Not much coding experience)
2. **Intermediate guide** (Python already installed, or experienced coder)

---

## Novice guide:

For users not experienced in coding, we suggest loading in Anaconda (https://www.anaconda.com/). Anaconda is software
distribution for Python. What a software distribution is: is just a collection of multiple software group into one
package. So, when you download Anaconda you are actually downloading several programs and not just one program. In the
case of Anaconda, it includes:

* Python programing language
* R programing language
* 100+ Python "packages" (libraries)
    * Packages are extra programs that other people (usually open source) have written that extend python to be able to do
      new things. (For example: numpy: for matrix math; scipy: for advanced math operations like linear regression)
* Spyder (IDE/editor) and JupyterNotebooks/JupyterLab
    * IDE is short for Integrated Development Environment. It’s a software where you can write your code. Python can be
      written in the “terminal” on your computer without an IDE, but using an IDE provides much more tools like
      autoformatting, code error checking and much more that make coding way faster and easier. The tutorials for CRIPT are
      written using the JupyterLab as an IDE.
* conda, Anaconda's own package manager, used for updating Anaconda and packages

The benefit of this approach it is a single download, and hopefully all the files are put into the proper locations on
your computer automatically (when manually downloading programs, this can be a big source of frustration). The downside
is you are installing a lot of software that you may not want/need, but if you are getting into data science, you will
probably use a lot of the installed programs.

### Installation of Anaconda:

To installation visit on of Anaconda guide:
* Windows: https://docs.anaconda.com/anaconda/install/windows/
* Mac: https://docs.anaconda.com/anaconda/install/mac-os/
* Linux: https://docs.anaconda.com/anaconda/install/linux/

**Important checks:**

Double check is that you have python 3.9 or greater installed and it is select in Anaconda interface prior to launching
JupyerLab.

Once finished: open JupyterLab and then load [“Part_1_CRIPT_tutorial.ipynb”]()


---

## Intermediate guide:

### Python already installed:

If you have python already installed, installing Anaconda (Novice guide) can break how your computer is currently
configured. So you have three options:

1. Try installing Anaconda 
   * It may affect any of your prior work if you are luck, and but it may also double install
   programs that you have already on your computer, just in a new location.
   * If it does break things, it should just be a matter of re-directing file locations.
2. Start fresh by uninstalling python, then following the Novice guide.
3. Just install JupyerLab. 
   * Make sure you have python 3.9 or greater installed. 
   * See JupyterLab installation guide: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html
   * You may run into issues if you did not configure your python installation in the most preferred manner. If you
   have any issues, Stackoverflow is always a good place to start for help.

Once finished: open JupyterLab and then load [“Part_1_CRIPT_tutorial.ipynb”]()

### Experienced Coder:

If you are experienced coder in another language like C, C++, Java, etc. installing python and JupyterLab should not be
a difficult process. Doing it manually (vs the Novice guide), avoids downloading lots extra stuff that you may not need
and give you flexibility to configure the program to your liking. The one thing to be cognizant of is the location where
you save python, and JuypterLab. The installation typically defaults to the right locations, but if you run into issues,
this is likely that cause as some software look for python in the default locations. 
* Python(>=3.9) : https://www.python.org/downloads/ 
* JuypterLab: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html

Bonus: If you are looking for an IDE for python, we recommend PyCharm Community
Edition (https://www.jetbrains.com/pycharm/ ). Its one of the heftier IDEs for python, but those extra features do come
in handy if you are doing a lot of python programing. 

Once finished: open JupyterLab and then load [“Part_1_CRIPT_tutorial.ipynb”]()