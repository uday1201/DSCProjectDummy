# DSCProjectDummy
This is a dummy project we created to show how to collaborate

## 
<!-- TOC -->
- [Install Git](#install-git)
- [Forking](#fork-this-repo)
- [Creating a Pull Request](#create-a-pr)
<!-- /TOC -->

---

## Install Git
### **Mac**
#### Using terminal to install git

* Installing `brew`(skip if you already have it)
  * __Checking for `brew`__
    * Search for terminal (Super + Space) and open up the app 
    * Enter the following to check the version `brew --version`
  * Enter the following into the window that pops up `brew`, then install ` /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
  * Be on the look on the terminal since there are more instructions afterward
  * __Resources__
    * Tutorial that is clear and straight to the point: https://www.youtube.com/watch?v=3XEr6ica_h0&ab_channel=KrunchyNacho
    * Repo w/ install & uninstall manual: https://github.com/Homebrew/install
  
* Install git using `brew`	
  * Enter the following into the command line (terminal) window `brew install git`

#### Install Desktop App
* Go to https://desktop.github.com/
* Select download for macOS or go to https://central.github.com/deployments/desktop/desktop/latest/darwin


### **Windows**
####  Installation of a Bash Command Line

* Use https://gitforwindows.org/ or https://git-scm.com/downloads
* Run the installer (clicking next on everything is generally fine - defaults are safely configured)

#### Install Desktop App
* Navigate to https://desktop.github.com/
* Select download for Windows 10 or go to https://central.github.com/deployments/desktop/desktop/latest/win32

---

- ## Fork this repo
  ![Fork](images/1.png)
  *Click on the Fork button and clone it into your profile*

- ## Clone the repo in your profile
  ```bash
  git clone https://github.com/<YourUsername>DSCProjectDummy.git
  ```
- ## Add a file with name <YourNetId>.txt inside folder **DSCProjectDummy/**

  ```
  Name
  Email
  ```
- ## Add your changes to your local repo

  ```bash
  git add <YourNetId>.txt
  ```

- ## Commit your changes

  ```bash
  git commit -m "<Your commit message>"
  ```

- ## Push your changes

  ```bash
  git push origin master
  ```

---

- ## Create a PR

  ![Open PR](images/2.png)
  *It will show that your repo has changes that is not in mine**

  ![Open PR](images/3.png)
  *Keep everything as it is, we are pushing the changes from main branch to main branch of my repo*

  ![Open PR](images/4.png)
  *Add information about your PR*

- ## I will review and approve/reject or ask more details in the PR
