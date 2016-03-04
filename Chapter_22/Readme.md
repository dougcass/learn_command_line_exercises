##Chapter 22

##Changing Environmental Variables

##Do More:

> Read the man page for env again. What else can it do?

```
-i      Execute the utility with only those environment variables specified by
             name=value options.  The environment inherited by env is ignored completely.

     -P altpath
             Search the set of directories as specified by altpath to locate the speci-
             fied utility program, instead of using the value of the PATH environment
             variable.

     -S string
             Split apart the given string into multiple strings, and process each of the
             resulting strings as separate arguments to the env utility.  The -S option
             recognizes some special character escape sequences and also supports envi-
 ```
 
##Questions:

> Can you set the debug environment variable to true?

`export DEBUG="true"`

> Can you remove the debug environment variable?

`unset DEBUG`

> My environmental variables and what they do.

`TERM_PROGRAM=iTerm.app`
Displays the name of your terminal program

`GEM_HOME=/Users/dcasserleigh/.rvm/gems/ruby-2.2.4@homework-tester`
Tells RubyGems where to find or install gems from.

`SHELL=/bin/bash`
Pathname to you login shell

`CLICOLOR=1`
Variable for color sequences to distinguish file types

`IRBRC=/Users/dcasserleigh/.rvm/rubies/ruby-2.2.4/.irbrc`
Shows gems and ruby version used in irbc

`TMPDIR=/var/folders/mh/51c7dt5s6hj56v0h_l83mj_m0000gn/T/`
Shows location of the temp directory

`OLDPWD=/Users/dcasserleigh/workspace/davinci_coders_t1_2016/homework`
Shows path to the directory above your current working directory

`MY_RUBY_HOME=/Users/dcasserleigh/.rvm/rubies/ruby-2.2.4`
Shows the gems and ruby version installed on the computer

`USER=dcasserleigh`
Shows current user

`PATH=/Users/dcasserleigh/.rvm/gems/ruby-2.2.4@homework-tester/bin:/Users/dcasserleigh/.rvm/gems/ruby-2.2.4
@global/bin:/Users/dcasserleigh/.rvm/rubies/ruby-2.2.4/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:
/Users/dcasserleigh/.rvm/bin`
Shows directories that contain executable programs

`PWD=/Users/dcasserleigh/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises`
Shows current working directory

`LANG=en_US.UTF-8`
Shows locale category for native language


