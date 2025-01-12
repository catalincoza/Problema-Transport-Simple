# Problema Transport - Analiză algoritmi

## Descriere
Acest repo conține soluții Python pentru problema transportului simplu și cu costuri (magazin, depozit, ambele). Codul implementează metode de rezolvare a problemelor de transport folosind tehnici de optimizare pentru a minimiza costurile de transport. Se utilizează date de intrare și se generează rezultate, inclusiv tabele de transport rezolvate. 
Rezultatele generate nu sunt optime, în afară de cazul problemei de transport simple, în cadrul căreia s-a folosit o combinație de algoritmi eficienți pentru acest caz.
Algoritmii folosiți sunt:
- Problema Transport Simplă - HiGHS Algorithm (generează rezultate optime)
- Problema Transport cu Cost Fix Magazin - Minim pe matrice
- Problema Transport cu Cost Fix Depozit - Vogel
- Problema Transport cu Cost Fix Magazin și Depozit - Vogel
Scopul acestor rezultate generate este de a compara eficacitatea algoritmilor față de rezultatele optime pentru fiecare tip de problemă: simplă, medie sau largă.

## Fișiere
- `simple.py, minim_matrice.py, vogel.py, vogel_FCD_FCR.py`: Scripturile principal care execută soluționarea problemei de transport.
- `Lab_simple_instances.zip, Lab_FCR_instances.zip, Lab_FCD_instances.zip, Lab_FCD_FCR_instances.zip`: Datele de intrare pentru diverse instanțe ale problemei de transport, cu și fără costuri.
- `Lab_simple_solved_results.xlsx, Lab_FCR_solved_results.xlsx, Lab_FCD_solved_results.xlsx, Lab_FCD_FCR_solved_results.xlsx`: Rezultatele rezolvate, aranjate în fișiere Excel, cu următoarea structură: numele instanței, optimul obținut, numărul de iterații pentru soluționarea problemei, timpul de rulare în secunde, dacă a fost soluționată problema.
