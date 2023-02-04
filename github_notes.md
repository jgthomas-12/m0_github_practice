# GitHub Notes

To check your own understanding of GitHub, answer the questions that follow.

1. **What is the purpose of GitHub?** Share files using a cloud-based storage system. Keep backups and storage. 
1. **What is the difference between forking and cloning a repository?** Forking gets the repository linked to your computer via the cloud. Cloning makes a copy of that forked repository and puts it on your personal computer. 

## What's gone on so far

- I opened this file in a different directory called "delete" and cloned it into that directory. I then connected that file to the github repository. I added some things into this same file, pushed everything to github and then I deleted the folder. I watched those files get crossed out in red on a different vscode window and then I reopened this initial file to find none of those changes. I'm assuming i would have to `git pull` to retrieve those changes and it SEEMS like they're still available on GitHub even though they've been deleted on my local terminal. 

- I'm now going to git add, git commit and git push this to github and I expect it to either line up and keep the old versions or throw errors. 
## Shazam 
## Shazam 2
## Shazam 3
## SHAZAM 4

- So I first did the git remote add origin <SSH>, tried to push and got error messages about having "No upstream branch". I had to set the upstream branch using `git push -u origin main`

- I received errors. I believe I need to retrieve the information before being able to edit the file some more. 
```
To github.com:jgthomas-12/m0_github_practice.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:jgthomas-12/m0_github_practice.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```
