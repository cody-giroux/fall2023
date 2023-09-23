    1  cd Desktop/392/
    2  git clone https://github.com/introcompsys/fall2023.git
    3  cd fall2023/
    4  git status
    5  git remote add origin https://github.com/cody-giroux/fall2023.git
    6  cd ..
    7  git remote add origin https://github.com/cody-giroux/fall2023.git
    8  cd fall2023/
    9  git remote add origin https://github.com/cody-giroux/fall2023.git
   10  git remote add fork https://github.com/cody-giroux/fall2023.git
   11  git remote -v
   12  git clone https://github.com/introcompsys/fall2023.git
   13  pwd
   14  cd 392
   15  cd Desktop/392
   16  git clone https://github.com/introcompsys/fall2023.git
   17  git status
   18  cd fall2023/
   19  git remote add origin https://github.com/introcompsys/fall2023.git
   20  git remote add origin https://github.com/cody-giroux/fall2023.git
   21  git remote -v
   22  git remote rm origin
   23  git remote -v
   24  git remote add origin https://github.com/cody-giroux/fall2023.git
   25  git remote -v
   26  touch terminal_practice.md
   27  history >> terminal_practice.md
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[remote "origin"]
	url = https://github.com/cody-giroux/fall2023.git
	fetch = +refs/heads/*:refs/remotes/origin/*
This setup allows for you to clone the main repo locally and then directly allows you to add, commit, and push changes into your fork locally right off the bat
