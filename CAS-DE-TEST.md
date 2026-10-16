# Cas de test

Cas vérifiés avec l’outil (version 1.0). À refaire après chaque modification. Sauf mention contraire : pondération du prix de 40 %, autres critères saisis en note moyenne, pas d’arrondi.

## Formules (prix le plus bas : 100 ; prix moyen : 120 ; cinq offres)

| # | Méthode et prix | Note attendue |
|---|---|---|
| 1 | T2, prix 120 | 3,472 |
| 2 | T200, prix 150 | 2,5 |
| 3 | T200, prix 250 | 0 |
| 4 | T300, prix 200 | 2,5 |
| 5 | Linéaire 50 %, prix 125 | 2,5 |
| 6 | Tmoyenne, prix 120 (égal au prix moyen) | 4 |
| 7 | Tmoyenne, prix 140 | 3 |

## ATA/1113/2024 (Cour de justice de Genève, 24 septembre 2024)

| # | Données | Note attendue | Point contrôlé |
|---|---|---|---|
| 8 | Tmoyenne, formule du prix moyen ; offres de 317’076 et 372’496.04 | 3,00 pour la seconde | lot Châtillon, note retenue par la Cour |
| 9 | Même formule ; offres de 323’559 et 332’937.36 | 3,00 pour la seconde | lot Chânats |
| 10 | Même formule ; prix moyen de 516’892 (offres de 411’838, 499’054.22 et 639’784) | 4,17 pour l’offre de 499’054.22 | lot La Praille |
| 11 | Tmoyenne, variante du Guide romand avec un montant estimé de 369’467 ; offres de 317’075.51 et 372’496.04 | 4,85, soit 194 points à 40 % | formule appliquée par les SIG |

## Exemple de l’outil (bouton « Charger un exemple »)

Offres : Alpha SA 1’080’000 (autres critères 3,2), Bêta Sàrl 1’250’000 (4,4), Gamma SA 1’310’000 (4,8), Delta SA 1’620’000 (4,5).

| # | Données | Résultat attendu |
|---|---|---|
| 12 | Méthode T2 | Gamma SA première avec 423,94 points ; Bêta Sàrl 413,30 ; Alpha SA 392,00 ; Delta SA 358,89 |
| 13 | Seuils, méthode T2 | Gamma SA reste première jusqu’à 1’364’471.93 (+4,2 %) ; Bêta Sàrl passe première à 1’207’717.77 (−3,4 %) ou avec une note de 4,58 ; Alpha SA à 944’654.43 (−12,5 %) ou avec une note de 3,73 ; Delta SA à 1’231’029.51 (−24 %), note de 5,58 impossible |
| 14 | Comparaison des méthodes | Gamma SA première avec toutes les méthodes calculables ; Tmoyenne : montant estimé requis |
| 15 | Tmoyenne, variante du Guide romand, montant estimé de 1’300’000 | Gamma SA première avec 480,92 points |
| 16 | Tmoyenne, formule du prix moyen | Gamma SA première avec 448,85 points |
| 17 | Linéaire 30 % | Alpha SA première avec 392,00 points |

## Avertissements et interface

| # | Contrôle | Résultat attendu |
|---|---|---|
| 18 | Pondération du prix de 15 % | avertissement sur la fourchette de 20 % à 80 % (ATF 143 II 553) |
| 19 | Tmoyenne, moins de cinq offres, sans montant estimé | résultat non calculé ; avertissement demandant le montant estimé |
| 20 | Trois offres, dont une inférieure de plus de 30 % à la moyenne des deux autres | avertissement sur l’offre anormalement basse (art. 38 al. 3 AIMP 2019) |
| 21 | Autres critères saisis en points | libellés « Points des autres critères » ; total = points de prix + points saisis |
| 22 | Une seule offre | message « Saisissez au moins deux offres avec un prix » |

© 2026 id est avocats Sàrl, sous licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr).
