To set Github pages

        1.Go to settings after creating repo, There is option for gh-pages select the branch and save.
    or  2.create a new branch as gh-pages
    
    
To github pages up-to-date from master branch

cmd for sync with master and other branches

git add .
git status // to see what changes are going to be commited
git commit -m 'Some descriptive commit message'
git push origin master


sync with master branch
switch branches

git checkout gh-pages // go to the gh-pages branch
git rebase master // bring gh-pages up to date with master
git push origin gh-pages // commit the changes
git checkout master // return to the master branch


