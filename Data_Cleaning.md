# Data Cleaning — Power Query

## Contrôles réalisés

Le dataset a été préparé dans Power Query avant la construction du dashboard.

Les contrôles portent sur :

- les types de données ;
- les valeurs manquantes ;
- les doublons ;
- la cohérence des catégories ;
- les dates ;
- les champs numériques utilisés dans les calculs.

## Valeurs manquantes

`TerminationDate` contient des valeurs vides pour les employés actifs. Elles ne sont pas considérées comme une erreur : une date de fin n'est pas attendue lorsqu'un employé a encore le statut `Active`.

## Doublons

Le dataset contient :

- 0 doublon de ligne ;
- 0 EmployeeID dupliqué.

## Résultat

Après préparation, les données sont prêtes pour le modèle Power BI et les mesures DAX.
