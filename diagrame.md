
<script id= "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"> </script>

![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

# Diagrame de tip _Flowchart_

```mermaid
flowchart LR
A[/Anul I/] -->|Tranzitie suoara| B[\Anul II\]
A -.->|Tranzitie grea| C[\Anul IV/]
```

**De retinut:**
- Diagramele _floecharte_ au _noduri_ si _conectori_
- Nodurile au:
  - **forma** (data de parantezele folosite la descrierea _nodului_)
  - ID (sirul folosit in afara descrierii nodului)
  - Descriere (texul ce apare in caseta nodului si care este implementat in interiorul diferitelor tipuri de paramteze - ce decid forma casetei nodului)
  - Conectorii au:
   - Diferite tipuri de sageti sau chiar pot activa fara sageti
   - Diferite tipuri de linii :
      - `-->` linie continua (sageata dreapta)
      - `--` linie continua (fara sageata)
      - `<-->` linie continua (sageata stanga si sageata dreapta)
      - `==>` linie ingrosata cu sageata spre dreapta
      - 

  ## Diagrama _flowcharte_ avansat

  ```mermaid
A --> B & C & D --> E
  ```
