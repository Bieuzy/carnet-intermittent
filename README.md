# Carnet d'intermittent

Outil personnel pour les intermittents du spectacle : suivi des contrats, compteur des 507 heures, dates bookées (prévisionnel), import d'attestations PDF (AEM, GUSO) et estimation des indemnités France Travail (annexes 8 et 10).

**Ouvrir le carnet :** https://bieuzy.github.io/carnet-intermittent/

## Confidentialité

Ce dépôt ne contient que la page. Les contrats, heures et salaires saisis sont enregistrés uniquement dans le navigateur de l'appareil utilisé (stockage local) et ne sont envoyés nulle part. Les PDF importés sont lus dans le navigateur. Pour passer d'un appareil à l'autre, utilisez « Sauvegarder » puis « Restaurer une sauvegarde » dans l'onglet Contrats.

## Barèmes légaux

Tous les montants et règles de calcul (AJ minimale et maximale, planchers, formule A + B + C, plafond de cumul, PMSS, prélèvements, heures assimilées, clause de rattrapage) sont dans [`baremes.json`](baremes.json), avec la date de vérification et les sources officielles. La page charge ce fichier à chaque ouverture : pour appliquer un changement de réglementation, il suffit de modifier `baremes.json` (et la copie de secours `BAREMES` en tête du script de `index.html`).

La page affiche la date de dernière vérification et prévient l'utilisateur si elle date de plus de 4 mois.

## Avertissement

Les montants sont des estimations indicatives. Seule la notification de droits de France Travail fait foi.
