---
title: Notebook
---

# I notebook del corso

Il codice dei capitoli sugli algoritmi sta nei **notebook Colab**, uno per capitolo e per linguaggio: **Python** e **C++** (le euristiche MIP solo in Python, con `gurobipy`). Nelle pagine del sito gli algoritmi sono scritti in pseudocodice; nei notebook gli stessi algoritmi sono implementati (con gli indici da 0) ed eseguiti su tutti gli esempi del capitolo e su tutte le istanze degli esercizi, con il controllo dei valori attesi, e una cella «Try it yourself» per provarli con dati tuoi.

**I notebook sono per ora in inglese**: commenti, testi e output sono quelli dei notebook del sito inglese; il codice e i risultati sono gli stessi delle pagine italiane.

- **Cos'è Colab.** [Google Colab](https://colab.research.google.com/) esegue i notebook nel browser, su un computer di Google: serve solo un account Google, sul tuo computer non si installa niente.
- **Come si apre.** Clicca su un badge della tabella, oppure sui pulsanti «Esegui in Colab» sotto lo pseudocodice nelle pagine dei capitoli. Per conservare le tue modifiche: *File → Salva una copia in Drive*.
- **Come si esegue.** *Runtime → Esegui tutte* (Ctrl+F9) esegue tutte le celle dall'alto in basso; una cella sola si esegue con Maiusc+Invio.
- **C++.** Ogni file viene scritto da una cella (`%%writefile`); la cella dopo `Main.cpp` compila tutto con `g++` ed esegue gli esempi: tutto avviene in Colab.
- **Un notebook per linguaggio.** I due notebook di un capitolo contengono gli stessi algoritmi e stampano gli stessi risultati.

Il link **.ipynb** apre il notebook su GitHub, da dove si scarica (*Download raw file*) per usarlo con Jupyter sul proprio computer.

<div class="tabella-notebook" markdown>

| Capitolo | Python | C++ |
|---|:---:|:---:|
| [2. Euristiche costruttive](constructive-heuristics/index.md) | [![Apri in Colab (Python)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/heuristic-algorithms/blob/main/notebooks/constructive-heuristics_python.ipynb) [.ipynb](https://github.com/fabiofurini/heuristic-algorithms/blob/main/notebooks/constructive-heuristics_python.ipynb) | [![Apri in Colab (C++)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/heuristic-algorithms/blob/main/notebooks/constructive-heuristics_cpp.ipynb) [.ipynb](https://github.com/fabiofurini/heuristic-algorithms/blob/main/notebooks/constructive-heuristics_cpp.ipynb) |
| [3. Ricerca locale](local-search/index.md) | [![Apri in Colab (Python)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/heuristic-algorithms/blob/main/notebooks/local-search_python.ipynb) [.ipynb](https://github.com/fabiofurini/heuristic-algorithms/blob/main/notebooks/local-search_python.ipynb) | [![Apri in Colab (C++)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/heuristic-algorithms/blob/main/notebooks/local-search_cpp.ipynb) [.ipynb](https://github.com/fabiofurini/heuristic-algorithms/blob/main/notebooks/local-search_cpp.ipynb) |
| [4. Metaeuristiche](metaheuristics/index.md) | [![Apri in Colab (Python)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/heuristic-algorithms/blob/main/notebooks/metaheuristics_python.ipynb) [.ipynb](https://github.com/fabiofurini/heuristic-algorithms/blob/main/notebooks/metaheuristics_python.ipynb) | [![Apri in Colab (C++)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/heuristic-algorithms/blob/main/notebooks/metaheuristics_cpp.ipynb) [.ipynb](https://github.com/fabiofurini/heuristic-algorithms/blob/main/notebooks/metaheuristics_cpp.ipynb) |
| [5. Euristiche MIP per i problemi classici](mip-heuristics-classical.md) | [![Apri in Colab (Python)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/heuristic-algorithms/blob/main/notebooks/mip-heuristics-classical_python.ipynb) [.ipynb](https://github.com/fabiofurini/heuristic-algorithms/blob/main/notebooks/mip-heuristics-classical_python.ipynb) |  |

</div>
