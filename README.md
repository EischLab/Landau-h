# Landau-h
This script allows for the generation of sociomatrices, Landau's h, and DeVries' correction for missing samples for societies of variable size


We include a COLAB notebook for folks with no coding/programming experience

---
Landau's linearity index (h) for social dominance ranges from 0 (fully non-linear) to 1 (fully linear), with 0.7 suggested as a threshold for linearity.

This is a society-wide (not animal-specific) measure after observations of animals at social conflict, often, but not always over a limited resource.

For perfectly dyadic societies (no ties or censored scores) Landau's h works well. For non-dyadic societies, with ties or censored scores, we use DeVries' correction to obtain h'.

This worksheet enables you to generate a sociomatrix and calculate h and h' by simply inputing a society n, and designating the winner, unknown or average wins for each pairing.

---

# Installation

`pip-install pandas`

---

References: 

>*On Dominance Relations and the Structure of Animal Societies: I. Effect of Inherent Characteristics. H.G. Landau, 1951*

>*An improved test of linearity in dominance hierarchies containing unknown or tied relationships. H. DeVries, 1995*
---

