# Opis aplikacji

Aplikacja zawiera dane o pracownikach, stanowiskach oraz wypłatach wynagrodzenia dla poszczegolnych pracownikow. Aby przeglądać dane, należy się zarejestrować w aplikacji, ponieważ dostęp do danych jest niemożliwy dla niezarejestrowanych użytkownikow.

Zakładka Moje Wypłaty prezentuje podsumowanie wszystkich wypłat tylko dla zalogowanego użytkownika. Nazwa użytkownika (email) musi zgadzać się z emailem pracownika zapisanego w bazie danych. 

Aby przygotować bazę danych do uruchomienia apikacji należy uruchomić w katalogu projektu polecenie:

	dotnet ef database update

Istnieje możliwość utworzenia bazy danych i przeprowadzenia migracji "w locie" podczas deweloperskiego uruchomienia aplikacji w oprogramowaniu Visual Studio.