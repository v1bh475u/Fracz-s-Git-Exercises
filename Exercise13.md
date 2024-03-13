We want to change not the last commit but the commit before it.

There is no specific tool for that (_no tool for modifying history_)!

We can use `git rebase` to achieve that.

We will use command `git rebase -i HEAD~x` for editing the last **x** commits.

Then we will enter in an interface. We will change `pick` against the commit we want to edit to `edit`.

Then we will make changes in the file to remove _typos_ and also remove typo from the commit message. 

We will now commit our changes as amend. And then we will use `git rebase --continue` to save our changes.

It can lead to conflicts but we can easily handle them.
