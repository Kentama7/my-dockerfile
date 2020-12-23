# jq

## Version

- jq: latest
- alpine: 3.12.3

## Setup

`docker build -t jq .`

## Usage

`docker run --rm -i jq <command>`

```shell
echo '{"foo": 0}' | docker run --rm -i jq .
{
  "foo": 0
}
```


### zsh

```
vi ~/.zshrc

# 以下を追記
alias jq="docker run --rm -i jq "
```
