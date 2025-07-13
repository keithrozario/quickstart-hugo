# Quick Start Hugo

Learning Hugo and JJ in one go.

Probably not a good idea.

## Hugo

Used to write blogs

## JJ

A new VCS, that's probably more agent friendly :)

-keith

### JJ Workflow

	$ jj new main@origin # creates a new revision on this bookmark
	$ jj bookmark move main -to @-  # moves the bookmark to the current working revision
	$ jj git push # pushes to the git repo

Others:

	$ jj bookmark create main@origin  # creates a bookmark 'main' at origin. 
	$ jj git remote add https:.// ..... # adds a new remote 
	$ jj git push --allow-new # pushes all bookmarks to git

Bookmarks are synonymous to branches in git. The main bookmark of jj will map the main branch in git.

the `allow-new` allows you to push new bookmarks to remote. By default only bookmarks/branches that exists in
the remote git repo will be pushed.


