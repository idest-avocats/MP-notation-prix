# Cas de test

Cas vérifiés avec le moteur de l’outil (version 2.0 ; 23 tests). À refaire après chaque modification. Notes sur 5 ; points sur 100 = note ÷ 5 × pondération du prix.

## Notes selon l’écart avec l’offre la moins chère

| # | Méthode | Écart | Note attendue |
|---|---|---|---|
| 1 | T2 | +10 % | 4,13 |
| 2 | T1,5 | +10 % | 4,33 |
| 3 | T3 | +10 % | 3,76 |
| 4 | T200 | +50 % | 2,50 |
| 5 | T300 | +100 % | 2,50 |
| 6 | Proportionnelle | +25 % | 4,00 |
| 7 | Linéaire, x = 20 % | +10 % | 2,50 |
| 8 | Linéaire, x = 20 % | +30 % | 0 |

## Impact (prix pondéré à 40 %)

| # | Données | Résultat attendu |
|---|---|---|
| 9 | T2, +10 % | 33,06 points ; 6,9 points perdus ; avance nécessaire 0,58 sur 5 |
| 10 | T2, +20 % | 12,22 points perdus ; avance nécessaire 1,02 sur 5 |
| 11 | Tmoyenne sans prix prévus | pas de tableau d’impact ; invitation à saisir des prix |

## Prix prévus

| # | Données | Résultat attendu |
|---|---|---|
| 12 | Tmoyenne, 5 prix de 100’000 à 140’000 (ATA/1113/2024) | offre 3 : note 4,00 ; note 0 dès +100 % |
| 13 | T2, mêmes prix | offre 5 (+40 %) : 20,41 points ; avance nécessaire 1,63 |
| 14 | Exemple du bouton (1’000’000, 1’080’000, 1’150’000, 1’300’000), T2 | offre 4 : +30 %, note 2,96, 16,3 points perdus |

## Alertes

| # | Données | Résultat attendu |
|---|---|---|
| 15 | Pondération du prix 15 % | alerte sur la fourchette de 20 % à 80 % |
| 16 | Prix 40 % + autres critères 50 % | alerte : total différent de 100 % |
| 17 | Tmoyenne avec 3 prix | alerte sur le montant estimé (ATA/1113/2024) |
| 18 | Linéaire x = 10 %, prix 100, 105 et 130 | alerte : une offre obtient la note 0 |

## Interface

| # | Vérification | Résultat attendu |
|---|---|---|
| 19 | Bandeau par défaut (T2, 40 %) | −6,9 points pour une offre 10 % plus chère ; avance nécessaire 0,58 |
| 20 | Comparaison des méthodes | tableau des points perdus par méthode pour les écarts de 5 % à 50 % ; méthode choisie en gras |
| 21 | Version anglaise (`?lang=en`) | textes et critères par défaut en anglais |
