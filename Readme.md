# svn-client
Old SVN clients to work with old svn repositories.

## How to use it
Run svn client
```
docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" -u $(id -u):$(id -g) nbrun/svn-client:latest svn
```

Use alias
```
alias svn='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" -u $(id -u):$(id -g) nbrun/svn-client:latest svn
```

## Docker Hub
https://hub.docker.com/r/nbrun/svn-client/
