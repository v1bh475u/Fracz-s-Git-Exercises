Here, we didn't want to track a file but after committing it, we added it to the **.gitignore**.

Hence, the changes in it were being tracked. We wanted to remove it from our working tree and index.

To do this, we used `git rm <filename>` and then committed it to update our working tree.
