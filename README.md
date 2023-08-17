# Github 101

Suho Choi A01029460


##[References](https://www.markdownguide.org/)

![Github logo](/Images/GIthub%20logo.png)
***Github***
What is github 101

>Week 1: On the first week, we have focused on the basics of Github. What we have learned is that github is an advanced saving system, where you can save your projects either locally, or through github (Online platform version of git), and also both.
The first thing we have done is to find the file where the programme is located.

>>![wonderhoy](/Images/wonderhoy.png)

The inputs for git are the following:
>**ssh**: Secure Shell: It is an input required to assign the file in order to secure the transaction between the local file(computer) and local file(Github).
>**ls**: list. git shows every archives that are listed in the folder that it's looking at

>**cd**: moves to the said folder. Ex: cd "folder_name"

>**pwd**: Shows the current folder which git is looking at

The above were the inputs to find and look for the folder that git is working with.

###How to pull/push (retrieve or upload files)

>For you to upload files in github, you must first set your local git connected to github. For that, you must first make a repository in github, and add SSH to the local git file. The process is done in the following method:

>1.- copy the ssh URL from github repository
>2.- type *git clone* on git, and paste the URL


In order to pull or push files, the following steps are required.

>### Push
>1.- Modify/Create new file in the git file.
>2.- Check the modification of the file with the following input: *git status*.
>3.- Add the modified status to git in order for it to understand: *git add -A*
>4.- Commit the designated files to git by typing: *git commit -m "file_name"*
>5.- Push or upload the file to github(online platform) by typing: *git push -u origin main*

>>![건-치](/Images/건-치.jpg)

>### Pull

This one is relatively easier than push.
After you or someone else makes modification in the remote file from github, you must retrieve the change in your local git file. the following is the input used in it.

>1.- ***git pull***: you simply take the modification from the remote files.
>2.- Then, you check the status: git status
>3.- Then, you repeat the process from git add to git commit in order to save it in your files.

And that's everything I've learned in the first week.


![몰루](/Images/몰루.jpg)

