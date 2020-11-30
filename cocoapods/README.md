# CocoaPods

## Version

- CocoaPods: 1.10.0
- Ruby: 2.7

## Setup

`docker build -t cocoapods .`

## Usage

`docker run --rm -v $PWD:/app cocoapods pod <command>`


### zsh

```
vi ~/.zshrc

# 以下を追記
alias pod=docker run --rm -v $PWD:/app cocoapods pod`
```
