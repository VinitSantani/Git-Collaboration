# Git Terminology and Commands
1. **Repository**: This is a storage area where your projects can live. It can store code, text, images, and anything else that your project may need. This is also sometimes shorthanded as “repo” and can be stored either in an online platform like git hub or locally to your pc.
2. **Clone**: *git clone*  is essentially downloading a local copy of a repo that is hosted somewhere else. For example, cloning a github repo to your local PC
3. **Fork**: Forking allows you to branch off from the master branch and develop a new feature without impacting your main code.
4. **Branch**: *git branch* is basically a duplication of code in a new parallel area. Your master branch is the default and then you can branch off from that. When you are ready to add a feature you can merge the feature branch back with the master branch
5. **Commit**: *git commit* saves the changes to your file in git and pushes them to your main repository
6. **Merge**: *git merge* automatically compiles your code from your new feature branch and merges it with the master branch. It will ensure that no lines of code are written over- if so it will show a merge conflict at which point you can make the necessary changes
7. **Git Checkout**: *git checkout* lets you navigate between the branches created by git branch. Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.
8. **Git Push**: *git push* is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.

9. **Git Pull**: *git pull* is used to fetch and download content from a remote repository and immediately update the local repository to match that content. ... Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit.

10. **Git Add**: *git add* creates a new connection to a remote repository. The "shortname" you provide can later be used instead of the URL when referencing the remote. A typical default shortname is "origin": this is used for the remote which your local repository was cloned from.

11. **Git Remove**: *git remove* disconnects the remote from the local repository. Note that this will have no effect on the actual remote repository (i.e. the repository itself is not removed / deleted / etc.).

12. **Git Rename**: *git rename* renames the remote connection.

13. **Git Status**: *git status* displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.
 
14. **Git Master/Main Branch**: The default branch name in Git is master. As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically. This may now be referred to as the main branch instead of master due to certain social issues in our world today.