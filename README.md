# README

```sh
$ rails _6.0.4_ new rails-tutorial-toy-app
$ cd rails-tutorial-toy-app/
$ bundle _2.2.17_ config set --local without 'production'
$ bundle update
$ bundle _2.2.17_ install
$ rails generate scaffold User name:string email:string
$ rails db:migrate
```