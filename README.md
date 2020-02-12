[//]: <> (Text can be **bold**, _italic_, or ~~strikethrough~~.)

[//]: <> (There should be whitespace between paragraphs.)

[//]: <> (There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.)

# Le projet

Il s'agit d'un logiciel permettant à un utilisateur d'interagir avec n'importe quel graphe. Aussi bien les graphes orientés que les graphes non-orientés.
Il permet de créer son propre graphe d'une part ou d'en importer un afin de faire des modifications dessus ou y appliquer certaines fonctions.

# Qui sommes nous ?
Etudiants à l'Epita, nous nous sommes fixés l'objectif de réaliser ce logiciel pour notre quatrième semestre.
Le groupe:
*   Mohamed DIALLO
*   Amayun HOUERY
*   Anthony JABRE
*   Alexandre JAMES

# La structure de graphes

```C
typedef struct graph
{
    uint32_t    order;
    int         directed;
    List**      adjlists;
} Graph;
```

# Le cahier des charges

Notre [cahier des charges](https://fr.overleaf.com/gallery "Overleaf") pour le projet est disponible sur overleaf

# Avancement

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

* * *
