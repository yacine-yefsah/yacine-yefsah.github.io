---
layout: default
title: Accueil
---

<style>
  /* Force le conteneur principal du thème à prendre toute la largeur */
  .main-content {
    max-width: 100% !important;
    padding: 2rem 2rem !important;
    margin: 0 !important;
  }

  /* Barre de navigation en haut */
  .nav-container {
    display: flex;
    justify-content: center;
    background: #2c3e50;
    padding: 12px;
    margin: -30px -30px 30px -30px;
    position: sticky;
    top: 0;
    z-index: 1000;
    width: calc(100% + 60px);
  }
  .nav-link {
    color: white !important;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
  }
  .nav-link:hover { color: #1abc9c !important; }

  /* Style des boutons */
  .custom-btn {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px 5px;
    border-radius: 5px;
    text-decoration: none !important;
    font-weight: bold;
    transition: 0.3s;
  }
  .btn-main { background: #3498db; color: white !important; }
  .btn-cv { background: #e67e22; color: white !important; }
  .custom-btn:hover { opacity: 0.8; transform: translateY(-2px); }

  /* Timeline du parcours */
  .timeline { border-left: 3px solid #3498db; padding-left: 20px; margin-left: 10px; }
  .event { margin-bottom: 20px; position: relative; }
  .event::before {
    content: '';
    position: absolute;
    left: -27px;
    top: 5px;
    width: 12px;
    height: 12px;
    background: #3498db;
    border-radius: 50%;
  }

  /* Centrage de la recherche de stage sans les étoiles */
  .search-badge-centered {
    text-align: center;
    margin: 40px 0;
    font-size: 1.2em;
    width: 100%;
  }
</style>

<div class="nav-container">
  <a href="./index.html" class="nav-link">🏠 Accueil</a>
  <a href="./projets.html" class="nav-link">📊 Projets</a>
  <a href="./experiences.html" class="nav-link">💼 Expériences</a>
</div>

# Yacine Yefsah 
**Étudiant en Master 1 SAAD | Université de Caen**

<div class="search-badge-centered">
  <strong>🎯 À la recherche d’un stage de 3 à 4 mois à partir de mai 2026, et reste également ouvert à une opportunité d’alternance.</strong>
</div>

---

### 🎓 Mon Parcours académique
<div class="timeline">
  <div class="event">
    <strong>2025 - Présent : Master 1 SAAD</strong><br>
    Statistique Appliquée et Analyse Décisionnelle | <em>Université de Caen Normandie</em>
  </div>
  <div class="event">
    <strong>2023 - 2025 : Licence MIASHS</strong><br>
    Mathématiques et informatique appliquées aux sciences humaines et sociales | <em>Université de Caen Normandie</em>
  </div>
  <div class="event">
    <strong>2020 - 2023 : Licence en Mathématiques et Informatique</strong><br>
    <em>Université des Sciences et de la Technologie Houari Boumediene, Algérie</em>
  </div>
</div>

---

### Coordonnées
- 💼 **LinkedIn :** [Yacine Yefsah](https://www.linkedin.com/in/yacine-yefsah-00a152290/)
- 📧 **Email :** [yyacine2909@gmail.com](mailto:yyacine2909@gmail.com)
- 📱 **Téléphone :** +33 6 65 16 38 74
- 📍 **Ville :** Caen, France

---

<div style="margin-top: 30px; text-align: center;">
  <a href="./projets.html" class="custom-btn btn-main">📁 Voir mes Projets</a>
  <a href="./CV_Yacine_Yefsah.pdf" class="custom-btn btn-cv">📄 Télécharger mon CV</a>
</div>
