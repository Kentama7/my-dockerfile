# Reactやるときに使うやつ

## version

- node: 14.4.0

## Setup

```shell
docker build -t node .
```

## Usage

```shell
# node
docker run --rm -it --entrypoint /usr/local/bin/node node <command>
# yarn
docker run --rm -it --entrypoint /usr/local/bin/yarn node <command>
# ts-node
docker run --rm -it --entrypoint /usr/local/bin/ts-node node <command>
```

## alias

### zsh

```
vi ~/.zshrc

alias node='docker run --rm -it --entrypoint /usr/local/bin/node node'
alias yarn='docker run --rm -it --entrypoint /usr/local/bin/yarn node'
```

