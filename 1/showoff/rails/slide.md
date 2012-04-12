!SLIDE bullets incremental

# Filozofia Rails

* podobnie jak w Ruby - uczynienie programowania przyjemnym
* abstrakcja wyciągnięta z prawdziwych projektów
* "Opinionated Software"
* Konwencja Ponad Konfiguracją


!SLIDE bullets incremental

# Implementacja Rails

* wzorzec Model-View-Controller
* zasada DRY: Don't Repeat Yourself
* możliwość pracy iteracyjnej, w małych krokach (Agile)
* struktura katalogów i szkielet aplikacji: app/, config/, public/


!SLIDE bullets incremental

# flow

* start, załadowanie konfiguracji, połączenie z bazą itd.
* podstawowy cykl przetwarzania żądania HTTP
* klient -> żądanie HTTP -> routing -> kontroler -> widok -> klient


!SLIDE bullets incremental

# Kontrolery i Widoki

* kontroler: akcja -> metoda klasy
* @zmienne @instancyjne dostępne w widokach
* widoki: szablony, np. .html.erb
* helpery: metody dostępne w widoku


!SLIDE bullets incremental

# ActiveRecord - warstwa Modelu

* wzorzec projektowy, ORM
* metody klasy, metody instancji
* kolumna = pole = metoda
* Model.new, .create, .save
