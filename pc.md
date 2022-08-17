## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?



1. Git is a Version control system, it's a way for multiple developers to access a project simultaneously, using it we can
create different branches(sections in which copies of the original code can be altared without affecting the original)
2. Git
is the software on your machine, Github is a website where we can upload our projects to, a space in the cloud that we can
save a copy of our project to.
3. If we want to work on a project without affecting the original code we would create a
branch, think video games, you have your completed game running on one branch (everyone can play it, all the bugs have been
ironed out hopefully(unlikely)) and a test branch that has some added new features(new features might bring bugs, maybe
something game breaking so we want to test these changes in an isolated environment that won't affect our perfectly(unlikely)
functioning game.
4. a pull request is a function we can use to submit our changes to a branch in a manner that it can be
reviewed(by a senior developer most likely) before actually being merged into that branch.
5. git checkout "branch name"
6. git pull = downloading the code from the remote repository(github) to your local repository. git fetch = checks the remote
repository to see if any changes are available(Does not download it to your local repository). git merge = How we combine the
code from different branches into one
7. A git merge conflict occurs when git cannot automatically integrate the differences
between two commits, say two developers are editing the code, developer 1 has pushed changes which have already merged,
developer 2 is unable to push their changes as developer 1 has already edited the code on the remote repository.
8. Git may return an error message that would suggest what changes need to be made in order to resolve the conflict, perhaps altaring one of the conflicting files(manually removing the conflict)

