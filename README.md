# MakeGit

A very simple bash shell script to create github repos or gists from the terminal

##example usage

post a gist
$ makegit -u alvaromuir:password -t *gist* -d 'this is a test upload' -p true test_files/test3.m


create a repo
$ makegit -u alvaromuir -t *repo* -n 'test_js_repo' -g 'javascript' -p true  -h "http://www.muiral.com/github/js"
note: a username alone w/o a password will prompt for one.


ToDo

DELETE repos and gists !

Alvaro Muir, @alvaromuir

