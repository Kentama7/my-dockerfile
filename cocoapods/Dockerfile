FROM ruby:2.7-alpine

RUN gem install cocoapods -v 1.10.0
RUN adduser cocoapods
USER cocoapods
RUN pod setup
WORKDIR /app
