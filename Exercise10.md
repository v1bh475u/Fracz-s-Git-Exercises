In this exercise, we had committed a file with a name but then realised that name is not in proper format as we wish.

We wish to change it. Hence, we use `git mv <current_filename> <new_filename>` instead of just `mv`. 

This is so that git can track the changes or else we would have to use extra commands like start using `mv` to change the name and then using `git add .` to add the changes to **stage state**.

Finally, we commit the changes.