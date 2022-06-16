### Rails basic application
*   web application framework for ruby
*   follows MVC architecture
*   uses puma as webserver
*   default port => ```localhost:3000```
*   ERB is a templating system that evaluates Ruby code embedded in a document.

create a new rails project
```
rails new <project name>
```
start the dev server
```
rails s
```
create a controller
```
rails generate controller <controller name> <function name>
```
create a model
```
rails generate model <table_name> <column1 name>:<type> <column2 name>:title
rails db:migrate
```
db interactive consloe
```
ruby console
```
list all the routes
```
rails routes
```
file structures
```
app/ => contains models, views, controllers
config/ => contains application routes **entry point**
db/ => contains sqlitedb, migration files

```

references:
*   https://guides.rubyonrails.org/getting_started.html
*   free ruby ebooks : https://github.com/EbookFoundation/free-programming-books/blob/main/books/free-programming-books-langs.md#ruby
