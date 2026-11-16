---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.about-intro { font-size: 1.05em; line-height: 1.7; margin-bottom: 1.5em; }
.home-actions { display: flex; flex-wrap: wrap; gap: 0.8em; margin: 1.5em 0 2em; }
.home-btn { display: inline-block; padding: 0.6em 1.2em; border-radius: 6px; color: #fff !important; text-decoration: none !important; font-weight: 600; }
.home-btn--green { background: #2e8b57; }
.home-btn--blue { background: #2f6fb3; }
.home-btn:hover { opacity: 0.85; }
.resume-sections { display: grid; grid-template-columns: 1fr 1fr; gap: 2em; margin-bottom: 2em; }
@media (max-width: 800px) { .resume-sections { grid-template-columns: 1fr; } }
.resume-item { border: 1px solid rgba(128,128,128,0.35); border-radius: 8px; padding: 0.8em 1em; margin-bottom: 0.9em; }
.resume-item__header { display: flex; align-items: center; gap: 0.8em; }
.resume-item__logo { width: 40px; height: 40px; flex: 0 0 40px; display: flex; align-items: center; justify-content: center; font-size: 1.5em; opacity: 0.8; }
.resume-item__logo img { max-width: 100%; max-height: 100%; }
.resume-item__org { margin: 0; font-size: 1em; flex: 1; }
.resume-item__date { font-size: 0.85em; opacity: 0.75; white-space: nowrap; }
.resume-item__role { margin: 0.5em 0 0 0; font-size: 0.95em; }
.skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1em; }
.skills-item { border: 1px solid rgba(128,128,128,0.35); border-radius: 8px; padding: 0.8em 1em; }
.skills-item h3 { margin: 0 0 0.4em 0; font-size: 1em; }
.skills-item p { margin: 0; font-size: 0.92em; }
</style>

<p class="about-intro">
Je suis [ton statut : doctorant / chercheur / étudiant en master] en [ta discipline] à l'Université de Sherbrooke (Québec, Canada) et à l'ENTPE (Vaulx-en-Velin, France). Mes recherches portent sur [ton sujet principal]. [1 ou 2 phrases sur tes méthodes, ton terrain ou tes objectifs.]
</p>

<div class="home-actions">
  <a href="/files/cv.pdf" class="home-btn home-btn--green"><i class="fas fa-download"></i> Télécharger mon CV (PDF)</a>
  <a href="/publications/" class="home-btn home-btn--blue"><i class="fas fa-book"></i> Voir mes publications</a>
</div>

<div class="resume-sections">
  <div class="resume-column">
    <h2>Formation</h2>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><i class="fas fa-graduation-cap"></i></div>
        <h3 class="resume-item__org">Université de Sherbrooke</h3>
        <div class="resume-item__date">[20XX–20XX]</div>
      </div>
      <p class="resume-item__role">[Diplôme, ex. Doctorat en génie civil]</p>
    </article>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><i class="fas fa-graduation-cap"></i></div>
        <h3 class="resume-item__org">ENTPE</h3>
        <div class="resume-item__date">[20XX–20XX]</div>
      </div>
      <p class="resume-item__role">[Diplôme]</p>
    </article>
  </div>
  <div class="resume-column">
    <h2>Expérience</h2>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><i class="fas fa-briefcase"></i></div>
        <h3 class="resume-item__org">[Organisation / laboratoire]</h3>
        <div class="resume-item__date">[Date – Présent]</div>
      </div>
      <p class="resume-item__role">[Poste ou mission]</p>
    </article>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><i class="fas fa-flask"></i></div>
        <h3 class="resume-item__org">[Organisation / laboratoire]</h3>
        <div class="resume-item__date">[Date – Date]</div>
      </div>
      <p class="resume-item__role">[Poste ou mission]</p>
    </article>
  </div>
</div>

<div class="skills-section">
  <h2>Compétences</h2>
  <div class="skills-grid">
    <div class="skills-item">
      <h3>[Domaine 1]</h3>
      <p>[Compétences, séparées par des virgules]</p>
    </div>
    <div class="skills-item">
      <h3>Programmation</h3>
      <p>[Python, MATLAB, ...]</p>
    </div>
    <div class="skills-item">
      <h3>Outils</h3>
      <p>[Logiciels, plateformes, ...]</p>
    </div>
    <div class="skills-item">
      <h3>Recherche et diffusion</h3>
      <p>[Articles, conférences, posters, ...]</p>
    </div>
  </div>
</div>
