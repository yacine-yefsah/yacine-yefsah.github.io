---
layout: default
title: Mes Projets 
---

<style>
  /* Force le conteneur principal à prendre toute la largeur */
  .main-content {
    max-width: 100% !important;
    padding: 2rem 2rem !important;
    margin: 0 !important;
  }

  .nav-container {
    display: flex; justify-content: center; background: #2c3e50; padding: 12px;
    margin: -30px -30px 30px -30px; position: sticky; top: 0; z-index: 1000;
    width: calc(100% + 60px);
  }
  .nav-link { color: white !important; margin: 0 15px; text-decoration: none; font-weight: bold; }
  .project-card {
    border: 1px solid #eee; padding: 15px; border-radius: 8px; margin-bottom: 20px;
    transition: 0.3s; background: #fafafa;
    width: 100%; /* S'assure que les cartes utilisent toute la largeur */
    box-sizing: border-box;
  }
  .project-card:hover { box-shadow: 0 4px 8px rgba(0,0,0,0.1); border-color: #3498db; }
  .btn-git {
    display: inline-block; padding: 6px 12px; background: #24292e; color: white !important;
    border-radius: 5px; text-decoration: none !important; font-size: 0.9em;
  }
</style>

<div class="nav-container">
  <a href="./index.html" class="nav-link">🏠 Accueil</a>
  <a href="./projets.html" class="nav-link">📊 Projets</a>
  <a href="./experiences.html" class="nav-link">💼 Expériences</a>
</div>

# Mes Projets Data Science & Statistiques

Retrouvez ici une sélection de mes travaux en science des données. Ces projets, issus de mon Master 1 SAAD ou de recherches personnelles, illustrent mon approche de l'analyse statistique et de la valorisation de la donnée.

---

<div class="project-card">
  <h3>Prédiction Immobilière - Boston Housing (Régression)</h3>
  <strong>Objectif :</strong> Prédire la valeur médiane des logements en analysant les variables socio-économiques.<br>
  <ul>
    <li><strong>Rigueur Statistique :</strong> Traitement des outliers (méthode IQR) permettant de passer d'un R² de 0.66 à <strong>0.75</strong>.</li>
    <li><strong>Outils :</strong> Python, Scikit-Learn, Seaborn.</li>
  </ul>
  <a href="https://github.com/yacine-yefsah/Immobilier-Prediction-ML" class="btn-git">Voir le Repo GitHub</a>
</div>

<div class="project-card">
  <h3>Diamonds Price Prediction (Random Forest)</h3>
  <strong>Objectif :</strong> Prédire le prix de +50 000 diamants selon leurs caractéristiques physiques.<br>
  <ul>
    <li><strong>Résultat :</strong> Score <strong>R² de 0.98</strong>, capturant les relations non-linéaires entre le carat et la clarté.</li>
    <li><strong>Outils :</strong> Random Forest Regressor, One-Hot Encoding.</li>
  </ul>
  <a href="https://github.com/yacine-yefsah/Diamonds-Price-Prediction-ML" class="btn-git">Voir le Repo GitHub</a>
</div>

<div class="project-card">
  <h3>Wine Classification (SVM)</h3>
  <strong>Objectif :</strong> Identifier l'origine de vins italiens via leur signature chimique.<br>
  <ul>
    <li><strong>Performance :</strong> <strong>97% de précision</strong> grâce à une normalisation StandardScaler et un noyau linéaire SVM.</li>
    <li><strong>Outils :</strong> Support Vector Machine, Matrice de Confusion.</li>
  </ul>
  <a href="https://github.com/yacine-yefsah/Support_Vector_Machine-SVM-" class="btn-git">Voir le Repo GitHub</a>
</div>

<div class="project-card">
  <h3>Penguin Segmentation (K-Means Clustering)</h3>
  <strong>Objectif :</strong> Découvrir des structures morphologiques cachées via l'apprentissage non-supervisé.<br>
  <ul>
    <li><strong>Méthode :</strong> Optimisation du nombre de clusters via la <strong>Méthode du Coude (Elbow Method)</strong>.</li>
    <li><strong>Outils :</strong> K-Means, Analyse des centroïdes.</li>
  </ul>
  <a href="https://github.com/yacine-yefsah/K-Means_Clustering" class="btn-git">Voir le Repo GitHub</a>
</div>

---

[⬅️ Retour à l'accueil](./index.html)
