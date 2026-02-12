# Analyse des données criminelles 📊

Ce projet a pour objectif d’explorer et de visualiser un jeu de données sur la criminalité afin de mieux comprendre les tendances par **type de crime**, **période de la journée** et **évolution dans le temps**.

---

## 🎯 Objectifs
- Identifier les **types de crimes les plus fréquents**.
- Analyser l’**évolution des crimes par mois et par année**.
- Étudier la répartition des crimes selon la **période de la journée** (matin, après-midi, soir, nuit).
- Mettre en place des **visualisations interactives** pour faciliter l’interprétation.

---

## 🗂 Données

Le jeu de données étudié contient près d’un million d’enregistrements relatifs aux
incidents criminels signalés par la police. Chaque ligne correspond à un incident unique,
identifié par un numéro d’enregistrement. Les variables couvrent différents aspects : la
temporalité des événements, leur localisation géographique, les caractéristiques du crime
et de la victime, ainsi que des informations administratives liées au traitement de l’affaire.

---

## 🛠️ Technologies utilisées

- **Python**
  - `pandas` : nettoyage, transformation et agrégation des données
  - `numpy` : opérations numériques
- **Visualisation**
  - `plotly.express` : graphiques interactifs (lignes, barres, etc.)
  - `seaborn` / `matplotlib` pour des visualisations complémentaires

---

## 🔍 Analyses réalisées

- **Top 10 types de crimes**
  - Calcul des 10 crimes les plus fréquents et création d’un sous-ensemble de données pour se concentrer sur eux.

- **Évolution mensuelle / annuelle**
  - Regroupement des incidents par `année-mois` pour visualiser l’évolution du nombre de crimes dans le temps (courbes).

- **Évolution journalière**
  - Nombre d’incidents par jour et par type de crime pour suivre les tendances au jour le jour.

- **Crimes selon la période de la journée**
  - Création d’une colonne `Période` (matin, après-midi, soir, nuit) à partir de l’heure (`TIME OCC`).
  - Histogrammes empilés montrant la répartition des types de crimes selon le moment de la journée.

---

## 📈 Exemple de visualisations

- Courbe de l’**évolution du nombre de crimes par mois**.
- Graphique montrant les **Top 10 crimes selon la période de la journée**.
- Courbe de l’**évolution journalière** des principaux types de crimes.

---
