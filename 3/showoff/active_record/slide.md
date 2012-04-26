!SLIDE title-slide

# ActiveRecord


!SLIDE bullets incremental

# ActiveRecord skrótowo

* Wzorzec projektowy realizujący ORM
* Martin Fowler: Patterns of EAA
* Implementacja w Railsach uważana za wzorcową, choć jest nieortodoksyjna
* Budzi zazdrość u użytkowników innych narzędzi / języków / frameworków ;)


!SLIDE 

# literatura?

## api.rubyonrails.org


!SLIDE

# konwencja ponad konfiguracją

## Railsy przyjmują i promują pewne nazewnictwo (i strukturę), ale wszystko (większość) można nadpisać.
### _Wszystko powinno być tak proste i łatwe, jak to możliwe, ale nie prostsze._

!SLIDE bullets

# konwencje w AR

* klasa o nazwie w CamelCase
* tabela w bazie our\_object*s*
* klucz główny: id
* klucz obcy: object\_id
* **wszystko można nadpisać**


!SLIDE bullets incremental

# tworzenie i edycja rekordów

* Model.new
* obj#attributes, obj#pole, obj#pole=
* obj#save vs. obj#save!
* Model.create
* obj#destroy


!SLIDE bullets incremental

# wyszukiwanie

* .find(id) - jeden wiersz
* .where(warunki)
* .where(warunki).order, method chains
* dynamic finders: find_by_title


!SLIDE bullets incremental

# łatwe deklarowanie relacji

* belongs\_to :something
* has\_one, has\_many
* has\_and\_belongs\_to\_many
* has\_many :through


!SLIDE bullets

# that's NOT all, folks!

* walidacje
* callbacks
* asocjacje polimorficzne
* dziedziczenie, STI
