# Projekt Excel - Sprzedaż detaliczna
Interaktywny dashboard sprzedażowy w Excelu na podstawie danych transakcyjnych z lat 2023–2025
(ok. 1600 transakcji, dane produktowe, sprzedawcy, klienci). Dane pochodziły z osobnych rocznych
eksportów i zawierały typowe błędy — niespójne formaty dat, duplikaty, braki w rabatach — które
zostały oczyszczone i skonsolidowane przed analizą.

**Zakres prac:**
- połączenie i oczyszczenie danych z 3 lat w Power Query (ujednolicenie formatów dat, usunięcie duplikatów, uzupełnienie braków),
- zbudowanie modelu danych w Power Pivot (relacje między tabelą transakcji a tabelami produktów, sprzedawców, klientów i kalendarzem) oraz miary DAX (przychód, marża, wzrost rok do roku, wskaźnik zwrotów i inne),
- utworzenie tabel i wykresów przestawnych na bazie modelu danych,
- złożenie całości w interaktywny dashboard z fragmentatorami i osią czasu, umożliwiający filtrowanie danych wg roku, regionu, kategorii i segmentu klienta.

**Narzędzia:** 
- Power Query, 
- Power Pivot, 
- DAX, 
- tabele przestawne, 
- wykresy przestawne, 
- fragmentatory, 
- oś czasu.

**Podgląd:** 
<br><br><img src="https://github.com/MkDevX/Excel/blob/main/Sprzeda%C5%BC%20detaliczna/Dashborad%20-%20filtrowanie%20-%20Sprzeda%C5%BC%20detaliczna.gif">
