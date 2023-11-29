its the folder in which 


## understand your project 

local reporsity - the .git folder that gets added after running gi init. 

it saved changes made it working directory in the staging area. 

from wokring idrectory to staging area, intemidate- im not ready to push it yet cause its not working
then I'll commit and push it. 
``` 
git add . 

```

``` 
git add <filename>
```

Step 2 

commit any changes (Move them to local repository). 
```
git commit
```

a label of the changes that you made. 

git add ./ file you want to stage
git diff --staged  compares stage and local repository 
git diff - compares changes in working directory and staging area.  press q to get out of the preview mode
git commit -m "description" 
git pull origin main 



## what is git?

its a version control system that makes collaboration on the same code base easy
work on the same base without interuppting each other. 
We can access the histoy of writing the code. if we break something we can go back in time. 

### 3 areas related to Git

- Working directory
- Staging area
- Local repository 

Remote repositiory (what's hosted on github website)

we could create a repository on github and clone it.

git push -u origin main (do it the first time) -u flag all we have to do is 
```
git push
```
if we dont use dash here we have to use the full version of the command. 

## a few more useful commands 

git fetch would only  update our local repository 

git merge - update working directory. 

create a repository and clone and work on the repository together 

1. 1 person creates the repository. 
2. Invite collaborator. 
3. clone the repository 
4. person one should add a html file with a pararagraph with their name. push their changes. 
5. person two will pull the changes and add a ccs file with some styling. 
6. person two will push the changes.  
7. person 1 will pull the changes. 

dont want to touch my main branch i want to make a new branch, then get someone to check it to see if its correct and then have it released to the main branch. 

git branch - shows the branchs you have
git branch naming convention creates a new branch 
git checkout name of branch - changes to the branch i wish to be on. 

once i finished my tash on a branch I need to add it to the main version 
a pull request - open a pull request. 

main - the code that is deployed
- develop branch 
send it all feautures together into develop and then it gets sent to main.
in develop they run tests to check the versions of the code and make sure its not effecting someone else code. 
merge to development and then into main. 
hotfix/some-bug-fix. 



1. Create a repository called nology-challenges-yourname
2. Add a readme file
3. Create a branch called feature/about-me
4. make an html and add a paragraph about you to that branch 
5. open a pull request to main and merge
6. make sure your local main is up to date with remote main 
7. create another branch called feautre/styling
8. Add some styling to the html file. 
9. puh that code open a pull request, merge to main 
10. and then make sure local main is up to date with remote. 