# Projet Power BI - Analyse en temps réel des Vélibs disponibles par station

---

## Description

Ce projet Power BI permet de visualiser la disponibilité des Vélibs (vélos en libre-service) par station dans la ville de Paris. Les données sont récupérées automatiquement via deux sources web officielles et combinées dans Power BI pour créer une carte interactive des stations Vélibs.

---

## Sources de données

Les données proviennent de deux liens web, récupérées directement dans Power BI :

- Informations sur les stations Vélibs (localisation, capacité, etc.) : https://velib-metropole-opendata.smovengo.cloud/opendata/Velib_Metropole/station_status.json
- Disponibilité des vélos et places libres en temps réel par station : https://velib-metropole-opendata.smovengo.cloud/opendata/Velib_Metropole/station_information.json

---

## Étapes du projet

1. **Récupération des données**  
   - Import des données via la fonctionnalité "Obtenir des données" > "Web" dans Power BI Desktop.  
   - Combinaison et traitement des données avec Power Query.

2. **Traitement des données dans Power BI**  
   - Nettoyage, fusion et calculs de métriques (vélos disponibles, places libres, taux d’occupation).  

3. **Création de la carte interactive**  
   - Visualisation géographique des stations avec code couleur et taille des points selon la disponibilité.

---

## Rapport Power BI

Le rapport est disponible au format PDF pour consultation :

[📄 Télécharger le rapport Power BI](https://github.com/GregoryBuriez/projet_velib_live/blob/main/Page%20BI.pdf)


> **Note :**  
> Le rapport Power BI n’est pas actualisé automatiquement pour l’instant.  
> Tu peux télécharger le fichier Power BI Desktop (.pbix) et actualiser les données manuellement.

---

## Utilisation

1. Clonez ce dépôt.  
2. Ouvrez le fichier Power BI Desktop (.pbix).  
3. Actualisez les données via Power BI pour charger les dernières informations en direct.  
4. Explorez la carte interactive et les filtres.

---

## Technologies utilisées

- Power BI Desktop  
- Power Query (M)  
- Sources web de données Vélibs (API publiques)

---
