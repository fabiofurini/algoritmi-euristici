# Indice completo

<!-- collana-organizzazione -->
## Come usare queste dispense

- **Sito e PDF.** Ogni capitolo del sito è un capitolo della dispensa, con gli stessi numeri e gli stessi colori; i capitoli lunghi sono divisi in una pagina per sezione.
- **In testa a ogni capitolo** la barra con la parte, il PDF della dispensa, le slide, gli esercizi e le app del capitolo; in fondo, il link agli esercizi.
- **I problemi.** Definizioni, istanze e formulazioni dei problemi stanno nel corso [Problemi di ottimizzazione combinatoria](https://fabiofurini.github.io/ottimizzazione-combinatoria/): i capitoli vi rimandano con un link.
- **Il codice.** Nelle pagine gli algoritmi sono in pseudocodice; i pulsanti «Esegui in Colab» aprono il notebook con il codice in Python e C++.

I box hanno gli stessi colori della dispensa:

<div class="grid" markdown>

!!! definizione "Definizione"
    Il significato preciso di un concetto nuovo.

!!! teorema "Teorema, proposizione, osservazione"
    Un risultato da ricordare, con le sue ipotesi.

!!! esempio "Esempio"
    Un calcolo svolto per intero, un passo alla volta.

!!! formula "Formula"
    In rosa le formule da avere sempre sotto mano.

!!! algoritmo "Algoritmo"
    Lo pseudocodice, passo per passo come nella dispensa.

!!! chiave ""
    **In verde** il punto chiave da portare a casa.

</div>

??? dimostrazione "Dimostrazione: si apre con un clic"
    Le dimostrazioni ci sono tutte, ma chiuse: prima leggi l'enunciato, poi apri la dimostrazione quando vuoi studiarla. Lo stesso vale per le soluzioni degli esercizi.
<!-- /collana-organizzazione -->

Tutte le pagine del sito, nell'ordine del menu: i capitoli con le loro sezioni e le altre pagine.

## [Principi](principi.md)

- **[1. Algoritmi euristici: definizioni](heuristics.md)** · [Esercizi](esercizi/heuristics.md)
    - [1.1 Algoritmi euristici](heuristics.md#11-algoritmi-euristici)
    - [1.2 I problemi e le ipotesi](heuristics.md#sez-sec-problems)
    - [1.3 Bound primali e duali](heuristics.md#13-bound-primali-e-duali)
    - [1.4 Classificazione degli algoritmi euristici](heuristics.md#14-classificazione-degli-algoritmi-euristici)
    - [1.5 Rappresentazione delle soluzioni e spazio di ricerca](heuristics.md#15-rappresentazione-delle-soluzioni-e-spazio-di-ricerca)
    - [1.6 Intorni e ottimi locali](heuristics.md#16-intorni-e-ottimi-locali)
    - [1.7 Intensificazione e diversificazione](heuristics.md#17-intensificazione-e-diversificazione)
    - [1.8 Come valutare un algoritmo euristico](heuristics.md#sez-sec-evaluation)
    - [1.9 Errori tipici](heuristics.md#19-errori-tipici)
    - [1.10 In sintesi](heuristics.md#110-in-sintesi)

## [Euristiche combinatorie](euristiche-combinatorie.md)

- **[2. Euristiche costruttive](constructive-heuristics/index.md)** · [Esercizi](esercizi/constructive-heuristics.md)
    - [2.1 Euristiche costruttive](constructive-heuristics/index.md#sez-sec-constructive)
    - [2.2 I problemi e le ipotesi](constructive-heuristics/i-problemi-e-le-ipotesi.md#sez-sec-problems)
    - [2.3 Il paradigma greedy](constructive-heuristics/i-problemi-e-le-ipotesi.md#sez-sec-greedy)
    - [2.4 Il problema dello zaino 0/1: quale ordinamento?](constructive-heuristics/il-problema-dello-zaino-0-1-quale-ordinamento.md)
    - [2.5 Il problema del bin packing: prima ordinare, poi riempire](constructive-heuristics/il-problema-del-bin-packing-prima-ordinare-poi-riempire.md)
    - [2.6 Scheduling su macchine parallele: prima i lavori più lunghi](constructive-heuristics/scheduling-su-macchine-parallele-prima-i-lavori-piu-lunghi.md)
    - [2.7 Il problema del commesso viaggiatore: accodare o inserire?](constructive-heuristics/il-problema-del-commesso-viaggiatore-accodare-o-inserire.md)
    - [2.8 Colorazione dei vertici: greedy e DSATUR](constructive-heuristics/colorazione-dei-vertici-greedy-e-dsatur.md)
    - [2.9 Costruzione randomizzata](constructive-heuristics/costruzione-randomizzata.md)
    - [2.10 Look-ahead e regret](constructive-heuristics/look-ahead-e-regret.md)
    - [2.11 Che cosa danno le euristiche costruttive, e che cosa non danno](constructive-heuristics/che-cosa-danno-le-euristiche-costruttive-e-che-cosa-non-dann.md)
    - [2.12 Errori tipici](constructive-heuristics/errori-tipici.md#212-errori-tipici)
    - [2.13 In sintesi](constructive-heuristics/errori-tipici.md#213-in-sintesi)
- **[3. Ricerca locale](local-search/index.md)** · [Esercizi](esercizi/local-search.md)
    - [3.1 Ricerca locale](local-search/index.md#sez-sec-ls)
    - [3.2 I problemi, le ipotesi e le soluzioni di partenza](local-search/i-problemi-le-ipotesi-e-le-soluzioni-di-partenza.md)
    - [3.3 Ricerca locale: lo schema](local-search/ricerca-locale-lo-schema.md#sez-sec-scheme)
    - [3.4 Intorni per i quattro problemi](local-search/ricerca-locale-lo-schema.md#sez-sec-neigh)
    - [3.5 First improvement e best improvement](local-search/first-improvement-e-best-improvement.md)
    - [3.6 Valutare una mossa in modo incrementale](local-search/valutare-una-mossa-in-modo-incrementale.md)
    - [3.7 TSP: 2-opt e Or-opt](local-search/tsp-2-opt-e-or-opt.md)
    - [3.8 $P\,||\,C_{\max}$: move e swap](local-search/p-cmax-move-e-swap.md)
    - [3.9 Paesaggi piatti e obiettivi ausiliari](local-search/paesaggi-piatti-e-obiettivi-ausiliari.md)
    - [3.10 KP: ammissibilità e penalità](local-search/kp-ammissibilita-e-penalita.md)
    - [3.11 Variable neighbourhood descent](local-search/variable-neighbourhood-descent.md)
    - [3.12 Ricerca locale multi-start](local-search/ricerca-locale-multi-start.md)
    - [3.13 Errori tipici](local-search/errori-tipici.md#313-errori-tipici)
    - [3.14 In sintesi](local-search/errori-tipici.md#314-in-sintesi)
- **[4. Metaeuristiche](metaheuristics/index.md)** · [Esercizi](esercizi/metaheuristics.md)
    - [4.1 Metaeuristiche](metaheuristics/index.md#sez-sec-metaheuristic)
    - [4.2 I problemi e le ipotesi](metaheuristics/i-problemi-e-le-ipotesi.md)
    - [4.3 Come uscire da un ottimo locale](metaheuristics/come-uscire-da-un-ottimo-locale.md#sez-sec-escape)
    - [4.4 Simulated annealing](metaheuristics/come-uscire-da-un-ottimo-locale.md#sez-sec-sa)
    - [4.5 Tabu search](metaheuristics/tabu-search.md)
    - [4.6 Iterated local search](metaheuristics/iterated-local-search.md)
    - [4.7 Variable neighbourhood search](metaheuristics/variable-neighbourhood-search.md)
    - [4.8 GRASP](metaheuristics/grasp.md)
    - [4.9 Large neighbourhood search](metaheuristics/large-neighbourhood-search.md)
    - [4.10 Metodi basati su popolazioni: algoritmi genetici e memetici](metaheuristics/metodi-basati-su-popolazioni-algoritmi-genetici-e-memetici.md)
    - [4.11 Confronto e conclusioni](metaheuristics/confronto-e-conclusioni.md)
    - [4.12 Errori tipici](metaheuristics/errori-tipici.md#412-errori-tipici)
    - [4.13 In sintesi](metaheuristics/errori-tipici.md#413-in-sintesi)

## [Euristiche MIP](euristiche-mip.md)

- **[5. Euristiche MIP per i problemi classici](mip-heuristics-classical.md)** · [Esercizi](esercizi/mip-heuristics-classical.md)
    - [5.1 Euristiche basate sulla PLI](mip-heuristics-classical.md#sez-sec-intro)
    - [5.2 I problemi e i loro modelli MIP](mip-heuristics-classical.md#sez-sec-models)
    - [5.3 Arrotondamento](mip-heuristics-classical.md#sez-sec-rounding)
    - [5.4 Diving](mip-heuristics-classical.md#sez-sec-diving)
    - [5.5 La feasibility pump](mip-heuristics-classical.md#sez-sec-fp)
    - [5.6 RINS, local branching e proximity search](mip-heuristics-classical.md#sez-sec-submip)
    - [5.7 Relax-and-fix e fix-and-optimize sul lot sizing](mip-heuristics-classical.md#sez-sec-rf)
    - [5.8 Le euristiche dentro il solver](mip-heuristics-classical.md#sez-sec-gurobi)
    - [5.9 Che cosa danno le euristiche basate sulla PLI](mip-heuristics-classical.md#sez-sec-give)
    - [5.10 Errori tipici](mip-heuristics-classical.md#sez-sec-mistakes)
    - [5.11 In sintesi](mip-heuristics-classical.md#sez-sec-summary)

## Altre pagine

- [Esercizi](esercizi/index.md)
- [Laboratorio](laboratorio/index.md)
- [Materiale](materiale.md)
- [Notebook Colab](notebook.md)
- [Autovalutazione](autovalutazione.md)
