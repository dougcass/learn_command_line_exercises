##Chapter 21

##What's in Your Environment (env, echo)

#Do more:

> I want you to go online and research how you change your PATH for your computer.
Try to do it entirely from the CLI.

In order to change the PATH for my computer I would edit the .profile file in my
home directory. You would add your new directory in to the path by adding a `:/new_directory`
to the end of the path that begins `export PATH=`


##Questions:

> What is your shell set to?

`echo $SHELL`
```
/bin/bash
```
> What directory are you in (don't use pwd this time)?

`echo $PWD`

> What is your home directory set to?

`env`
```
/Users/dcasserleigh
```
> Can you set your environment to have DEBUG set to true?

`export DEBUG="true"`
