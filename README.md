# dokku-git-info
Fetches some information for the revision hash and the git repo and sets it in environment variables. It sets these three (with an example value).

```
GIT_REV=f85239dc961012a3d4de65a69768fbf0432a7617
GIT_VERSION=1.8.1
GIT_COMMITDATE=Mon Oct 9 16:47:05 2017 +0200
```

## requirements

- git
- dokku 0.4.0+
- docker 1.6.x

## installation

```shell
# on 0.4.x
dokku plugin:install https://github.com/StefSchenkelaars/dokku-git-info.git git-info
```
