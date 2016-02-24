###Starting a new project

1) Clone a copy of the News Apps Template from Chris’ Git page.
2) Rename the repository locally. Already in a single git command.

Git command to clone and rename a repository locally:
$ git clone [repository address here] file-name-here

###Save to YOUR repository:

1.) Add all untracked files to the repository.
$ git add “js/data.json”

$ git add .
OR
$ git add -A

2.) Create a new repo on YOUR Git page.
Open your Git page, create and name a new repository.

3.) Removed the original ORIGIN (which links to Chris’ Git page)
$ git remote rm origin

4.) Add YOUR origin to the repository
$ git remote add origin [address copied from your newly-created repo]

5.) Commit your changes.
$ git commit -am “Note”

6.) Push to repo.
$ git push origin master

(Use Git Command Markdown Language)