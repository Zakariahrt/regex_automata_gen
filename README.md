This project demonstrates how to generate and visualize finite automata from regular expressions using the FAdo Python library. It supports three classical automata constructions:

- **Thompson NFA** (based on concatenation, union, and star operators)
- **Glushkov NFA** (also called Position Automaton)
- **Antimirov NFA** (based on partial derivatives)

---

## Features

- Input regular expressions as strings.
- Automatically generates the 3 main types of NFAs.
- Displays and saves visualizations of each automaton.
- Modular code with separate functions for generation and visualization.

---

## Requirements

Before running the notebook, make sure to install the dependencies:

```bash
pip install FAdo
````

You may also need `graphviz` installed on your system to generate PNG images.

---

## References

* FAdo Library
* Automata Theory and Formal Languages
* Regular Expressions and Finite Automata Equivalence
