# Marchés publics – notation du prix – id est avocats

Outil en ligne de simulation de la notation du prix et du classement des offres en marchés publics, développé par id est avocats Sàrl.

> **Aide au calcul uniquement.** Seules la méthode et la pondération annoncées dans les documents d’appel d’offres font foi. Voir [AVERTISSEMENT.md](AVERTISSEMENT.md).

Version 1.0 (beta), octobre 2026. Historique : [CHANGELOG.md](CHANGELOG.md).

## Ce que fait l’outil

- **Méthodes de notation** : les six méthodes du Guide romand pour les marchés publics (T1,5, T2, T3, T200, T300 et Tmoyenne, annexe T2), la méthode proportionnelle et une méthode linéaire dont l’utilisateur fixe l’écart donnant la note 0.
- **Méthode Tmoyenne avec moins de cinq offres** : choix entre la variante du Guide romand (montant estimé par l’adjudicateur) et la formule fondée sur le prix moyen, selon ce qui a été annoncé (ATA/1113/2024).
- **Classement** : note du prix, points pondérés, autres critères (note moyenne de 0 à 5 ou points déjà pondérés), total sur 500 points et rang.
- **Seuils de bascule** : prix jusqu’auquel l’offre classée première conserve sa place ; prix auquel chaque autre offre passerait en tête ; note qu’il lui faudrait aux autres critères à prix inchangé.
- **Comparaison des méthodes** : les mêmes offres notées selon chaque méthode, avec le changement éventuel de l’offre classée première.
- **Courbes de notation** : graphique de toutes les méthodes, avec la position des offres sur la méthode annoncée.
- **Avertissements** : pondération du prix hors de la fourchette de 20 % à 80 %, offre inférieure de plus de 30 % à la moyenne des autres, difficultés de la méthode Tmoyenne, courbe trop plate, deux offres seulement, égalité en tête.
- **Résumé** prêt à copier : méthode, formule, classement, seuils et comparaison.

## Utilisation

1. Choisir la méthode annoncée et, le cas échéant, l’écart de la méthode linéaire ou la variante et le montant estimé de la méthode Tmoyenne.
2. Indiquer la pondération du prix et, si les documents d’appel d’offres le prévoient, l’arrondi des notes.
3. Saisir les offres : soumissionnaire, prix TTC et résultat aux autres critères. Le bouton « Charger un exemple » remplit quatre offres fictives.
4. Lire le classement, les seuils de bascule et la comparaison des méthodes, puis copier le résumé.

L’affichage peut être réglé en mode clair, sombre ou automatique.

## Protection des données

id est avocats ne collecte aucune donnée dans le cadre de l’utilisation de l’outil : les calculs sont effectués dans le navigateur et les montants saisis ne sont pas conservés. Seul le mode d’affichage est mémorisé dans le stockage local du navigateur (clé `idest-notation:theme`). L’outil est hébergé sur GitHub, qui peut collecter certaines informations, notamment au moyen de cookies, conformément à sa propre déclaration relative à la protection des données.

## Licence

© 2026 id est avocats Sàrl.

Le code est distribué sous licence GNU Affero General Public License, version 3 ou toute version ultérieure (AGPL-3.0-or-later). Voir [LICENSE](LICENSE).

Les tableaux et textes juridiques (formules, avertissements, principes, documentation) sont en outre mis à disposition sous licence [Creative Commons Attribution – Pas d’utilisation commerciale 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Attribution : « id est avocats Sàrl, Marchés publics – notation du prix ».
