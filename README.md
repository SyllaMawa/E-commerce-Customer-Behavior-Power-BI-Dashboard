# 📊 E-commerce Customer Behavior — Power BI Dashboard

Analyse du comportement d’achat des clients d’un site e-commerce à partir d’un dataset Kaggle.

---

## 🎯 Objectif du projet

L’objectif de ce projet est d’analyser les comportements d’achat clients afin de :

- Identifier les profils clients dominants  
- Comprendre les habitudes de consommation  
- Analyser la performance commerciale  
- Proposer des recommandations business concrètes  

Ce projet s’inscrit dans une démarche complète de data analyse :

- Préparation des données  
- Transformation et enrichissement  
- Visualisation sous Power BI  
- Analyse et interprétation métier  

---

## 🗂️ Dataset

- **Source** : Kaggle — *E-commerce Customer Behavior – Sheet1*  
- **Taille** : 58 observations  
- **Particularité** : dataset déjà filtré avant utilisation  

### Variables principales :
- City  
- Gender  
- Age  
- Membership Type  
- Items Purchased  
- Total Spend  
- Average Rating  

---

## 🛠️ Préparation des données

### 🔧 Transformations réalisées

- Vérification et nettoyage des données  
- Harmonisation des variables catégorielles  
- Typage des colonnes  

### ➕ Enrichissement des données

Création d’une colonne conditionnelle **Age_group** dans Power BI :

- 18–35 → *Young Adult*  
- 36–55 → *Adult*  
- 56+ → *Senior*  

### 📐 Mesures DAX créées

- Total Spend  
- Total Items Purchased  
- Average Rating  

---

## 📊 Dashboard Power BI

Le dashboard est structuré autour de trois axes principaux :

### 1. Profil client
- Répartition par genre  
- Segmentation par âge  
- Type de membership  

### 2. Comportement d’achat
- Nombre total d’articles achetés  
- Dépenses totales  
- Intensité d’achat  

### 3. Performance commerciale
- Analyse par ville  
- Indicateurs de satisfaction  
- Corrélation entre dépenses et comportement  

---

## 📈 Analyse Business

### 1. Vue d’ensemble

L’analyse met en évidence un segment client fortement homogène :

- Majoritairement féminin (≈ 82 %)  
- 100 % appartenant à la catégorie *Adult*  
- 100 % membres *Silver*  
- Activité concentrée sur la ville de Miami  

Ce segment constitue le cœur actif du dataset analysé.

---

### 2. Comportement d’achat

- **675 articles achetés**  
- **660,3 de dépenses totales**

Malgré un statut *Silver*, les clients présentent un niveau d’engagement élevé.

👉 **Lecture business** :  
Le comportement observé est proche d’un segment à forte valeur, suggérant un potentiel d’augmentation de la valeur client.

---

### 3. Analyse géographique

Bien que le dataset contienne plusieurs villes, les données exploitées montrent une concentration des transactions sur **Miami**.

👉 **Lecture business** :  
- Marché local fortement actif  
- Opportunité de consolidation sur cette zone  
- Nécessité d’élargir l’analyse pour une vision globale  

---

### 4. Satisfaction client

Les indicateurs de rating sont principalement associés au segment adulte et indiquent un niveau de satisfaction globalement positif.

👉 **Lecture business** :  
Un bon niveau de satisfaction constitue un levier clé pour :
- la fidélisation  
- l’upsell  
- la recommandation client  

---

## 🧠 Recommandations Business

### 1. Maximisation de la valeur client
- Mettre en place des offres **premium (Gold / Platinum)**  
- Développer des stratégies d’**upsell et cross-sell**  
- Créer des avantages exclusifs pour les membres Silver  

### 2. Personnalisation marketing
- Campagnes ciblées basées sur le comportement d’achat  
- Recommandations produits personnalisées  
- Segmentation avancée  

### 3. Expansion analytique
- Intégrer un dataset complet non filtré  
- Comparer les performances entre villes  
- Identifier de nouveaux segments clients  

---

##  Limites méthodologiques

- Dataset déjà filtré avant analyse  
- Échantillon réduit (58 clients)  
- Faible diversité démographique  
- Concentration géographique sur une seule ville  

👉 Les résultats doivent être interprétés comme une **analyse exploratoire** et non comme une vision exhaustive du marché.

---

##  Aperçu du dashboard

![Dashboard Overview](images/dashboard_overview.png)

---

## 📁 Structure du projet
