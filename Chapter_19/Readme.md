##Chapter 19

##Getting Command Help (man, HELP)

##Do More:

> Use man or help to look at every one of the commands
you have in your list to memorize.

```
man pwd
man hostname
man mkdir
man cd
man ls
man rmdir
man pushd
man popd
man cp
man mv
man less
man cat
man xargs
man find
man grep
man man
man apropos
man env
man echo
man export
man exit
man sudo
man chmod
man chown
```

##Questions:

> What option to ls tells it to output file size in human readable form?

`man ls`
`ls -h`

> Is there a case insensitive option to grep?

`man grep`
`grep -i`

> What does the -r and -f options to rm do exactly?

`man rm`

```
-R          Attempt to remove the file hierarchy rooted in each file argument.  The
                 -R option implies the -d option.  If the -i option is specified, the
                 user is prompted for confirmation before each directory's contents are
                 processed (as well as before the attempt is made to remove the direc-
                 tory).  If the user does not respond affirmatively, the file hierarchy
                 rooted in that directory is skipped.

     -r          Equivalent to -R.

-f          Attempt to remove the files without prompting for confirmation,
 regard-less of the file's permissions.  If the file does not exist, do not dis-
```

> What does the ifconfig command do?

`man ifconfig`

The `ifconfig` is a utility that is used to assign an address to a network interface 
and/or con-figure network interface parameters.
