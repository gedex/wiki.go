Wiki.go
=======

My first stab at writing web apps in Go by folllowing [this article](http://golang.org/doc/articles/wiki/).

## Run it

~~~
go build wiki.go
./wiki
open http://localhost:8080
~~~

## TODO

* Add configuration file
* Use DB instead of text files.
* Add user login and register handler
* Use session for logged-in user
* Add history of a Page
* Add diff of a Page revision
* Allow Markdown syntax and/or safe HTML markups
