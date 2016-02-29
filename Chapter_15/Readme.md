##Chapter 15

##Pipes and Redirection

##Do more:

##Questions:

> Can you put "This class is fun" into bar.txt?

`echo "This class is fun" > bar.txt`

> Can you put "Oh so much fun" into foo.txt?

`echo "Oh so much fun" > foo.txt`

> Explain what the |, <, > and >> commands do in your own words.

The `|` command directs the output of the command on the left of 
the pipe to the command on the right of the pipe.

The `<` command will direct the content from the file to the right
of the < symbol to the command to the left of the < symbol.

The `>` command directs the output of the command on the left of 
the > symbol and writes it to the file on the right of the > symbol.

The `>>` command directs the output of the command on the left of
the >> symbol and adds it to the end(or appends) of the file on the right of
the >> symbol.  
