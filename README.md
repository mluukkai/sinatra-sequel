# introduction

A simple app for Tietokantojen perusteet to try out sql in wild

[https://tsohatesting.herokuapp.com](https://tsohatesting.herokuapp.com)

## initializing database 

```ruby
heroku run console
require './app.rb'
DB.run("create table beers (name text, brewery text)")
```

## console 

```ruby
bundle exec irb -r ./src.rb
```
