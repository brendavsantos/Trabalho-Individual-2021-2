FROM ruby:3.0.0

WORKDIR /app

COPY . /app
RUN bundle install

RUN docker network create biblioteca-network