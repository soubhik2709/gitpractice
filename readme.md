# this is making from local syetem. 
 Now im going to create a branches for learning purpose , 
 <br>
 now creating new branch , it name is feature1.
 <br>
 Now creating 2nd branch i.e. feature2,
<br>
  git branch
  feature1
* feature2, 
<br> 
now im going to delte feature2 branch  
git branch -d feature2
Deleted branch feature2 (was 96a595c).
<br>
now im gonna add new feature on the feature1 branch. on idex.html new p tag...so after new p tag, the git status is showing us <br>
 git status 
On branch feature1
Changes not staged for commit:
modified:   index.html
 modified:   readme.md
<br>
after add new feature on feature1  , if i go on another branch then the changes are not showing on that brunch. but before going on the  another branch , we have to commit the changes otherwise it will overwritten on another branch.
<br>git commit -m"the html and readme file has updated on the feature1 branch"
[feature1 1083c83] the html and readme file has updated on the feature1 branch
 1 file changed, 4 insertions(+), 2 deletions(-)
<br>
now for pushing this change branch and other not changes branches together , by git push origin __the current branch name