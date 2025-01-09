# note 
<!-- List All Branches: -->
git branch


* main
  newbranch

<!-- create a New Branch: -->
git branch newbranch

<!-- Switch to a Branch: -->
git checkout newbranch

<!-- Or, in newer Git versions: -->
git switch newbranch

<!-- Create and Switch to a New Branch (shortcut): -->
git checkout -b newbranch1

<!-- Delete a Branch: -->
git branch -d newbranch

<!-- To work with the newbranch1 branch and eventually merge it into the main branch -->

git checkout newbranch1
-----------
git status

git add .

git commit -m "Updated note.md with new information"


 <!-- Push Changes to the Remote Branch  -->
 <!-- If your newbranch1 exists on a remote repository, push the changes: -->
git push origin newbranch1


<!-- Switch to the main Branch -->
git checkout main


<!-- Merge newbranch1 into main -->
<!-- Merge the changes: -->
git merge newbranch1


