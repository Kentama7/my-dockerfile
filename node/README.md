# node

Reactやるときように以下を追加

- typescript
- ts-node
- typesync

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

### zsh

```
vi ~/.zshrc

alias node='docker run --rm -it -v "$PWD":/app --entrypoint /usr/local/bin/node node'
alias yarn='docker run --rm -it -v "$PWD":/app -p 3000 --entrypoint /usr/local/bin/yarn node'
```

