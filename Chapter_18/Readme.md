##Chapter 18

##Look Inside Files (grep)

##Do more:

> Use quotes to find "new file" and "old file" and "This is".

```
grep "new file" *.txt
grep "old file" *.txt
grep "This" *.txt
grep -i "this" *.txt
```

> Take the list of videos you created (or any other list) and
use it to find some videos you want to find.

```
grep "git" videolist.txt
Users/dcasserleigh//workspace/davinci_videos/git_review_with_tim/Git - Part 1.mp4
/Users/dcasserleigh//workspace/davinci_videos/git_review_with_tim/Git - Part 2.mp4
/Users/dcasserleigh//workspace/davinci_videos/git_review_with_tim/Git - Part 3.mp4
/Users/dcasserleigh//workspace/davinci_videos/in_class/git_101.mp4
/Users/dcasserleigh//workspace/davinci_videos/in_class/git_101_warmup.mp4
/Users/dcasserleigh//workspace/davinci_videos/in_class/git_102.mp4
/Users/dcasserleigh//workspace/davinci_videos/in_class/git_branching_homework_review.mp4
/Users/dcasserleigh//workspace/davinci_videos/in_class/questions_gitignore_mine_autocomplete.mp4
```

##Questions:

> Show me the lines in foo.txt that have "ERROR" in them.

`grep "ERROR" foo.txt`

> Show me the lines in bar.txt that have "davinci" in them.

`grep "davinci" bar.txt`

> Can you print all the lines in text files that have your
 first and last name in them?
 
 `grep -i "Douglas Casserleigh" *.txt` 
 
> What does the -i option to grep accomplish?
 
 `grep -i` deactivates case sensitivity when looking for
  words or letters in files.
