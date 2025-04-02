# EEMB 595R/194R RSeminar
Shared Code Repo for UCSB EEMB R Seminar(EEMB 595R, EEMB 194R)

Created by Leander Anderegg (landeregg@ucsb.edu, https://github.com/leanderegg), based on materials created by legendary Dr. Ian Breckheimer (https://github.com/ibreckhe) for an old R Seminar at the University of Washington (https://github.com/UW-RSeminar-Fall2015)

# Schedule:
https://docs.google.com/spreadsheets/d/1KVy5sDUts8ZbA43a6mORx8WoYPln6zxAxpIcuUJFJpE/edit?usp=sharing

# Listserv:
rstats@eemb.ucsb.edu (add your email to the Schedule or email landeregg@ucsb.edu to be added)

Guidelines for Presenters:

- Move Slow—You know your code, data and approach better than your audience.

- Make it Interactive—Include a simple exercise to give people a chance to play with the code.

- Upload materials at least 24hr in advance—Allows folks to install packages, work out any platform-specific kinks.

- Motivate with Science—We are scientists, not programmers.

## For Folks Enrolled in 194R/595R
- If you're a grad enrolled in 595R, please sign up to lead a tutorial
- If you're an undergrad enrolled in 194R, please sign up to either of:
    1) help a grad student with a tutorial (be an assistant tutorial lead)
    2) present a 5-10 min 'Favorite Function' section to
       - give a deep dive into a function (either your current fav/a great one you've recently discovered or one of the central functions from a prior tutorial that you wanted to know more about)
       - Share a coding tip or trick that makes your code more readable/transferable/robust or just something cool that makes your R life better.
(NOTE: This is actually intended to be quick, really 5mins or less)

## Instructions for Presenters:
Sign into the GitHub website and create a new repository to hold the files you want to share. Name it using the convention "Sp25_WeekX_topic". For example if you are presenting about regression on week 3, the name would be "Sp25_Week3_regression". Optionally add a description, .gitignore, README, and license. Click "Create repository".

In RStudio, go to File > New Project... Select Version Control > Git

Clone the repository to your local machine. The repository URL should be https://github.com/*username*/*repository_name*.git. Choose a directory name and indicate where on your local machine you want the files to live, for example ~/leeanderegg/code/.

Click "Create Project". This will create a directory and that will sync to the remote repository. It will also download the files (README,.gitignore,LICENSE) that you created on GitHub to this directory, and create a new Rstudio Project file.

Get Coding! To start a new script, go to File > New File > R Script, and save it to the repository directory. Write some code and run it to make sure it works.

When you get done with a chunk of significant work, Save the script and select the "Git" tab from the upper-right panel in RStudio. Click "Commit".

Click the blue down arrow to pull changes from the remote server, then hit the check marks next to the files you want to sync to the remote repo. Add a message describing what you just did and click the "Commit" button.

If everything has gone smooth, you are ready to push changes to the remote server. Do that by clicking the "Push" button. Now you are ready to do another chunk of work. Save, Pull, Commit, Push, Repeat.

When you are done with the code, email me (landeregg@ucsb.edu) and I will fork the repository to the R Seminar Organization so it will be easy for the rest of the group to find.

Note on public vs. private repositories
The default for GitHub (and this seminar) is to have all of the files in a repository, including code and data, open for public examination. If that is not possible (for example you are using someone else's data), you can choose to keep a repository private when you create it. To do so without paying for a GitHub subscription, you will need to apply for an education discount (https://education.github.com/). After you get the discount, you can select the "Private" option when you create a new repository. This repository will not be visible to anyone except you by default. In order to share it with the rest of the seminar, you will need to give me access to this repository so I can create a "fork" of it that will be visible to the rest of the seminar participants, but not the general public. To do this, go to the repository's website, and click the "Settings" link on the right-hand side of the page, and then select the "Collaborators" tab. Add my GitHub username (@leanderegg) to the collaborators list.



## Github and R/Rstudio resources:
https://cfss.uchicago.edu/setup/ 
https://rfortherestofus.com/2021/02/how-to-use-git-github-with-r/
![image](https://github.com/UCSB-RSeminar/W24_Wk1_Intro_RSeminar/assets/96857122/4e1726c7-0859-405a-9499-0413a04a8da7)
