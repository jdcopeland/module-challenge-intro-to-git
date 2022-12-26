## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a version control system that tracks the history of changes as people and teams collaborate on projects together. As developers make changes to a project, any earlier version of the project can be recovered at any time. Developers can review a project's history to find, which changes were made, who made the changes, when were the changes made and why were the changes needed.

2. What is the difference between Git and GitHub?
Git is a version control system that allows you to manage and keep track of your source code history. GitHub is a cloud-based hosting service that allows you to manage Git repositories. Git is an open source software maintained by Linux, while GitHub is owned and maintained by Microsoft.

3. Why do we create a branch?
Developers create branches to allow for development of features, bug fixes or to safely experiment with new ideas in a contained area of a repository. Users always create a branch from an existing branch, typically the default branch of your repository.

4. What is the purpose of a Pull Request?
Pull requests allow users to tell others about changes they have pushed to a branch in a repository on GitHub. Once a pull request is opened, users can discuss and review potential changes with collaborators and add follow-up commits before changes are merged into the base branch.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
$ git checkout <existing-branch-name>

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The `git fetch` command helps users download commits, refs, and files from the remote repository to the local repository.  Executing this command will allow users to see all the updates on the remote repository.

The `git merge` command is the confirmed conclusion of the user's decision to incorporate the changes they viewed using the `git fetch` command. As suggested by the command's name (`git merge`), users are confirming to "merge" these changes in the repository.

The `git pull` command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

7. What is a merge conflict?
Merge conflicts occur when users merge branches that have competing commits, and Git needs the users' help to decide which changes to incorporate in the final merge.

8. How do you resolve a merge conflict?
To resolve a merge conflict, the user must manually edit the conflicted file to select the changes that they want to keep in the final merge. There are a couple of different ways to resolve a merge conflict:

	1) If the merge conflict is caused by competing line changes, such as when 	people make different changes to the same line of the same file on different 	branches in the Git repository, you can use the conflict editor on GitHub to 	resolve the conflict.
	2) For all other types of merge conflicts, users must resolve the conflict in a 	local clone of the repository and push the change to their branch on GitHub.