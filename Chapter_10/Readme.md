#Chapter 10 

##Copy a file (cp)

##Do More

> Use the cp -r command to copy more directories with files in them.

`cp -r newplace newerplace`
With this command I created a new directory called newerplace and 
copied the contents of the newplace directory into it.  The
awesome.txt file that was located in newplace is now also exists 
in the newerplace directory.

> Copy a file to your home directory or desktop.

`cp awesome.txt cd`
With this command I copied awesome.txt to the home directory.


##Questions:

> Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)
```
echo "foo" > foo.txt
cp foo.txt /tmp
```

> Can you copy .bash_profile in your home directory to the current
 directory?

> What is Robocopy?

Robocopy, or "Robust File Copy" is an application tthat allows users
to copy entire folders using the command line interface.  Robocopy 
is a Windows apllication and is not available for the Mac OS.
 
