Usage:

``` bash
docker run -v $(pwd):/cwd [-v $HOME/.ssh:/root/.ssh:ro] vmoebius/git-lfs:latest <command> [<args>]
```

e.g.

``` bash
docker run -v $(pwd):/cwd vmoebius/git-lfs:latest clone git@github.com:vmoebius/dockerfiles.git
```

or

``` bash
docker run -v $(pwd):/cwd vmoebius/git-lfs:latest lfs track
```
