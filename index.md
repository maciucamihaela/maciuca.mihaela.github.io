**Cuprins**

[Formule cu Mathjax](formuele_mathjax.md)

[Formuule cu Mathjax](formule_mathjax2.md)

[Diagrame](diagrame)

***

# Implementarea relatiilor in Markdown

## Implementarea relatiilor/legaturilor catre alte fisiere

Fisierele accesate prin link-uri pot fi:
1. Gazduite pe alte servere (de ex.: accesarea unui alt site)
2. Gazduite pe serverul site-ului curent.

De asemenea, prin aceste linkuri se pot accesa si sectiuni din pagina curenta sau sectiuni din alte pagini ale aceluiasi site.

### Sintaxa unui link Markdown 

Tipuri de linkuri in Markdown:
1. Linkuri clasice (normale)
2. Linkuri referentiate

#### Linkurile clasice

**Variante:**
[Textul linkului](https://google.com/)
[Textul linkului](https://google.com/ "Accesare site Google")

#### Linkurile referentiate

Iata un [link][link1] catre site-ul Google.

[link1]: https://google.com/

Varianta prescurtata a linkurilor referentiate:

Iata un link [important] catre site-ul Google.

[important]: https://google.com/

#### Linkuri catre imagini

![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)
