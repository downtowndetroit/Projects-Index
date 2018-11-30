# [DDP](http://www.downtowndetroit.org) Projects Documentations

This is a all-in-one Tian's DDP Projects Documentation pages. The purpose of this page is to

1. Act like a Projects index in Github
2. Provide general solution for environment setting

## Projects Pages(By Time Series)

1. [Downtown Geocoder(tools)](https://github.com/tianxie1995/Downtown-Detroit-Geocoder)
2. [Downtown Business Inventory(Web Application)](https://tianxie1995.github.io/ddp-business-inventory-arcgis/)
3. [Development Viewer(Web Application)](https://tianxie1995.github.io/ddp-business-inventory-arcgis/development)
4. [Places API Scraper(tools)](https://github.com/tianxie1995/google-places-scrapy)
5. [Detroit Building Permit Automation Tools(tools)](https://github.com/tianxie1995/ddp-building-permit)

## Environment Setting

### Set up Python

Project 1,4 and 5 are writen with Python3. So the most important prerequesit is to have the right Python3 environment. I suggest to use `Anaconda` Python3 distribution. You can directly download from their [website](https://www.anaconda.com/).

### Install Required Packages

**Windows:**

### Install Git in computer

To clone the repository from Github, you need Git downloaded from https://git-scm.com/downloads . After install Git, restart Anaconda Prompt.

In Windows, from the Start menu, search for and open “Anaconda Prompt”.

a. Create a new environment named `ddp`

```
conda create --name ddp
```

b. To use, or “activate” the new environment, type the following:

```
activate ddp
```

c. Install Packages required by specific srcipt, please refer to specific project pages

d. Run Scirpt

Within Anaconda Prompt, run

```
python SCRIPTNAME.PY
```

**MacOS or Linux**

All commands below are typed into the Terminal window.
a. Create a new environment named `ddp`

```
conda create --name ddp
```

b. To use, or “activate” the new environment, type the following:

```
source activate ddp
```

c. Install Packages required by specific srcipt, please refer to specific project pages

d. Run Scirpt

Within Anaconda Prompt, run

```
python SCRIPTNAME.PY
```

## Run script

After we set up the Anaconda environment, we can start running scripts.

**Windows** (_Runing in Anaconda Propmt_)

**Clone Repository**

choose the folder you want to put the repository in and clone it from Github

Find the repo link in Repo
![img](repoLink.png)

```
cd FOLDER_ABOSOLUTE_PATH

git clone REPO_LINK
```

**Install packages and change configuration**

After clone the repository to your computer, we can start running the script

a. First, you need to change the current working direction to the repository by

```
cd REPO_FOLDER_NAME
```

b. Please read through each repository's README.md for requriement for each repo, change configuration, install required packages if needed

c. Run the script (this step depend on specific script's requirement)

```
python SCRIPT_NAME.py
```
