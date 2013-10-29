# MakeGit

A very simple bash shell script to create github repos or gists from the terminal


### Installation

```
$ curl https://raw.github.com/alvaromuir/makegit/master/makegit > makegit && 
  chmod 755 makegit && 
  sudo mv makegit /usr/local/bin/
```

## Example usage

__post a gist:__
```
$ makegit -u alvaromuir:password -t gist -d 'this is a test upload' -p true test_files/test3.m
```

__create a repo:__
```
$ makegit -u alvaromuir -t repo -n 'test_js_repo' -g 'javascript' -p true  -h "http://www.muiral.com/github/js"
```

__note:__ _a username alone w/o a password will prompt for one._


ToDo

DELETE repos and gists !

Alvaro Muir, @alvaromuir