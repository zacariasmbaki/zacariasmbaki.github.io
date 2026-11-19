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
.resume-item__logo { width: 80px; height: 56px; flex: 0 0 80px; display: flex; align-items: center; justify-content: center; font-size: 1.5em; }
.resume-item__logo img { max-width: 100%; max-height: 100%; object-fit: contain; background: #fff; border-radius: 4px; padding: 2px; }
.resume-item__org { margin: 0; font-size: 1em; flex: 1; }
.resume-item__date { font-size: 0.85em; opacity: 0.75; white-space: nowrap; }
.resume-item__role { margin: 0.5em 0 0 0; font-size: 0.95em; }
.skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1em; }
.skills-item { border: 1px solid rgba(128,128,128,0.35); border-radius: 8px; padding: 0.8em 1em; }
.skills-item h3 { margin: 0 0 0.4em 0; font-size: 1em; }
.skills-item p { margin: 0; font-size: 0.92em; }
</style>

<p class="about-intro">
I am a Joint PhD candidate at Université de Sherbrooke (Québec, Canada), in Civil Engineering, and ENTPE (Vaulx-en-Velin, France), in Mechanical Engineering. My research focuses on numerical fluid-structure interaction, nonlinear structural dynamics and vibration control, with applications to overhead powerline structures. I hold a MEng in Mechanical Engineering from INSA Lyon and combine numerical modelling with experimental structural dynamics and wind tunnel testing.
</p>

<div class="home-actions">
  <a href="/files/cv.pdf" target="_blank" rel="noopener noreferrer" class="home-btn home-btn--green"><i class="fas fa-download"></i> Download CV (PDF)</a>
  <a href="/publications/" class="home-btn home-btn--blue"><i class="fas fa-book"></i> View Publications</a>
</div>

<div class="resume-sections">
  <div class="resume-column">
    <h2>Education</h2>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><img src="/images/UDES.png" alt="Université de Sherbrooke logo"></div>
        <h3 class="resume-item__org">Université de Sherbrooke, Canada</h3>
        <div class="resume-item__date">2024 – Present</div>
      </div>
      <p class="resume-item__role">Joint PhD in Civil Engineering — Numerical Fluid-Structure Interaction and Overhead Powerline Structures</p>
    </article>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><img src="/images/ENTPE.jpg" alt="ENTPE logo"></div>
        <h3 class="resume-item__org">ENTPE, France</h3>
        <div class="resume-item__date">2024 – Present</div>
      </div>
      <p class="resume-item__role">Joint PhD in Mechanical Engineering — Nonlinear Structural Dynamics and Vibration Control</p>
    </article>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><img src="/images/INSA.jpg" alt="INSA logo"></div>
        <h3 class="resume-item__org">INSA Lyon, France</h3>
        <div class="resume-item__date">2021 – 2024</div>
      </div>
      <p class="resume-item__role">MEng in Mechanical Engineering — Product Design and Innovation</p>
    </article>
  </div>

  <div class="resume-column">
    <h2>Experience</h2>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><img src="/images/ETIC.png" alt="ETIC logo"></div>
        <h3 class="resume-item__org">ETIC INSA Technologies, Lyon, France</h3>
        <div class="resume-item__date">Aug 2023 – Jul 2024</div>
      </div>
      <p class="resume-item__role">Consulting Engineer, Fluid-Structure Interaction</p>
      <p class="resume-item__role"><em>Activities:</em> CFD Modelling, Experimental Characterization of Composite Materials, Finite Element Modelling</p>
    </article>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><img src="/images/IMS.jpg" alt="IMS logo"></div>
        <h3 class="resume-item__org">Institute for Mechatronic Systems (IMS), Darmstadt, Germany</h3>
        <div class="resume-item__date">Jul 2023 – Oct 2023</div>
      </div>
      <p class="resume-item__role">Research Intern, Vehicle Dynamics Team</p>
      <p class="resume-item__role"><em>Activities:</em> Product Design, Reverse Engineering, Numerical Modelling</p>
    </article>
    <article class="resume-item">
      <div class="resume-item__header">
        <div class="resume-item__logo"><img src="/images/EFI.png" alt="EFI logo"></div>
        <h3 class="resume-item__org">EFI Automotive, Saint-Maurice-de-Beynost, France</h3>
        <div class="resume-item__date">2021 – 2024</div>
      </div>
      <p class="resume-item__role">R&amp;D Mechanical Design Engineer (Apprenticeship), Advanced Research Team</p>
      <p class="resume-item__role"><em>Activities:</em> Product Design, Benchmarking, Reverse Engineering, System Modelling, Prototyping and Testing</p>
    </article>
  </div>
</div>

<div class="skills-section">
  <h2>Skills</h2>
  <div class="skills-grid">
    <div class="skills-item">
      <h3>Mechanical Design &amp; Manufacturing</h3>
      <p>CAD (SolidWorks, CATIA V5, Creo, 3DEXPERIENCE), GD&amp;T (CETOL, 3DCS), CAM (TopSolid, Esprit), PLM</p>
    </div>
    <div class="skills-item">
      <h3>Structural Modelling &amp; Simulation</h3>
      <p>Linear and Nonlinear Finite Element Modelling (Abaqus, Code_Aster), CFD (Ansys Fluent, STAR-CCM+), Gmsh, MSC Adams, Simulink</p>
    </div>
    <div class="skills-item">
      <h3>Experimental Skills</h3>
      <p>Experimental Structural Dynamics, Experimental Acoustics, Wind Tunnel Testing</p>
    </div>
    <div class="skills-item">
      <h3>Programming</h3>
      <p>Python, MATLAB, VBA</p>
    </div>
    <div class="skills-item">
      <h3>Communication</h3>
      <p>Scientific Outreach, Poster Presentations, Scientific Presentations</p>
    </div>
  </div>
</div>
