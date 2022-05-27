# Visimind_doc
# Dokumentacja
Dokumentacja z zajęć z przedmiotu fakultatywnego
## Projekt OWASP ZAP + CRUD w symfony
Na tworzenie aplikacji każdy będzie przeznaczał około 1 godziny dziennie, a we wtorek dodatkową godzinę, poniważ zaplanowane mamy wtedy zajęcia przeznaczone do realizacji danego projektu. Projekt powinien zostać zrealizowany do 25.05.2022 roku lecz nie musi być skończony.
## Cel
Stworzyć aplikacje sprawdzającą luki w zabezpieczeniach przez OWASP ZAP i zapisującą wszystkie wyniki dla danej strony. Przeprowadzi atak na daną stronę i wygeneruje raport z lukami.
## Podział zespołów
Jeszcze nie ma.
## Analiza ryzyka
### Prawdopodobieństwo
- brak znajomości lub mała znajomość frameworka symfony
### Wpływ na projekt
- opóźnienie rozpoczęcia pracy nad projektem
### Sposób ograniczenia ryzyka
- rozpoczęcie nauki frameworka symfony/ praca z dokumentacją
### Reakcja
- w przypadku gdy jeden z programistów będzie miał jakieś trudności z danym zadaniem, pozostałe osoby pomogą w rozwiązaniu danego problemu
# Epic
Aplikacja sprawdzająca luki w zabezpieczeniach przez OWASP ZAP i przedsatwiająca wszystkie wyniki.
## Feature
1. 
2. 
3. 
4. 
5. 
6. 
7. 
8. 
9. 

## User story/task
-tak
# Analiza zespołu
## Analiza SWOT
### Silne strony
- znajomość różnych języków programowania
- możliwość douczenia się w przypadku problemów
- zespół uzupełniający się
### Słabe strony
- brak zaawansowanej znajomości niektórych frameworków
- brak zaawansowanej znajomości niektórych jezyków programowania
### Okazje
- możliwość rozwinięcia wiedzy własnej odnośnie nowych jezyków programowania
- możliwość rozwinięcia wiedzy własnej odnośnie nowych frameworków
- możliwość zdobycia umiejętności pracy w zespole
### Zagrożenia
- możliwość posiadania problemów związanych z brakiem znajomości frameworka symfony
- nie wystarczająca ilość czasu na wykonanie danego projektu
## Wstępny wykres gantta
![image](https://user-images.githubusercontent.com/58747620/160109148-84d74b8b-0425-4b03-a45d-10228363f9ec.png)
# Schematy blokowe
## Rejestracja/Logowanie
![image](https://user-images.githubusercontent.com/58747620/160111355-1641904a-958c-4329-aba4-7a98e1924085.png)
## Zmiana hasła
![image](https://user-images.githubusercontent.com/58747620/165851351-508d5cc2-9f82-4b68-a66b-d597c6359cef.png)
## Konflikty
### Przypadek 1
> Piotr zachowuje się agresywnie w stosunku do innych uczestników.
-   Przeciwdziałania
    -   postarać sie dowiedzieć jaka jest przyczyna takiego zachowania
    -   ustalenie z innymi członkami projektu co można zrobić w danej sytuacji
    -   w ostateczności zwolnić pracownika
### Przypadek 2
> Przełożony wymaga przygotowania demo, które nie było zaplanowane w sprincie co powoduje opóźnienie w projekcie.
-   Przeciwdziałania
    -   zrobić miejsce na demo kosztem jednego z punktów sprintu
    -   poproszenie o przesunięcie terminu projektu
    -   doprecyzowanie w jakim celu jest potrzebne wykonanie tego demo
    -   zasugerować możliwość nadgodzin
### Przypadek 3
> Maciek jest wspaniałym analitykiem i jego wiedza pomogłaby w realizacji projektu. Niestety zespół z równolegle prowadzonego projektu rówhież potrzebuje jego wsparcia.
-   Przeciwdziałania
    -   zapytać Maćka czy jest w stanie nadzorować dwa projekty jednocześnie
    -   przydzielić Maćkowi w jednym dniu jeden projekt w drugim dniu drugi
    -   zatrudnić na pewien okres drugiego tak dobrego analityka
    -   przydzielenie Maćka do ważniejszego projektu

## DoD (Definition of Done)
> Dla portalu internetowego
-   Test ortografii
-   Test responsywności
-   Test czytelności
-   Czy na różnych systemach wyświetla się prawidłowo
-   Przeprowadzono testy na urządzeniach/przeglądarkach wymienionych w dokumentacji
-   Przeszły testy kompatybilności wstecznej
-   Testy wydajności przeszły pomyślnie
-   Naprawiono wszystkie błędy  
## Kryteria akceptacji
>     indywidualne kryteria która musi spełnić każda poszczególna historyjka
Dla testowania zabezpieczeń stron :: Jako użytkownik chce sprawdzić czy dana strona jest dobrze zabezpieczona
-   możliwość logowania i sprawdzania raportów poprzednich skanów bezpieczeństwa strony
-   opcja 'Prównaj raporty' do sprawdzę czy poprzednie błędy w zabezpieczeniach zostały naprawione
-   sprawdzenie możliwość poprawy zabezpieczeń danej strony
-   poinformowanie użytkownika o nie istniejącej stronie do skanowania zabezpieczeń lub jej błędne wpisanie
-   możliwość pobrania raportu
-   możliwość wyświetlenia raportu
