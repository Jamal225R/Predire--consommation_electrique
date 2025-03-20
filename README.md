# Analyse de la consommation energetique et prediction  de besoin en electricité de notre region 📊

## Objectif
* predire la consommation d'electricité en tenant compte de certains facteurs.
* Predire  la demande en energie sachant qu'elle n'est pas stockable
* Mobiliser  les series temporelles notamment certains  objets type SARIMA

## Dataset
- **Source** : Données webscrappé sur le site de  RTE.
- **Variables** : Mois  , quantité, territoire,  production totale, nucleaire  , thermique  etc.

## Étapes de l'analyse
1. Nettoyage des données
2. Analyse des productions et  consommations energetiques
3. Visualisation des series temporelles
4. Corriger  les variations saisonnières par regression lineaire
5. Application de certains  outils  de series temporelles telles que  :la methode Holt Winters (lissage exponentiel)

## Techniques et methodologies  utilisées
* Prediction avec holt-winters 2
* Prediction Grace aux methodes SARIMA


## Tests statistiques
* Test de Shapiro-Wilk
