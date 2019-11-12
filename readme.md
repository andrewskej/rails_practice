# Rails commands... no ruby (you go figure)

<!-- create new project -->
### rails new [projectname]

<!-- run server -->
### rails -s  ||  rails server

<!-- create DB ... newer version of rails seems to do it automatically -->
### rails db:create

<!-- migrate the DB created -->
### rails db:migrate

<!-- do them in once -->
### rails db:create && db:migrate

<!-- scaffold -->
### rails g scaffold [name] [feature]:[type] [feature]:[type]


<!-- ralis build for api mode (no front view!)...awesome...-->
### rails new [project] --api -T  

<!-- controller generator -->
### rails g controller [name], [name], [name]

<!-- model generator -->
### rails g model [name(singular)] [attribute:type]
#### after making a model,   rails db:migrate  <- is needed to update the db schema

<!-- resource generator -->
### rails g resource [Name] [attr:type]

<!-- get routes...so nice -->
### rake routes
### rake routes | grep [routename]