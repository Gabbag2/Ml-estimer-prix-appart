# Estimation du Prix des Appartements - Projet de Régression

Ce projet consiste en une tâche de régression visant à estimer les prix de l'immobilier. L'estimation des prix des biens immobiliers est un sujet courant avec une riche littérature, reposant généralement sur des données comme l'emplacement, la surface, le terrain, le nombre de chambres, et l'âge du bâtiment.

L'objectif est de modéliser les prix des biens immobiliers résidentiels français à partir des données classiques présentées sous forme de tableaux hiérarchiques.

## Description des données
La variable de sortie **y** représente les prix des biens immobiliers proposés pour les actifs français, exprimés en euros.

La variable d'entrée **X** contient les informations suivantes :

### Exemples de données :
- Un identifiant de l'annonce
- Le type de bien (maison, appartement, copropriété, hôtel particulier, etc.)
- La localisation (latitude approximative, longitude approximative, ville, code postal, exposition, étage, le cas échéant)
- La superficie (surface habitable et surface du terrain, si applicable)
- Le nombre de pièces, de chambres, de salles de bains
- Les indicateurs de performance énergétique (énergie et émissions de gaz à effet de serre)
- Le nombre de photos jointes à l'annonce
- Les indicateurs relatifs à la présence d'une cave, d'un balcon, de la climatisation, etc.
- D'autres colonnes détaillant diverses caractéristiques

### Taille du dataset
L'échantillon global contient environ **50 000 annonces** et **300 000 photos**.

Nous avons réparti les données en 80% pour l'entraînement et 20% pour le test, ce qui correspond à environ **40K** annonces pour l'entraînement et **10K** pour le test.

### Observations
Il y avait quelques erreurs de saisie dans le dataset, ce qui explique pourquoi les résultats n'étaient pas parfaitement précis.

### Résultats
Nous avons terminé dans le **top 30** sur 180 participants, sachant que nous n'avons pas pu traiter les photos par manque de matériel. Nous avons atteint une précision de **30%**, tandis que le benchmark était à **37%**.
