# Projekt Excel - HR-kadry
## Analiza HR / kadry i rotacja pracowników

Interaktywny dashboard kadrowy w Excelu na podstawie danych 110 pracowników z lat 2023–2025
(kartoteka osobowa, wynagrodzenia miesięczne, absencje). Dane pochodziły z osobnych źródeł —
osobny eksport wynagrodzeń na każdy rok oraz niespójne nazewnictwo działów (różna wielkość liter
w tej samej nazwie) — co wymagało konsolidacji i dopasowania przed analizą.

**Zakres prac:**
- oczyszczenie i dopasowanie danych w Power Query, w tym dopasowanie rozmyte (fuzzy matching)
  niespójnych nazw działów do jednej tabeli wymiarów oraz konsolidacja wynagrodzeń z 3 lat,
- zbudowanie modelu danych w Power Pivot (relacje między pracownikami, działami, wynagrodzeniami,
  absencjami i kalendarzem) oraz miary DAX liczące m.in. bieżący stan zatrudnienia na dowolny
  dzień, wskaźnik rotacji, średni staż pracy, koszty wynagrodzeń i absencje,
- utworzenie tabel i wykresów przestawnych na bazie modelu danych,
- złożenie całości w interaktywny dashboard z fragmentatorami i osią czasu, umożliwiający
  filtrowanie danych wg działu, stanowiska i roku.

**Narzędzia:** Power Query, Power Pivot, DAX, tabele przestawne, wykresy przestawne, fragmentatory, oś czasu.

## Preview
<img src="https://github.com/MkDevX/sendit-project/assets/48242687/2faa4067-62c3-4b48-9f9e-cf61a61c276f" width="200" height="auto">
<img src="https://github.com/MkDevX/sendit-project/assets/48242687/72b84be4-4eb0-4296-b0ce-d744ec61d34a" width="200" height="auto">
<img src="https://github.com/MkDevX/sendit-project/assets/48242687/1b8a83c7-3858-444b-972d-79d21f73739f" width="200" height="auto">
<img src="https://github.com/MkDevX/sendit-project/assets/48242687/d4d495a9-cf35-4506-9f97-efb484d75aec" width="200" height="auto">
<img src="https://github.com/MkDevX/sendit-project/assets/48242687/404104d0-6037-4cf3-9d79-fc87a75f458e" width="200" height="auto">
<img src="https://github.com/MkDevX/sendit-project/assets/48242687/73aee278-d405-4489-913d-36117747e60f" width="200" height="auto">
<img src="https://github.com/MkDevX/sendit-project/assets/48242687/06602a7c-6c4d-4f6e-aa4f-7441b9262868" width="200" height="auto">

## Authors
- [@MkDevX](https://github.com/MkDevX/)
