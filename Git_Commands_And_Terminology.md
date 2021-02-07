Git Checkout: This command is used to switch from one branch to another branch.
Git Push: The git push command is used to upload local repository content to a remote repository.
Git Pull: The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content
Git add <shortname> <url>: Creates a new connection to a remote repository. The "shortname" you provide can later be used instead of the URL when referencing the remote. A typical default shortname is "origin": this is used for the remote which your local repository was cloned from.
Git remove <name>: Disconnects the remote from the local repository. Note that this will have no effect on the actual remote repository (i.e. the repository itself is not removed / deleted / etc.).
Git rename <old-name> <new-name>: Renames the remote connection.
Git Status: The git status command displays the state of the working directory, and the staging area
Git Master Branch: The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made.

Git Checkout: The git checkout command lets you navigate between the branches created by git branch . Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.

Git Push: The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.

Git Pull: The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. ... Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit.

Git Add <shortname> <url>: Creates a new connection to a remote repository. The "shortname" you provide can later be used instead of the URL when referencing the remote. A typical default shortname is "origin": this is used for the remote which your local repository was cloned from.

Git Remove <name>: Disconnects the remote from the local repository. Note that this will have no effect on the actual remote repository (i.e. the repository itself is not removed / deleted / etc.).
