##Chapter 17

##Finding Files (find)

##Do more:

> You can put any directory where the . (dot) is.
 Try another directory to start your search there.
 
`find temp -print`
shows all of the contents of the temp directory

`find temp -name "*.txt" -print`
shows all of the files in the directory with the name.txt

> Look for all the video files on your computer starting at
 the home drive and use the > to save the list to a file. 
 
`find ~/ -name "*.mp4" - print > videolist.txt`

##Questions:

> Can you show me all the files in slash temp slash foo?

`find /tmp/foo -print`

> What log files are in your log directory?

```
cd log
find . -name "*.log" - print
```

> Run find in the class directory, pipe the output to pbcopy
and create a gist with the content.  Paste the Gist URL as a 
comment on this story.

```
cd workspace/davinci_coders_t1_2016/
find . -print | pbcopy
```    
