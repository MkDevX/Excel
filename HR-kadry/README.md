# Projekt Excel - HR-kadry
Interaktywny dashboard kadrowy w Excelu na podstawie danych 110 pracowników z lat 2023–2025
(kartoteka osobowa, wynagrodzenia miesięczne, absencje). Dane pochodziły z osobnych źródeł —
osobny eksport wynagrodzeń na każdy rok oraz niespójne nazewnictwo działów (różna wielkość liter
w tej samej nazwie) — co wymagało konsolidacji i dopasowania przed analizą.

**Zakres prac:**
- oczyszczenie i dopasowanie danych w Power Query, w tym dopasowanie rozmyte (fuzzy matching) niespójnych nazw działów do jednej tabeli wymiarów oraz konsolidacja wynagrodzeń z 3 lat,
- zbudowanie modelu danych w Power Pivot (relacje między pracownikami, działami, wynagrodzeniami, absencjami i kalendarzem) oraz miary DAX liczące m.in. bieżący stan zatrudnienia na dowolny dzień, wskaźnik rotacji, średni staż pracy, koszty wynagrodzeń i absencje,
- utworzenie tabel i wykresów przestawnych na bazie modelu danych,
- złożenie całości w interaktywny dashboard z fragmentatorami i osią czasu, umożliwiający
  filtrowanie danych wg działu, stanowiska i roku.

**Narzędzia:** 
- Power Query, 
- Power Pivot, 
- DAX, 
- tabele przestawne, 
- wykresy przestawne, 
- fragmentatory, 
- oś czasu.

**Podgląd:** 
<br><img src="https://github.com/MkDevX/Excel/blob/main/HR-kadry/Dashboard%20-%20filtrowanie%20-%20HR-kadry.gif">
