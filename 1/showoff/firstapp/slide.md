!SLIDE

## Nasza pierwsza aplikacja w Rails

### Nie znamy Ruby'ego, poznaliśmy zaledwie filozofię Railsów... no i co z tego? ;)


!SLIDE command

    rails new blog


!SLIDE command

    cd blog
    rails s


!SLIDE title-slide

http://guides.rubyonrails.org/getting_started.html


!SLIDE command

    rails generate scaffold Post \
      title:string content:text


!SLIDE

## jeden mały babol
### dodajemy do Gemfile w grupie 'assets'

    gem 'execjs'


!SLIDE

# bawimy się!