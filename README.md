# Algoritmi-Fundamentali

Acest cod prezintă o implementare extinsă a unor algoritmi fundamentali de grafuri, cu scopul de a demonstra înțelegerea aprofundată a structurilor de date, algoritmilor și a paradigmelor de programare modernă în C++. Proiectul face parte din materia **Algoritmi Fundamentali** și subliniază cunoștințele și abilitățile mele în programare și rezolvarea problemelor complexe.

## Funcționalități

Proiectul include o implementare completă a claselor și funcțiilor pentru a lucra cu grafuri complexe, acoperind o gamă largă de algoritmi și probleme clasice:

- **Citirea și afișarea grafurilor**: Din fișiere, sub formă de listă de adiacență, matrice de adiacență sau listă de muchii.
- **Parcurgerea grafurilor**: Implementări pentru BFS și DFS atât iterative cât și recursive.
- **Algoritmi de drum minim**:
  - Dijkstra (graf ponderat)
  - Bellman-Ford (grafuri cu ponderi pozitive, negative sau nule)
  - Floyd-Warshall (distanțe minime pentru toate perechile de noduri)
- **Algoritmi pentru determinarea arborilor de cost minim**:
  - Kruskal
  - Prim
- **Algoritmi pentru componente conexe și tare conexe**:
  - Flood Fill
  - Tarjan
  - Kosaraju
- **Sortare topologică** (pentru grafuri aciclice orientate)
- **Algoritmi pentru grafuri bipartite și cuplaje maxime**:
  - Verificare graf bipartit
  - Algoritmul Hopcroft-Karp
- **Flux maxim și flux de cost minim**:
  - Algoritmul Edmonds-Karp
  - Flux maxim cu cost minim
- **Determinarea drumului critic într-un graf orientat și ponderat** (Critical Path Method - CPM)
- **Determinarea punctelor și muchiilor critice** într-un graf neorientat
- **Probleme speciale**:
  - Havel-Hakimi și construcția unui graf neorientat dintr-o secvență de grade
  - Verificarea și construcția grafurilor hamiltoniene și euleriene
  - Algoritmul de colorare a unui graf folosind 6 culori
- **Alți algoritmi**:
  - Algoritm de clustering bazat pe Kruskal
  - Funcții de editare și distanță între șiruri de caractere (Levenshtein)

## Tehnologii și concepte folosite

- **Programare orientată pe obiecte (OOP)**: Clasa `Graf` este nucleul acestei implementări și folosește pe scară largă principiile OOP.
- **Funcții recursive și iterative**: Demonstrează versatilitatea în implementarea algoritmilor de parcurgere.
- **Algoritmi Greedy și de Programare Dinamică**: Dijkstra, Bellman-Ford, Prim, Floyd-Warshall.
- **Algoritmi bazati pe structuri de date avansate**: Heapuri, cozi de priorități, stive și alte structuri STL.
- **Design modular și clar**: Funcțiile sunt organizate pe categorii, iar codul este ușor de extins și de reutilizat.

## Scop

Codul a fost realizat ca parte a unei evaluări academice, însă este și o demonstrație a abilităților mele în proiectarea și implementarea algoritmilor pentru grafuri complexe. Acesta poate servi ca bază pentru proiecte mai avansate sau poate fi folosit ca un instrument educațional pentru învățarea algoritmilor de bază și avansați.
