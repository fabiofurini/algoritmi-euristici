---
title: Algoritmi euristici
hide:
  - navigation
  - toc
---

<div class="hero" markdown>

# Algoritmi euristici

<!-- collana-riga -->
<p class="collana-riga" markdown>Un corso della collana <b>Ricerca Operativa e Matematica</b> · [tutti i corsi](#la-collana)</p>
<!-- /collana-riga -->

Materiale didattico ideato e sviluppato da **[Fabio Furini](https://fabiofurini.github.io/)**, professore
associato al [DIAG](https://www.diag.uniroma1.it/), Sapienza Università di Roma.

**Le dispense del corso, online**: algoritmi euristici per i problemi di ottimizzazione combinatoria, cioè bound primali e duali e valutazione delle euristiche, euristiche costruttive, ricerca locale, metaeuristiche ed euristiche MIP, applicate ai problemi di zaino, di packing, di routing, di scheduling e di colorazione; con definizioni, esempi svolti passo per passo, esercizi con le soluzioni, notebook Colab e app interattive.

Prerequisiti: [Ottimizzazione combinatoria](https://fabiofurini.github.io/ottimizzazione-combinatoria/) per i problemi, le loro istanze e le loro formulazioni.

[Comincia :material-arrow-right:](heuristics.md){ .md-button .md-button--primary }
[:material-pencil: Esercizi](esercizi/index.md){ .md-button }
[:material-gesture-tap: Laboratorio](laboratorio/index.md){ .md-button }
[:material-clipboard-check-outline: Quiz](autovalutazione.md){ .md-button }
[:material-download: Materiale](materiale.md){ .md-button }

</div>

<!-- collana-app -->
## Provalo subito

Il TSP con nearest neighbour e 2-opt: il giro si costruisce città per città, poi il 2-opt lo migliora; trascina le città nel piano.

<div class="gi" data-grafico="oc-tsp"></div>

[:material-gesture-tap: Altre app nel laboratorio](laboratorio/index.md){ .md-button }
<!-- /collana-app -->

## Le parti del corso

I capitoli del corso, gli stessi della dispensa e del menu.

<div class="grid cards" markdown>

-   :material-scale-balance: **1. Algoritmi euristici: definizioni**

    ---

    *Capitolo 1*

    I problemi e le ipotesi · Bound primali e duali · Classificazione degli algoritmi euristici · Rappresentazione delle soluzioni e spazio di ricerca

    [:octicons-arrow-right-24: Leggi il capitolo](heuristics.md) · [Esercizi](esercizi/heuristics.md)

-   :material-hammer-wrench: **2. Euristiche costruttive**

    ---

    *Capitolo 2*

    I problemi e le ipotesi · Il paradigma greedy · Il problema dello zaino 0/1: quale ordinamento? · Il problema del bin packing: prima ordinare, poi riempire

    [:octicons-arrow-right-24: Leggi il capitolo](constructive-heuristics/index.md) · [Esercizi](esercizi/constructive-heuristics.md)

-   :material-magnify: **3. Ricerca locale**

    ---

    *Capitolo 3*

    I problemi, le ipotesi e le soluzioni di partenza · Ricerca locale: lo schema · Intorni per i quattro problemi · First improvement e best improvement

    [:octicons-arrow-right-24: Leggi il capitolo](local-search/index.md) · [Esercizi](esercizi/local-search.md)

-   :material-fire: **4. Metaeuristiche**

    ---

    *Capitolo 4*

    I problemi e le ipotesi · Come uscire da un ottimo locale · Simulated annealing · Tabu search

    [:octicons-arrow-right-24: Leggi il capitolo](metaheuristics/index.md) · [Esercizi](esercizi/metaheuristics.md)

-   :material-function-variant: **5. Euristiche MIP per i problemi classici**

    ---

    *Capitolo 5*

    Euristiche basate sulla PLI · I problemi e i loro modelli MIP · Arrotondamento · Diving

    [:octicons-arrow-right-24: Leggi il capitolo](mip-heuristics-classical.md) · [Esercizi](esercizi/mip-heuristics-classical.md)

</div>

<!-- collana-da-non-perdere -->
## Da non perdere

<div class="grid cards" markdown>

-   :material-pencil-box-multiple: **Esercizi con le soluzioni**

    ---

    Esercizi per ogni capitolo, ciascuno con la soluzione svolta che si apre con un clic.

    [:octicons-arrow-right-24: Gli esercizi](esercizi/index.md)

-   :material-clipboard-check-outline: **Quiz di autovalutazione**

    ---

    Un facsimile d'esame nuovo a ogni avvio: 13 domande, 33 punti, con la soluzione e il link alle dispense. In Materiale c'è anche la banca completa delle domande.

    [:octicons-arrow-right-24: Mettiti alla prova](autovalutazione.md)

-   :material-gesture-tap: **Laboratorio interattivo**

    ---

    App che girano nel browser: muovi i parametri e guarda le idee del corso lavorare, un passo alla volta.

    [:octicons-arrow-right-24: Il laboratorio](laboratorio/index.md)

-   :material-download: **Dispense in PDF**

    ---

    Dispense, eserciziari e slide in PDF, con la stessa numerazione del sito.

    [:octicons-arrow-right-24: Il materiale](materiale.md)

-   :material-language-python: **Notebook in Colab**

    ---

    Il codice del corso che gira nel browser, senza installare niente.

    [:octicons-arrow-right-24: I notebook](notebook.md)

-   :material-format-list-numbered: **Indice completo**

    ---

    Tutti i capitoli con le loro sezioni in una pagina, e come è fatto ogni capitolo.

    [:octicons-arrow-right-24: L'indice](indice.md)

</div>
<!-- /collana-da-non-perdere -->

---

<!-- collana -->
## La collana

Dieci corsi con la stessa impostazione: dispense online e in PDF, esercizi con le soluzioni, laboratorio interattivo e quiz di autovalutazione.

<div class="grid cards" markdown>

-   :material-function-variant: **[Analisi Matematica 1](https://fabiofurini.github.io/analisi-matematica-1/)**

    numeri reali, funzioni, limiti, derivate e serie, con i grafici interattivi

-   :material-matrix: **[Algebra lineare](https://fabiofurini.github.io/algebra-lineare/)**

    vettori, matrici, determinanti, sistemi lineari e autovalori, con il laboratorio di calcolo

-   :material-code-braces: **[Algoritmi](https://fabiofurini.github.io/algoritmi/)**

    rappresentazione dei numeri, pseudocodice, ordinamento e ricerca, analisi e algoritmi ricorsivi

-   :material-vector-triangle: **[Programmazione lineare](https://fabiofurini.github.io/programmazione-lineare/)**

    poliedri, algoritmo del simplesso, dualità e simplesso duale, con il laboratorio interattivo

-   :material-dots-grid: **[Programmazione lineare intera](https://fabiofurini.github.io/programmazione-lineare-intera/)**

    rilassamento continuo, disuguaglianze valide, piani di taglio, branch-and-bound e branch-and-cut

-   :material-vector-curve: **[Ottimizzazione convessa](https://fabiofurini.github.io/ottimizzazione-convessa/)**

    insiemi e funzioni convesse, problemi di ottimizzazione convessa, con grafici interattivi

-   :material-graph-outline: **[Ottimizzazione su reti](https://fabiofurini.github.io/ottimizzazione-su-reti/)**

    grafi, alberi ricoprenti, cammini minimi, flussi su reti, simplesso su reti e gestione dei progetti

-   :material-hexagon-multiple-outline: **[Ottimizzazione combinatoria](https://fabiofurini.github.io/ottimizzazione-combinatoria/)**

    zaino, bin packing, colorazione, TSP, scheduling e lot sizing, risolti in tutti i modi

-   :material-table-large: **[Programmazione dinamica](https://fabiofurini.github.io/programmazione-dinamica/)**

    principi e algoritmi di PD per zaino, lot sizing, cambio monete e taglio delle aste

-   :material-map-marker-path: **Algoritmi euristici** · *questo corso*

    euristiche costruttive, ricerca locale, metaeuristiche ed euristiche MIP per i problemi di ottimizzazione combinatoria

-   :material-approximately-equal: **[Algoritmi di approssimazione](https://fabiofurini.github.io/algoritmi-di-approssimazione/)**

    garanzie di prestazione, schemi di approssimazione e limiti dell'approssimazione per i problemi combinatori

-   :material-vector-polygon: **[Modellazione MIP](https://fabiofurini.github.io/modellazione-mip/)**

    modelli di programmazione lineare a variabili intere, dalla formulazione alla soluzione con i solver

-   :material-chart-timeline-variant: **[Laboratorio di Ricerca Operativa](https://fabiofurini.github.io/laboratorio-ricerca-operativa/)**

    modellazione e risoluzione di problemi di ottimizzazione con Python e i solver

</div>
<!-- /collana -->

---

Materiale didattico di **[Fabio Furini](https://fabiofurini.github.io/)** —
[DIAG](https://www.diag.uniroma1.it/), Sapienza Università di Roma.

*Questo sito è disponibile anche in [inglese](https://fabiofurini.github.io/heuristic-algorithms/).*
