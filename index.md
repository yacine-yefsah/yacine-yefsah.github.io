---
layout: default
title: Accueil
---

<style>
  /* Barre de navigation en haut */
  .nav-container {
    display: flex;
    justify-content: center;
    background: #2c3e50;
    padding: 12px;
    margin: -30px -30px 30px -30px; /* Aligné avec le thème Cayman */
    position: sticky;
    top: 0;
    z-index: 1000;
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
</style>

<div class="nav-container">
  <a href="./index.html" class="nav-link">🏠 Accueil</a>
  <a href="./projets.html" class="nav-link">📊 Projets</a>
  <a href="./experiences.html" class="nav-link">💼 Parcours</a>
</div>

# Yacine Yefsah 
**Étudiant en Master 1 SAAD | Université de Caen**
<div class="search-badge">
  🎯 À la recherche d’un stage de 3 à 4 mois à partir de mai 2026, et reste également ouvert à une opportunité d’alternance.
</div>

<div style="margin-top: 20px;">
  <a href="./projets.html" class="custom-btn btn-main">📁 Voir mes Projets</a>
  <a href="./CV_Yacine_Yefsah.pdf" class="custom-btn btn-cv">📄 Télécharger mon CV</a>
</div>

---

### Coordonnées
- 💼 **LinkedIn :** [YEFSAH Yacine](https://www.linkedin.com/in/yacine-yefsah-00a152290/)
- 📧 **Email :** [yyacine2909@gmail.com](mailto:yyacine2909@gmail.com)
- 📱 **Téléphone :** +33 6 65 16 38 74
- 📍 **Ville :** Caen, France

---

### 🎓 Mon Parcours académique
<div class="timeline">
  <div class="event">
    <strong>2025 - Présent : Master 1 SAAD</strong><br>
    Statistique Appliquée et Analyse Décisionnelle | <em>Université de Caen Normandie</em>
  </div>
  <div class="event">
    <strong>2021 - 2024 : Licence Mathématiques & Informatique</strong><br>
    Spécialité Statistique | <em>[Nom de ton Université]</em>
  </div>
  <div class="event">
    <strong>2021 : Baccalauréat Scientifique</strong><br>
    Mention [Ta mention] | <em>[Nom de ton Lycée]</em>
  </div>
</div>
