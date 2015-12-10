git clone

this command lets you download and setup a new repository that exists on github or elsewhere.
Example:

git clone git@github.com:jarnoveldhuis/learning.git wxyz

in this example wxyz will be the name of the folder that contains the contents of the repository "learning"

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git status

this command shows you what files have changed in your local directory compared with what has been committed on your local repository.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git diff

this command show you what has changed exactly inside all the files comparing your local files to the local commit tree

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git add

this command "stages" changes, in preparation for committing them

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git commit 

this command "lock in" staged changes and makes them "official"

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git push

this command sends all of your commits to another "clone" of the same repository

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git pull

this command pulls all the commits from one place to your local "clone" of a "repository"

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git branch

this command does lots of branch stuff... without any parameters it will show you all the branches that your local machine knows about

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

git checkout

this is a very magical command that does many many things. The person who made git should be ashamed of themselves.
"git checkout -b xyz" will copy the current branch and make a new one identical to it called in this example "xyz"

