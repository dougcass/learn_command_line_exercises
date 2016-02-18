#Chapter 7

##Remove Directory (rmdir)

##Do More

> Make 20 more directories and remove them all
```
mkdir 1
rmdir 1
mkdir 2
rmdir 2
mkdir 3
rmdir 3
mkdir 4
rmdir 4
mkdir 5
rmdir 5
mkdir 6
rmdir 6
mkdir 7
rmdir 7
mkdir 8
rmdir 8
mkdir 9
rmdir 9
mkdir 10
rmdir 10
mkdir 11
rmdir 11
mkdir 12
rmdir 12
mkdir 13
rmdir 13
mkdir 14
rmdir 14
mkdir 15
rmdir 15
mkdir 16
rmdir 16
mkdir 17
rmdir 17
mkdir 18
rmdir 18
mkdir 19
rmdir 19
mkdir 20
rmdir 20
```
> Make a single path of directories that is 10 deep and remove them one at a time like I did above.
```
mkdir -p 1/2/3/4/5/6/7/8/9/10
cd 1//2/3/4/5/6/7/8/9
rmdir 10
cd ..
rmdir 9
cd ..
rmdir 8
cd ..
rmdir 7
cd ..
rmdir 6
cd ..
rmdir 5
cd ..
rmdir 4
cd ..
rmdir 3
cd ..
rmdir 2
cd ..
rmdir 1
```
##Questions:

>Can you remove the tmp directory?

`rmdir tmp`
No you cannot remove the tmp directory because the directory is not empty.





