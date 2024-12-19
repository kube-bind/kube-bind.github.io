# kube-bind.io

This repository contains the [Hugo](https://gohugo.io) files for [kube-bind.io](https://kube-bind.io), the official website of the kube-bind project.

## Development

To set up a local development environment, make sure to have `git`, `npm` and `hugo` available. After checking out the repository, make sure dependencies and submodules are pulled:

```sh
$ npm ci && git submodule update --init
```

Afterwards, run `hugo` and visit [localhost:1313](http://localhost:1313):

```sh
$ hugo serve
```
