# intitialize database 

heroku run console
require './app.rb'
DB.run("create table beers (name text, brewery text)")
