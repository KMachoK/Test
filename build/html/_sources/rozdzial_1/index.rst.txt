================================
Wstęp do sprawozdania oraz linki
================================

:Autorzy:
    1. Olaf Chomicki
    2. Konrad Machowski
    3. Wiktor Wydrzyński

Wstęp
=====

Niniejsze sprawozdanie stanowi kompleksową dokumentację prac laboratoryjnych zrealizowanych w ramach przedmiotu Bazy Danych. Głównym założeniem projektu było przełożenie wiedzy akademickiej na praktyczne umiejętności inżynierskie, niezbędne przy projektowaniu, implementacji oraz utrzymaniu nowoczesnych systemów relacyjnych baz danych.

Opracowanie przeprowadza czytelnika przez pełen cykl życia systemu bazodanowego. Proces rozpoczął się od dogłębnej analizy wymagań teoretycznych, co posłużyło jako fundament do zaprojektowania modelu pojęciowego i logicznego. Następnie architektura ta została powołana do życia poprzez fizyczną implementację w środowiskach PostgreSQL oraz SQLite. Istotnym elementem projektu była również automatyzacja i realizacja procesów wsadowego zasilania struktury rzeczywistymi danymi.

Wykaz repozytoriów (Linki)
==========================

Zgodnie z dobrymi praktykami inżynierii oprogramowania, projekt został logicznie rozdzielony na odrębne repozytoria w rozproszonym systemie kontroli wersji Git. Takie podejście gwarantuje utrzymanie porządku, separację dokumentacji tekstowej od kodu wykonywalnego oraz ułatwia śledzenie historii zmian w poszczególnych komponentach.

Główne repozytorium sprawozdania (Dokumentacja Sphinx)
------------------------------------------------------
Niniejsze repozytorium pełni rolę centralnego węzła dokumentacyjnego. Znajduje się w nim pełna struktura tekstowa zapisana w formacie reStructuredText, niezbędna konfiguracja generatora dokumentacji Sphinx (plik ``conf.py``) oraz pliki konfiguracyjne środowiska budowania (np. pliki Makefile).

* **Link:** https://github.com/KMachoK/Test.git

Repozytorium z plikami projektowymi
-----------------------------------
To repozytorium przechowuje właściwe pliki inżynierskie i deweloperskie. Zgromadzono w nim skrypty DDL definiujące struktury dla silników PostgreSQL i SQLite, wygenerowany plik lokalnej bazy danych oraz zbiory danych w formacie CSV, które wykorzystano do automatycznego zasilenia poszczególnych tabel.

* **Link:** https://github.com/KMachoK/Test.git

Repozytoria reszty grupy (Submoduły)
------------------------------------
Poniższa sekcja zawiera wykaz repozytoriów, w których zespoły opracowywały dedykowane tematy specjalistyczne. Aby zapewnić spójność ostatecznego dokumentu, repozytoria te zostały zintegrowane z głównym projektem jako submoduły (submodules) i stanowią treść Rozdziału 2.

* **Grupa 1 (rozdzial_1):** https://github.com/karaskamil/Sprzet-dla-bazy-danych.git
* **Grupa 2 (rozdzial_2):** https://github.com/Youarecheck/Bazy_Danych_Tematyczne_Repo_MK.git
* **Grupa 3 (rozdzial_3):** https://github.com/pawlos1337/Bazy-danych-temat.git
* **Grupa 4 (rozdzial_4):** https://github.com/OskarProgrammer/monitorowanie_i_diagnostyka.git
* **Grupa 5 (rozdzial_5):** https://github.com/KMachoK/Tematyczne.git
* **Grupa 6 (rozdzial_6):** https://github.com/domino0472/Partycjonowani-Danych
* **Grupa 7 (rozdzial_7):** https://github.com/oski486/BazyDanych-Subject.git
* **Grupa 8 (rozdzial_8):** https://github.com/Koko9077/Kopie-zapasowe-i-odzyskiwanie-danych.git
