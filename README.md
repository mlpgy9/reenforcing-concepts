###STEPS IN MAKING NEW PROJECT

1.	Clone a copy of the News Apps Template from Chris’ Git page
2.	Rename the repository locally. Already in a single git command.

Git command to clone and rename a repository locally:
```
$ git clone [repository address here] file-name-here
```

###TO SAVE TO MY REPOSITORY
1.	Add all untracked files to the repository
```
$ git add . OR $git add –A (. =all)
```
2.	Create a new repo on MY Git page
Open your Git page, create and name a new repository.
3.	Remove the original ORIGIN (which links to Chris’ Git page)
```
$ git remote rm origin
```
4.	Add MY origin to the repository 
```
$git remote add origin [address copied from the newly-created repo]
```
5.	Commit my changes
```
$ git commit –am “describe your changes here”
```
6.	Push to my new repository
```
$ git push origin master
```