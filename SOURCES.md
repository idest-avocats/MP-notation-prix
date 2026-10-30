# Sources

© 2026 id est avocats Sàrl ; texte sous licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Version 2.0 (beta), textes consultés en octobre 2026.

## Textes légaux

| Texte | Utilisation dans l’outil |
|---|---|
| Accord intercantonal sur les marchés publics du 15 novembre 2019 (AIMP 2019) | Critères d’adjudication et pondération (art. 29), offre anormalement basse (art. 38 al. 3), offre la plus avantageuse (art. 41), exclusion (art. 44 al. 2 let. c) |
| Loi fédérale sur les marchés publics (LMP, RS 172.056.1), [Fedlex](https://www.fedlex.admin.ch/eli/cc/2020/126/fr) | Mêmes dispositions pour les marchés de la Confédération (art. 29, 38, 41 et 44) |
| Règlement vaudois d’application de la loi sur les marchés publics (RLMP-VD) | Obligation d’annoncer la méthode de notation du prix (art. 4 al. 1 let. a) |
| Message concernant la révision totale de la LMP (FF 2017 1695, en particulier p. 1802) | La pente de la courbe de notation doit couvrir la fourchette de prix attendue |

## Guide romand pour les marchés publics (CROMP)

| Document | Utilisation dans l’outil |
|---|---|
| [Annexe T2](https://www.vd.ch/fileadmin/user_upload/themes/economie_emploi/march%C3%A9s_publics/Guide_romand/Fran%C3%A7ais/Annexe_T2.pdf), version du 1er mai 2026 | Méthodes T1,5, T2, T3, T200, T300 et Tmoyenne ; montants TTC ; offres recevables et contrôlées ; note 5 pour l’offre la moins chère ; variante de la méthode Tmoyenne avec moins de cinq offres |
| [Annexe O](https://www.vd.ch/fileadmin/user_upload/themes/economie_emploi/march%C3%A9s_publics/Guide_romand/Fran%C3%A7ais/Annexe_O.pdf), version du 15 décembre 2025 | Pondération du prix entre 20 % et 80 % ; offre inférieure de 30 % à la moyenne des autres ; notation des critères qualitatifs sur toute l’échelle |
| [Barème de notation, modèle vaudois](https://www.vd.ch/fileadmin/user_upload/themes/economie_emploi/march%C3%A9s_publics/Mod%C3%A8les_recommandations/Bar%C3%A8me_de_notation_crit%C3%A8res_1_2_3_5.pdf) | Formules détaillées des méthodes T3, T2, T1,5, T200 et Tmoyenne |

## Formules

| Méthode | Formule |
|---|---|
| T1,5 ; T2 ; T3 | Note = 5 × (prix le plus bas ÷ prix de l’offre) à la puissance 1,5, 2 ou 3 |
| T200 | Note = 5 × (2 × prix le plus bas − prix de l’offre) ÷ prix le plus bas ; note 0 dès le double du prix le plus bas |
| T300 | Note = 5 × (3 × prix le plus bas − prix de l’offre) ÷ (2 × prix le plus bas) ; note 0 dès le triple du prix le plus bas |
| Tmoyenne, cinq offres ou plus | Note = 5 − (prix de l’offre − prix le plus bas) ÷ (prix moyen − prix le plus bas) |
| Tmoyenne, moins de cinq offres (Guide romand) | Note = 5 − (prix de l’offre − prix le plus bas) ÷ montant estimé par l’adjudicateur |
| Proportionnelle | Note = 5 × prix le plus bas ÷ prix de l’offre |
| Linéaire paramétrable | Note = 5 × [1 − (prix de l’offre − prix le plus bas) ÷ (prix le plus bas × x %)] ; note 0 dès x % au-dessus du prix le plus bas |

Les notes sont comprises entre 0 et 5. L’outil exprime les points sur 100 (note ÷ 5 × pondération en pour cent), ce qui revient au barème sur 500 points du Guide romand. L’avance nécessaire sur les autres critères est la différence de note moyenne pondérée (sur 5) qu’une offre plus chère doit obtenir pour compenser les points de prix perdus : points perdus ÷ (100 − pondération du prix) × 5.

## Jurisprudence

| Décision | Point retenu |
|---|---|
| ATF 143 II 553 consid. 6.4 | Pondération du prix en principe entre 20 % et 80 % |
| TF 2C_802/2021 du 24 novembre 2022 | Pondération du prix d’au moins 60 % pour des prestations peu complexes |
| ATF 130 I 241 consid. 6.1 | Contrôle limité à l’abus ou à l’excès du pouvoir d’appréciation |
| Cour de justice de Genève, ATA/1113/2024 du 24 septembre 2024 | L’adjudicateur doit appliquer la formule annoncée ; la variante Tmoyenne du Guide romand n’est applicable que si elle a été annoncée ; modification admise seulement pour un motif objectif, notamment une dénaturation du critère du prix |
| Tribunal administratif du canton de Zurich, VB.2018.00444 du 25 octobre 2018 (cité dans l’ATA/1113/2024) | S’écarter de la formule annoncée viole le principe de transparence |

Doctrine citée par la Cour de justice : Domenico Di Cicco, *Le prix en droit des marchés publics*, 2022, n. 793 et 1030 ss.

## Choix de calcul

- **Arrondi** : par défaut, les notes du prix ne sont pas arrondies ; un arrondi à deux ou une décimale peut être choisi s’il est prévu par les documents d’appel d’offres.
- **Égalité** : deux totaux égaux à quatre décimales près sont classés au même rang.
- **Seuils de bascule** : calculés par approximations successives en ne modifiant que le prix de l’offre concernée ; le prix le plus bas et le prix moyen sont recalculés à chaque étape.
- **Offre anormalement basse** : signalée lorsque le prix est inférieur de plus de 30 % à la moyenne des autres offres (Guide romand, annexe O), à partir de trois offres.
- **Courbe trop plate** : signalée lorsque l’écart de prix atteint 20 % et que l’écart de points de prix reste inférieur à 20 % du poids du prix.
