---
label: Rendu HTML
order: -30
---

# Rendu HTML des différents composants

## Tableau {#table}

### Markdown 

<div class="caption">Titre du tableau</caption>
  
| Colonne 1           | Colonne 2 |
|---------------------|----------:|
| texte de la cellule | jkhjkjhkj |
| Autre texte         |    jkhhkj |


### HTML

<table>
  <caption>Titre du tableau</caption>
  <thead><tr><th>Colonne 1</th><th style="text-align: right;">Colonne 2</th></tr></thead>
  <tbody><tr><td>texte de la cellule</td><td style="text-align: right;">jkhjkjhkj</td></tr><tr><td>Autre texte</td><td style="text-align: right;">jkhhkj</td></tr></tbody>
</table>

## Une image

### Markdown

![Le VIH](vih.jpg)

### HTML

<figure>
  <img src="vih.jpg" alt="Le VIH" />
  <figcaption>Le virus VIH</figcaption>
</figure>

## Blocs d'info

!!!
Alerte simple
!!!

!!! Alerte simple avec titre
Et le texte qui va avec
!!!


!!!primary Primary
This is a `primary` alert.
!!!

!!!secondary Secondary
This is a `secondary` alert.
!!!

!!!success Success
This is a `success` alert.
!!!

!!!danger Danger
This is a `danger` alert.
!!!

!!!warning Warning
This is a `warning` alert.
!!!

!!!info Info
This is a `info` alert.
!!!

!!!light Light
This is a `light` alert.
!!!

!!!dark Dark
This is a `dark` alert.
!!!

!!!contrast Contrast
This is a `contrast` alert.
!!!

## Liste de définitions

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Inclusion d'une vidéo Youtube

https://youtu.be/W5F6kvCMosc

<iframe width="560" height="315" src="https://www.youtube.com/embed/W5F6kvCMosc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Notes de bas de page

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
