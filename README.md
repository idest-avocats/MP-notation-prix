# Marchés publics – notation du prix

Outil en ligne pour choisir la méthode de notation du prix au moment de rédiger les documents d’appel d’offres : effet d’un écart de prix selon la méthode et la pondération, avance nécessaire sur les autres critères pour compenser, avec ou sans prix prévus.

Outil développé par id est avocats Sàrl, Lausanne. Version 2.0 (beta), octobre 2026. Historique : [CHANGELOG.md](CHANGELOG.md).

## Ce que fait l’outil

- Saisie des critères d’adjudication et de leur pondération (prix et autres critères), avec contrôle du total.
- Choix de la méthode de notation du prix : T1,5, T2, T3, T200, T300 et Tmoyenne du Guide romand pour les marchés publics (annexe T2), méthode proportionnelle, méthode linéaire paramétrable.
- Pour la méthode choisie : points de prix (sur 100) obtenus par une offre selon son écart avec l’offre la moins chère, points perdus et avance nécessaire sur les autres critères pour revenir à égalité, pour des écarts de 5 % à 50 %.
- Graphique des points selon l’écart, avec comparaison des autres méthodes.
- En option, prix prévus (« Offre 1, 2, 3… », sans nom de soumissionnaire) : notes, points et points perdus pour chaque méthode, prix reportés sur le graphique.
- Alertes : pondération hors fourchette, méthode qui attribue la note 0 à une partie des offres, Tmoyenne avec moins de cinq prix, obligation d’annoncer la méthode.
- Résumé et texte prêt à copier pour les documents d’appel d’offres ; interface en français et en anglais.

## Ce que l’outil ne couvre pas

L’outil ne note pas les critères de qualité et ne classe pas des offres réelles ; il sert à choisir la méthode et la pondération avant l’appel d’offres. Il ne traite pas des offres anormalement basses, des variantes ni des rabais.

## Utilisation

1. Indiquer la pondération du prix et les autres critères.
2. Choisir la méthode ; pour la méthode linéaire, fixer l’écart x ; pour Tmoyenne, indiquer le montant estimé.
3. Lire l’effet d’un écart de prix dans le bandeau, le graphique et les tableaux ; activer la comparaison des méthodes pour arbitrer.
4. Au besoin, saisir des prix prévus pour voir l’effet sur des écarts concrets.
5. Copier le résumé ou le texte pour les documents d’appel d’offres.

## État du droit

Les formules reproduisent l’annexe T2 du Guide romand (version du 1er mai 2026). Les références jurisprudentielles figurent dans [SOURCES.md](SOURCES.md). Les modifications de l’outil sont consignées dans [CHANGELOG.md](CHANGELOG.md).

## Protection des données

Les calculs sont effectués dans le navigateur ; aucune donnée n’est conservée et aucun nom de soumissionnaire n’est demandé. Seuls le mode d’affichage et la langue choisis sont mémorisés localement sur l’appareil. L’outil est hébergé sur GitHub, qui peut collecter certaines informations selon sa propre déclaration relative à la protection des données.

## Sources et tests

- Sources : [SOURCES.md](SOURCES.md).
- Cas de référence : [CAS-DE-TEST.md](CAS-DE-TEST.md).
- Avertissement complet : [AVERTISSEMENT.md](AVERTISSEMENT.md).

## Licence

Code sous licence GNU AGPL 3.0 ou version ultérieure ([LICENSE](LICENSE)). Textes juridiques également sous licence CC BY-NC 4.0, avec attribution à id est avocats Sàrl.

## Contact

id est avocats Sàrl, Lausanne.

---

## English

An online tool to choose the price scoring method when drafting tender documents: effect of a price difference under each method and weighting (Guide romand methods T1.5, T2, T3, T200, T300, Tmoyenne, proportional and linear), lead needed on the other criteria to compensate, optional expected prices without bidder names, chart and method comparison, copyable text for the tender documents. French and English interface. Calculations run in the browser and no data is stored. Code under the GNU AGPL 3.0 or any later version; legal texts also under CC BY-NC 4.0 (attribution: id est avocats Sàrl).
