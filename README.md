# EmployeesOffice

### Opis

Aplikacja webowa stworzona do sprawdzania ile osób pozostało w biurze. 
Backend jest tylko przykładowy i ma symulować połączenie z czytnikiem identyfikatorów pracowników.
Np: Jeżeli pracownik się "odbija" w czytniku to backend dostaje informacje i dodaje te osobe do listy u mnie jest to zastąpione metodą POST aby pokazać przykładowe działanie.
Socket wysyła powiadomienie które otrzymuje od czytnika czy Front ma odświeżyć widok ponieważ, zaszła zmiana w REST API.  W moim backendzie jest co 10s wysyłania wartość true lub false aby zasymulować i pokazać, że odświeżanie działa.
***
### Funkcje
***
**HomePage: ** Wyświetla dwa komponenty zależne od REST API i wartości czy lista ma być widoczna. Jeżeli tak jest widoczna lista a jeżeli nie jest widoczna tylko liczba Pracowników.
**EmployeesList** :  Wyświetla liste praconików w tabeli stworzonej przy użyciu technologii Bootstrap.
**EmployessNumber**: Wyświetla liczbe praconików.
**Settings**: Oferuję możliwość włączenia zegarka który pobiera czas z serwera a wybraną opcje zapisuje w cookies przeglądarki. 
**Responsive Mobile and Desktop NavBar**: Responsywny navbar

###Użyte technologie 
****
**Frontend** : Vue.js, MDB Bootstrap 
**Backend** : Node.js, Socket.io, Express





