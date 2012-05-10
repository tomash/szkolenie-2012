!SLIDE bullets

# Rails Routing

## config/routes.rb
### http://guides.rubyonrails.org/routing.html


!SLIDE

# Routing klasyczny

## /:controller/:action/:id


!SLIDE

# Routing dowolny

## /articles/:filename


!SLIDE

# REST

## REpresentational State Transfer


!SLIDE bullets

* styl projektowania architektury serwisów [komunikujących się ze sobą] w rozproszonym środowisku
* opisany w pracy doktorskiej Roya Fieldinga z roku 2000
* opozycja do SOAP i RPC
* zorientowanie na zasób (resource)


!SLIDE bullets

# MOAR?

* http://en.wikipedia.org/wiki/REST
* http://tiny.pl/n3sq


!SLIDE bullets

# REST a HTTP

### GET, POST
### PUT, DELETE


!SLIDE

# _zasób_ (resource)


!SLIDE bullets incremental

## czasowniki HTTP a CRUD

* POST - CREATE
* GET - READ
* PUT - UPDATE
* DELETE - DELETE (!)


!SLIDE bullets incremental

# konwencja REST w ścieżkach

* POST /resources - create
* GET /resources - index
* GET /resource/:id - show
* PUT /resource/:id - update
* DELETE /resource/:id - destroy


!SLIDE bullets

# REST w Rails

* Rails od wersji 2.0 to wzorcowy framework do aplikacji RESTful
* zasób -> model (ale nie zawsze!), 
* kontroler wyłącznie jako pośrednik


!SLIDE

# Zasoby naszej aplikacji

### Post
### Komentarz