#Chapter 11

##Moving a File (mv)
  
##Do More

> Move a file in the newplace directory to another directory then
 move it back.

```
cd newplace
mv awesome.txt newerplace
cd ..
cd newerplace
mv awesome.txt newplace
```

##Questions:

> Can you rename foo.txt to blah.txt?

`mv foo.txt blah.txt`

> Can you move the production.log file in the log directory to
  slash temp?

```
mkdir log
cd log
echo "log" > production.log
mv production.log /tmp
```
  
  
  
