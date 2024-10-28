



[Homepage](index.md)

# Inserarea ecuatiilor si formulelor 'MathJax'

**Sintaxma:**

Formule 'MathJax' sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri '$'.

*Exemplu:* aceasta este o ecuatie $a=bc$

Formule 'LaTex' (prin 'MathJax' ) se introduc pe rand nou intre doua parechi simbolul '$$'

*Exemplu:* 

$$a=b^c$$

# Ridicat la putere ('superscript')

Se foloseste 

*Exemplu:*

$$a=10^7$$

# 'Subscript'

Se foloseste meta-caracterul 'LaTex' : '_'

*Exemplu:*

$$a_i = b^c$$



# Gruparea elementelor din formule

Elementele din formule se grupeaza prin meta-caracterul

$$ 10^{10} $$

# Litere grecesti

* Exemplu:*

'\alpha' - alpha litera mica ($\alpha$)

'\Alpha' - alpha litera mare ($$\Alpha$$)

# Paranteza

- Parantezale rotumde se scriu direct (nu au inteles special 'LaTex')

- Parantezale patrate se scriu direct (nu au inteles special 'LaTex'
  
- Acoladele, deoarece ele sunt metacaractele de grupe, vor fi renderizate corect daca sunt 'escapade' de intelesul lor special punand in fata lor 'metacaracterul' '\'

*Exemplu:*

$$a = (b+c)^{3x} - [3+6x]$$

# Fractiile

 
  `\frac{numarator}{numitor}`

  *Exemplu: * 
  

  $$ a= \frac{(a+bc)}{(d-c)}$$
  # Semnele de multiplicare si respectiv de diviziune 
  *Exemplu:*

  $$ a = c + 10 \times x $$

  $$ a = c + 10 \cdot x $$
  
  $$ a = b \div c$$


  # Suma de la i=0 la n
  
  **Exemplu:**
  
  $$ \sum_{i=0}^n i^2 = \frac {(a+b)\times (b+c)} {6} $$

# Integrale 

**Exemplu:**

$$ \int_0^1 X^4 dx $$

$$ \iint_0^1 X^4 dx $$






















