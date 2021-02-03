# httpie

https://httpie.io/

## Version

- httpie: latest
- alpine: 3.12.3

## Setup

`docker build -t http .`

## Usage

`docker run --rm -it http <command>`

`docker run --rm -it https <command>`

### zsh

```
vi ~/.zshrc

# 以下を追記
alias http="docker run --rm -it http http "
alias https="docker run --rm -it http https "
```
