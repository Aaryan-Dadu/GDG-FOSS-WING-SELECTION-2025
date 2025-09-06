### Answer the following questions in you own words.

> It's not necessary that you havee to know and answer all the questions. Just answer the ones
> you know and write in your own words.

1. Give the difference between the remotes - upstream and origin - with an example.

You answer: Consider after reading the documentation.md you get fascinated by the concept of POML and want to contribute in it, so you fork the official POML repo names that fork My-POML and then clone it on your local system. Now, the remote origin is the fork i.e. My_POML and the remote upstream is the original repo which you forked i.e. POML.

2. You have two branches A and B and you have currently made some changes in branch A.
You want to move into branch B but do not want to commit the current changes in branch A.
What will you do?

You answer: will save those changes without saving them by stashing them then would freely switch branches.

3. You were assigned a work to implement a feature and create a PR to your organization's remote repository.
For this you made a branch (say A) and made some changes and commited them. Now you moved to some other branch 
(say B) to do some other assigned work. But later you realisd that have to complete the task assigned earlier 
first and commited some changes in branch B which are meant for branch A. How will you use git to bring the 
changes from branch B to branch A?

You answer: 

3. What is the difference between fetching changes and pulling changes?

Your answer: fetching just fetches the changes of the remote repository letting us to compare the states while pulling leads to merging the changes in the remote repository with the local repository.

4. What does -i flag stand for? What is it's significance in git?

You answer: interactive

5. You are working in an organization that follows very strict guidelines for PRs and commits.
You made three commits in your PR and the maintainer says you were supposed to make a single commit.
What will you do in this case?

You answer: squash those commits into one then will force push the squashed commit history.

6. Explain `git merge` and `git rebase` with example(s).

You answer: git merge is used to merge the states of the two branches and it generates a merge commit while git rebase connects the head of the branch to the tail of the other branch and updates the head to the head of the other branch.

7. Write the flow how you create a repository and push changes to it. Also mention the commands used at each step.

You answer: I create a remote repo then clone it locally using ``git clone <link>``, makes the required changes then then stage them using ``git add .`` , then commit it ``git commit -m "Name"`` , lastly pushes it. 

8. How would you prevent a file or folder from getting tracked by git?

Your answer: using .gitignore

9. You did not implement the step you mentioned in question 8 and now you have committed and pushed your database's
secret key to the github. How will you remove the key from your git's commit history to avoid any misuse?

You answer:

---