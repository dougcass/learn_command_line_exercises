#Chapter 9

##Making Empty Files (Touch, New-Item)

##Do More
`mkdir touchtest`
`cd touchtest`
`touch hello.txt`
`cd ..`
`rmdir touchtest`
I then recieved the error 'directory is not empty'.
This error indicates that I cannot remove the touchtest directory because
I had created an empty file in the touchtest directory.


##Questions:
###Can you touch blah.txt?
`touch blah.txt`
###Let's create foo.txt.
`touch foo.txt`
###What happens if you touch an existing file?
The date that the file is accessed or modified is updated.

