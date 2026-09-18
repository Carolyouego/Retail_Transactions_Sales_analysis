# Retail Transactions & Sales Analysis — Power BI

## Présentation du projet

Ce projet analyse les transactions de ventes d’une entreprise de commerce de détail afin de transformer des données brutes en informations claires et exploitables pour la prise de décision.

Le travail couvre la préparation des données avec **Power Query**, la création de mesures et KPI avec **DAX**, puis la conception d’un tableau de bord interactif dans **Power BI**.

---

## Objectifs

- Nettoyer et préparer les données transactionnelles.
- Mesurer la performance commerciale globale.
- Analyser le chiffre d’affaires par période, région, catégorie, produit et canal de vente.
- Étudier les volumes vendus et le comportement des clients.
- Identifier les catégories et produits qui contribuent le plus aux ventes.
- Comparer les performances des régions et des canaux de vente.
- Fournir des indicateurs facilitant la prise de décision.

---

## Technologies utilisées

 Technologie et Utilisation 

**Power BI** : Modélisation, analyse et tableaux de bord 
**Power Query** : Nettoyage et transformation des données 
**DAX** : Création des mesures et KPI 
**Excel / CSV** : Source des données 

---

## Préparation et nettoyage des données

Les données ont été préparées dans Power Query avant leur analyse.

Les principales opérations ont notamment porté sur :

- la vérification des types de données ;
- le traitement des valeurs manquantes ;
- la vérification des champs `Customer_ID`, `Region` et `Product` ;
- le contrôle des quantités, prix unitaires et remises ;
- le traitement des valeurs négatives ou incohérentes ;
- la vérification du montant des ventes.

La logique utilisée pour le montant des ventes est :

**Montant des ventes = Quantité × Prix unitaire × (1 − Remise)**

---

## KPI principaux

Le tableau de bord permet de suivre les indicateurs suivants :

 KPI et Résultat 
Chiffre d’affaires : **3 996 440,15 $** 
Nombre de clients : **1 489** 
Nombre de commandes : **7 848** 
Quantité vendue : **15 620 unités** 
Panier moyen : **509,23 $** 

---

## Structure du tableau de bord

Le rapport Power BI est organisé autour de trois axes d’analyse.

### 1. Performance commerciale, 2024–2025

Cette page fournit une vue d’ensemble de l’activité à travers les KPI principaux ainsi que :

- l’évolution mensuelle du chiffre d’affaires ;
- le chiffre d’affaires par région ;
- la répartition du chiffre d’affaires par canal de vente.

### 2. Analyse des produits

Cette page permet d’étudier :

- le chiffre d’affaires par catégorie ;
- la quantité vendue par catégorie ;
- le chiffre d’affaires par produit ;
- la quantité vendue ;
- le nombre de commandes ;
- le chiffre d’affaires détaillé par produit.

### 3. Région, Canaux et Clients

Cette page approfondit l’analyse avec :

- le chiffre d’affaires par région et canal ;
- la contribution des différents canaux dans chaque région ;
- le chiffre d’affaires par client ;
- la quantité achetée et le nombre de commandes par client.

---

## Principaux résultats

### Catégories de produits

La catégorie **Électronique** génère le chiffre d’affaires le plus élevé, avec environ **1,4 M$**.

Elle est suivie par les catégories **Sports**, **Maison**, **Vêtements** et **Beauté**.

Les quantités vendues par catégorie sont toutefois relativement proches. Cela suggère que l’importance de l’Électronique dans le chiffre d’affaires est davantage associée à la valeur des produits vendus qu’à un volume nettement supérieur.

### Évolution des ventes

Le chiffre d’affaires varie au cours de l’année. Le tableau de bord fait ressortir **août** comme le mois présentant le niveau de chiffre d’affaires le plus élevé, tandis que **février** figure parmi les périodes les plus faibles.

Cette information peut contribuer à la planification des campagnes commerciales et des ressources.

### Performance régionale

Les ventes sont réparties entre cinq régions :

**Alberta, Colombie-Britannique, Manitoba, Ontario et Québec.**

Les performances régionales sont relativement équilibrées, chacune représentant environ **0,8 M$** de chiffre d’affaires. L’activité ne dépend donc pas fortement d’une seule région dans les données analysées.

### Canaux de vente

La contribution des trois canaux au chiffre d’affaires est relativement équilibrée :

- **En ligne : ~34,37 %**
- **Magasin : ~33,08 %**
- **Téléphone : ~32,55 %**

Le canal en ligne arrive légèrement en tête, sans domination marquée.

### Analyse des clients

L’analyse par `Customer_ID` permet d’identifier les clients qui contribuent le plus au chiffre d’affaires et de comparer leur quantité achetée et leur nombre de commandes.

Cette vue peut notamment soutenir des initiatives de segmentation et de fidélisation.

---

## Recommandations métier

À partir des résultats observés :

- surveiller particulièrement la catégorie **Électronique**, qui contribue fortement au chiffre d’affaires ;
- approfondir les causes des variations mensuelles afin de mieux préparer les périodes de forte et de faible activité ;
- conserver une approche multicanale, puisque les trois canaux contribuent de manière relativement équilibrée aux ventes ;
- identifier les clients à forte valeur afin de soutenir des stratégies de fidélisation ciblées ;
- suivre les performances régionales afin d’adapter les actions commerciales aux différents marchés.

---

## Compétences démontrées

**Power BI • Power Query • DAX • Data Cleaning • Data Visualization • KPI • Analyse commerciale • Analyse clients • Analyse produits • Business Intelligence**

---

## À propos

Analyste de données orientée vers la transformation de données brutes en informations claires et exploitables pour soutenir la prise de décision.

**Compétences :** Power BI | SQL Server | Python | Excel | Power Query | DAX | Tableau

---

**Merci d’avoir consulté ce projet.**
