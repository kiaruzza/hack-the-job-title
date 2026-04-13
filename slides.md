---
theme: default
background: white
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
mdc: true
fonts:
  sans: Inter
  serif: Inter
  mono: Fira Code
---

<style>
:root {
  --red-main: #E8001C;
  --red-dark: #B8001A;
  --red-pale: #FFF0F0;
  --red-light: #FFD6D6;
  --navy: #1a1f3a;
  --gray-soft: #F8F8F8;
  --gray-border: #E8E8E8;
}
.speaker-badge {
  display: inline-block;
  background: var(--red-pale);
  color: var(--red-dark);
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  padding: 0.2rem 0.7rem;
  border-radius: 20px;
  margin-bottom: 0.8rem;
}
.cluster-box {
  border: 1.5px solid var(--gray-border);
  border-radius: 12px;
  padding: 1.2rem 1.4rem;
  background: var(--gray-soft);
}
.cluster-box-title {
  font-size: 0.8rem;
  font-weight: 700;
  color: var(--red-main);
  margin-bottom: 0.6rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}
.highlight-line {
  font-size: 1.6rem;
  font-weight: 800;
  color: var(--navy);
  line-height: 1.3;
}
.highlight-line span { color: var(--red-main); }
.data-box {
  background: var(--red-pale);
  border-left: 4px solid var(--red-main);
  border-radius: 0 12px 12px 0;
  padding: 1rem 1.2rem;
  font-size: 0.9rem;
  color: var(--navy);
}
.source-note {
  font-size: 0.65rem;
  color: #888;
  font-style: italic;
  margin-top: 0.4rem;
}
.avatar {
  width: 64px;
  height: 64px;
  border-radius: 50%;
  border: 3px solid white;
  overflow: hidden;
  background: #B8001A;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}
.avatar img { width: 100%; height: 100%; object-fit: cover; }
.avatar-sm {
  width: 52px;
  height: 52px;
  border-radius: 50%;
  border: 2px solid #E8001C;
  overflow: hidden;
  background: #FFF0F0;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}
.avatar-sm img { width: 100%; height: 100%; object-fit: cover; }
.job-post {
  background: #FAFAFA;
  border: 1.5px solid #E8E8E8;
  border-radius: 12px;
  padding: 1rem 1.2rem;
  font-size: 0.82rem;
  color: #1a1f3a;
  font-family: 'Fira Code', monospace;
  line-height: 1.6;
}
.ann-verb {
  background: #E8001C;
  color: white;
  border-radius: 4px;
  padding: 0 4px;
  font-weight: 700;
  font-style: normal;
}
.ann-soft {
  background: #FFD6D6;
  color: #B8001A;
  border-radius: 4px;
  padding: 0 4px;
  font-weight: 700;
  font-style: normal;
}
.ann-wishlist {
  background: #F0F0F0;
  color: #888;
  border-radius: 4px;
  padding: 0 4px;
  text-decoration: line-through;
  font-weight: 600;
}
.ann-cluster {
  background: #1a1f3a;
  color: white;
  border-radius: 4px;
  padding: 0 4px;
  font-weight: 700;
  font-style: normal;
}
</style>

---
layout: cover
background: https://donne4.it/wp-content/uploads/2025/10/C52A12D2-65AE-4353-B2E9-1C68C0E75E9B.jpg?id=19999
---

<div style="position:absolute;inset:0;background:linear-gradient(to right, rgba(232,0,28,0.88) 0%, rgba(232,0,28,0.65) 55%, rgba(0,0,0,0.25) 100%);"></div>

<div style="position:relative;z-index:10;display:flex;flex-direction:column;justify-content:center;height:100%;padding:0 3rem;">

<div style="margin-bottom:0.6rem;text-align: center">
    <span style="font-size:0.75rem;font-weight:700;letter-spacing:0.2em;text-transform:uppercase;color:rgba(255,255,255,0.8);">
        Talk &middot; Career &middot; Tech Culture
    </span>
</div>

<h1 style="font-size:3rem;font-weight:900;color:white;line-height:1.1;margin-bottom:0.8rem;text-shadow:0 2px 8px rgba(0,0,0,0.3);">
<div class="flex items-center justify-center gap-4">
    <img src="https://devfest.gdgpisa.it/_astro/logo_wtm_quadrato_2026.pWtoT8-u.png" class="h-10" />
    Hack the Job Title
    <img src="https://donne4.it/wp-content/uploads/2021/08/Logo-donne4-rit-100px.png" class="h-10" />
</div>
</h1>

<p style="font-size:1.3rem;font-weight:600;color:rgba(255,255,255,0.92);margin-bottom:2rem;text-align: center">
  Il lavoro reale dietro i titoli del tech
</p>

<div style="display:flex;gap:2rem;flex-wrap:wrap;margin-bottom:2rem;align-items:center;justify-content: center">

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.5rem;">
    <div class="avatar">
      <img src="https://sessionize.com/image/bbe0-400o400o1-GC45U3jx4Sw9b64DsYA27P.jpg" alt="Chiara Corrado" />
    </div>
    <div style="text-align:center;">
      <div style="font-weight:700;color:white;font-size:0.82rem;">Chiara Corrado</div>
      <div style="font-size:0.65rem;color:rgba(255,255,255,0.78);">Tech &amp; Orientamento</div>
    </div>
  </div>

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.5rem;">
    <div class="avatar">
      <img src="https://sessionize.com/image/9112-400o400o1-hraEvrgu5KGZL1xUam5LzQ.jpg" alt="Luciana Bertoncini" />
    </div>
    <div style="text-align:center;">
      <div style="font-weight:700;color:white;font-size:0.82rem;">Luciana Bertoncini</div>
      <div style="font-size:0.65rem;color:rgba(255,255,255,0.78);">Tech &amp; Ruoli</div>
    </div>
  </div>

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.5rem;">
    <div class="avatar">
      <img src="https://sessionize.com/image/1005-400o400o1-LiWyv11N1uKXiiE87fTsgx.png" alt="Pinelopi Troullinou" />
    </div>
    <div style="text-align:center;">
      <div style="font-weight:700;color:white;font-size:0.82rem;">Pinelopi Troullinou</div>
      <div style="font-size:0.65rem;color:rgba(255,255,255,0.78);">Ethics &amp; Linguaggio</div>
    </div>
  </div>

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.5rem;">
    <div class="avatar">
      <img src="https://sessionize.com/image/442b-400o400o1-9XRUwCu9oubMHygXNLLMiH.jpg" alt="Federica Merenda" />
    </div>
    <div style="text-align:center;">
      <div style="font-weight:700;color:white;font-size:0.82rem;">Federica Merenda</div>
      <div style="font-size:0.65rem;color:rgba(255,255,255,0.78);">Gender Equality</div>
    </div>
  </div>

</div>

<div style="font-size:0.82rem;color:rgba(255,255,255,0.75);font-weight:600;text-align: center">
  Donne 4.0 &times; WTM Pisa
</div>

</div>

---
layout: center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Chi siamo &mdash; Donne 4.0
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:720px;margin:0 auto 1.2rem;">

<div class="cluster-box">
<div class="cluster-box-title">La missione</div>
<p>Rendere <strong>protagoniste le donne</strong> nell&rsquo;affrontare le sfide globali e costruire con le tecnologie un futuro <strong>inclusivo e sostenibile</strong>.</p>
</div>

<div class="cluster-box">
<div class="cluster-box-title">I nostri valori</div>
<ul>
<li>Solidariet&agrave;</li>
<li>Agenda ONU 2030</li>
<li>Cultura e formazione</li>
<li>Rappresentanza e rete</li>
</ul>
</div>

</div>

<div class="data-box" style="max-width:720px;margin:0 auto;">
  Questo talk &egrave; esattamente il lavoro di Donne 4.0:<br>
  <strong>tradurre il tech in un linguaggio che includa, non escluda.</strong>
</div>

---
layout: center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Chi parla oggi
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:700px;margin:0 auto;">

  <div class="cluster-box" style="display:flex;gap:1rem;align-items:flex-start;">
    <div class="avatar-sm">
      <img src="https://sessionize.com/image/bbe0-400o400o1-GC45U3jx4Sw9b64DsYA27P.jpg" alt="Chiara" />
    </div>
    <div>
      <div class="cluster-box-title">Tech &amp; Orientamento</div>
      <div style="font-size:0.95rem;font-weight:700;color:#1a1f3a;">Chiara Corrado</div>
      <div style="font-size:0.78rem;color:#666;margin-top:0.2rem;">Introduce il tema e guida la mappa dei ruoli tech</div>
    </div>
  </div>

  <div class="cluster-box" style="display:flex;gap:1rem;align-items:flex-start;">
    <div class="avatar-sm">
      <img src="https://sessionize.com/image/9112-400o400o1-hraEvrgu5KGZL1xUam5LzQ.jpg" alt="Luciana" />
    </div>
    <div>
      <div class="cluster-box-title">Tech &amp; Ruoli</div>
      <div style="font-size:0.95rem;font-weight:700;color:#1a1f3a;">Luciana Bertoncini</div>
      <div style="font-size:0.78rem;color:#666;margin-top:0.2rem;">Approfondisce i cluster e le competenze strutturali</div>
    </div>
  </div>

  <div class="cluster-box" style="display:flex;gap:1rem;align-items:flex-start;">
    <div class="avatar-sm">
      <img src="https://sessionize.com/image/1005-400o400o1-LiWyv11N1uKXiiE87fTsgx.png" alt="Pinelopi" />
    </div>
    <div>
      <div class="cluster-box-title">Ethics &amp; Linguaggio</div>
      <div style="font-size:0.95rem;font-weight:700;color:#1a1f3a;">Pinelopi Troullinou</div>
      <div style="font-size:0.78rem;color:#666;margin-top:0.2rem;">Il linguaggio che esclude e i dati sul gender gap</div>
    </div>
  </div>

  <div class="cluster-box" style="display:flex;gap:1rem;align-items:flex-start;">
    <div class="avatar-sm">
      <img src="https://sessionize.com/image/442b-400o400o1-9XRUwCu9oubMHygXNLLMiH.jpg" alt="Federica" />
    </div>
    <div>
      <div class="cluster-box-title">Gender Equality</div>
      <div style="font-size:0.95rem;font-weight:700;color:#1a1f3a;">Federica Merenda</div>
      <div style="font-size:0.78rem;color:#666;margin-top:0.2rem;">Ethics Expert, cosa possiamo fare meglio</div>
    </div>
  </div>

</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Chiara</div>

<h1 style="font-size:2.8rem;font-weight:900;color:#1a1f3a;margin-bottom:1.5rem;">
  Ma quindi tu cosa fai davvero?
</h1>

<div style="max-width:600px;margin:0 auto;">
  <div style="background:#F8F8F8;border-radius:12px;padding:1.5rem 2rem;font-size:1.15rem;font-style:italic;color:#1a1f3a;border-left:4px solid #E8001C;">
    &ldquo;Ok&hellip; ma quindi questa persona cosa fa?&rdquo;
  </div>
</div>

---
layout: default
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.5rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Titoli dal mondo reale
</h2>

<div style="display:grid;grid-template-columns:1.15fr 0.85fr;gap:1.6rem;align-items:start;margin-top:0.8rem;">

<div style="display:flex;flex-direction:column;gap:0.6rem;">
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">TPU Software Tech Lead</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">Silicon Engineer</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">DevOps Coordinator</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">BI Developer</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">UX/UI Designer</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">Research Scientist</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">Ethics Expert</div>
</div>

<div style="padding-left:0.8rem;">
  <div style="font-size:1.3rem;font-weight:800;color:#1a1f3a;margin-bottom:0.8rem;">
    Sembrano lavori diversi.
  </div>
  <div style="font-size:1.8rem;font-weight:900;color:#E8001C;line-height:1.3;">
    Ma spesso&hellip;<br>non lo sono.
  </div>
</div>

</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.2rem;font-weight:600;color:#E8001C;margin-bottom:1rem;">Il problema</h2>

<div class="highlight-line" style="margin-bottom:0.8rem;">
  Non &egrave; che i lavori sono complessi.
</div>

<div class="highlight-line">
  &Egrave; che li <span>raccontiamo male.</span>
</div>

---
layout: center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.5rem;font-weight:800;color:#1a1f3a;margin-bottom:1.5rem;text-align:center;">
  Pattern del mercato
</h2>

<div style="display:flex;flex-direction:column;align-items:center;gap:0.4rem;max-width:480px;margin:0 auto;">
  <div style="background:#E8001C;color:white;font-weight:700;font-size:1rem;padding:0.7rem 2.5rem;border-radius:8px;width:100%;text-align:center;">Software Engineer</div>
  <div style="color:#E8001C;font-size:1.6rem;line-height:1;">&darr;</div>
  <div style="background:#FFD6D6;color:#B8001A;font-weight:700;font-size:1rem;padding:0.7rem 2.5rem;border-radius:8px;width:100%;text-align:center;">Specializzazione</div>
  <div style="color:#E8001C;font-size:1.6rem;line-height:1;">&darr;</div>
  <div style="background:#FFD6D6;color:#B8001A;font-weight:700;font-size:1rem;padding:0.7rem 2.5rem;border-radius:8px;width:100%;text-align:center;">Titoli sempre pi&ugrave; specifici</div>
  <div style="color:#E8001C;font-size:1.6rem;line-height:1;">&darr;</div>
  <div style="background:#1a1f3a;color:white;font-weight:700;font-size:1rem;padding:0.7rem 2.5rem;border-radius:8px;width:100%;text-align:center;">Sempre meno comprensibili</div>
</div>

---
layout: default
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:0.5rem;">Esempio</h2>
<h3 style="font-size:1.1rem;font-weight:700;color:#E8001C;margin-bottom:1.2rem;">TPU Software Tech Lead</h3>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;margin-top:0.8rem;">

<div>
  <div class="cluster-box">
    <div class="cluster-box-title">Sembra</div>
    <ul>
      <li>Qualcosa di iper-specialistico</li>
      <li>Quasi incomprensibile</li>
      <li>Molto lontano da &ldquo;sviluppo software&rdquo;</li>
    </ul>
  </div>

  <div style="margin-top:1.5rem;" class="highlight-line">
    Cambia il contesto.<br>
    <span>Non il mestiere.</span>
  </div>
</div>

<div>
  <div class="cluster-box" style="margin-bottom:1rem;">
    <div class="cluster-box-title">&Egrave; in realt&agrave;</div>
    <ul>
      <li>Sviluppo software</li>
      <li>Progettazione architetturale</li>
      <li>Coordinamento tecnico del team</li>
    </ul>
  </div>

  <div class="data-box" style="font-size:0.82rem;">
    <strong>= Software Engineer + Leadership + dominio specifico</strong><br>
    <span style="font-size:0.75rem;color:#666;">TPU = chip di Google per l&rsquo;intelligenza artificiale</span>
  </div>
</div>

</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.2rem;font-weight:600;color:#E8001C;margin-bottom:1rem;">Hack the Job Title</h2>

<div class="highlight-line" style="font-size:2rem;">
  Tradurre i ruoli<br>
  <span>in ci&ograve; che fanno davvero</span>
</div>

---
layout: center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  La mappa dei ruoli tech
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:0.8rem;max-width:820px;margin:0 auto;">

<div class="cluster-box">
<div class="cluster-box-title">1 &middot; Costruire</div>
<ul><li>Software Engineer</li><li>ML Engineer</li><li>Application Engineer</li></ul>
</div>

<div class="cluster-box">
<div class="cluster-box-title">2 &middot; Capire &amp; sperimentare</div>
<ul><li>Data Scientist</li><li>Research Scientist</li><li>Student Researcher</li></ul>
</div>

<div class="cluster-box">
<div class="cluster-box-title">3 &middot; Far funzionare</div>
<ul><li>DevOps Engineer</li><li>SRE</li><li>Performance Engineer</li></ul>
</div>

<div class="cluster-box">
<div class="cluster-box-title">4 &middot; Proteggere</div>
<ul><li>Security Engineer</li><li>IT Security Specialist</li></ul>
</div>

<div class="cluster-box">
<div class="cluster-box-title">5 &middot; Specializzarsi</div>
<ul><li>Silicon Engineer</li><li>Display Test Engineer</li></ul>
</div>

<div class="cluster-box">
<div class="cluster-box-title">6 &middot; Tradurre</div>
<ul><li>UX/UI Designer</li><li>BI Developer</li><li>Help &amp; Client Service</li></ul>
</div>

</div>

<div style="text-align:center;margin-top:0.8rem;font-size:0.75rem;color:#888;">
  + Cluster 7: Dare direzione e senso
</div>

---
layout: default
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 1 &mdash; Costruire
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;margin-top:0.8rem;">

<div>
  <div class="cluster-box" style="margin-bottom:1.2rem;">
    <div class="cluster-box-title">Ruoli</div>
    <ul><li>Software Engineer</li><li>ML Software Engineer</li><li>Application Engineer</li></ul>
  </div>

  <div class="highlight-line" style="font-size:1.3rem;">
    Cambia il contesto.<br>
    <span>Non il mestiere.</span>
  </div>
</div>

<div>
  <div class="cluster-box">
    <div class="cluster-box-title">Cosa fanno davvero</div>
    <ul>
      <li>Scrivono codice</li>
      <li>Progettano componenti software</li>
      <li>Costruiscono sistemi e applicazioni</li>
      <li>Risolvono problemi tecnici concreti</li>
    </ul>
  </div>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Chiara &rarr; Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 2 &mdash; Capire e sperimentare
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;margin-top:0.8rem;">

<div>
  <div class="cluster-box" style="margin-bottom:1.2rem;">
    <div class="cluster-box-title">Ruoli</div>
    <ul><li>Data Scientist</li><li>Research Scientist</li><li>Student Researcher</li></ul>
  </div>

  <div class="highlight-line" style="font-size:1.3rem;">
    Non sempre codice.<br>
    <span>Ma sempre problem solving.</span>
  </div>
</div>

<div>
  <div class="cluster-box">
    <div class="cluster-box-title">Cosa fanno davvero</div>
    <ul>
      <li>Analizzano dati per trovare pattern</li>
      <li>Costruiscono modelli predittivi</li>
      <li>Testano ipotesi con esperimenti</li>
      <li>Trasformano dati in decisioni</li>
    </ul>
  </div>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 3 &mdash; Far funzionare
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;margin-top:0.8rem;">

<div>
  <div class="cluster-box" style="margin-bottom:1.2rem;">
    <div class="cluster-box-title">Ruoli</div>
    <ul><li>DevOps Coordinator</li><li>System Performance Engineer</li><li>SRE (Site Reliability Engineer)</li></ul>
  </div>

  <div class="highlight-line" style="font-size:1.3rem;">
    Non costruiscono la feature.<br>
    <span>Fanno s&igrave; che funzioni davvero.</span>
  </div>
</div>

<div>
  <div class="cluster-box">
    <div class="cluster-box-title">Cosa fanno davvero</div>
    <ul>
      <li>Gestiscono il &ldquo;mettere online&rdquo; i sistemi</li>
      <li>Monitorano performance e affidabilit&agrave;</li>
      <li>Intervengono quando qualcosa si rompe</li>
      <li>Garantiscono che tutto regga sotto carico</li>
    </ul>
  </div>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 4 &mdash; Proteggere
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;margin-top:0.8rem;">

<div>
  <div class="cluster-box" style="margin-bottom:1.2rem;">
    <div class="cluster-box-title">Ruoli</div>
    <ul><li>Security Engineer</li><li>IT Security Software Engineer</li></ul>
  </div>

  <div class="highlight-line" style="font-size:1.3rem;">
    Il tech viene attaccato ogni giorno.<br>
    <span>Loro costruiscono le difese.</span>
  </div>
</div>

<div>
  <div class="cluster-box">
    <div class="cluster-box-title">Cosa fanno davvero</div>
    <ul>
      <li>Mettono in sicurezza sistemi e dati</li>
      <li>Analizzano vulnerabilit&agrave;</li>
      <li>Prevengono attacchi e incidenti</li>
      <li>Riducono il rischio operativo</li>
    </ul>
  </div>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 5 &mdash; Specializzazioni estreme
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;margin-top:0.8rem;">

<div>
  <div class="cluster-box" style="margin-bottom:1.2rem;">
    <div class="cluster-box-title">Ruoli</div>
    <ul><li>Silicon Engineer</li><li>Display Test Engineer</li></ul>
  </div>

  <div class="highlight-line" style="font-size:1.3rem;">
    Sempre ingegneria.<br>
    <span>Solo pi&ugrave; vicino al silicio.</span>
  </div>
</div>

<div>
  <div class="cluster-box">
    <div class="cluster-box-title">Cosa fanno davvero</div>
    <ul>
      <li>Lavorano vicino all&rsquo;hardware fisico</li>
      <li>Ottimizzano chip, schermi, sensori</li>
      <li>Testano e raffinano sistemi a basso livello</li>
      <li>Richiedono profondit&agrave; tecnica molto alta</li>
    </ul>
  </div>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 6 &mdash; Tradurre per le persone
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;margin-top:0.8rem;">

<div>
  <div class="cluster-box" style="margin-bottom:1.2rem;">
    <div class="cluster-box-title">Ruoli</div>
    <ul><li>UX/UI Designer</li><li>BI Developer</li><li>Help &amp; Client Service</li></ul>
  </div>

  <div class="highlight-line" style="font-size:1.3rem;">
    Il tech da solo non basta.<br>
    <span>Servono persone che traducano.</span>
  </div>
</div>

<div>
  <div class="cluster-box">
    <div class="cluster-box-title">Cosa fanno davvero</div>
    <ul>
      <li>Progettano esperienze usabili</li>
      <li>Trasformano dati in informazioni leggibili</li>
      <li>Collegano il sistema alle persone reali</li>
      <li>Rendono il tech comprensibile</li>
    </ul>
  </div>
</div>

</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.2rem;font-weight:600;color:#E8001C;margin-bottom:1rem;">Insight</h2>

<div class="highlight-line" style="font-size:1.6rem;margin-bottom:0.8rem;">
  Molti di questi lavori sono variazioni<br>dello stesso mestiere:
</div>

<div style="font-size:2.2rem;font-weight:900;color:#E8001C;">
  risolvere problemi complessi
</div>

---
layout: default
---

<div class="speaker-badge">Federica</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 7 &mdash; Dare direzione e senso
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;">

<div>
  <div class="cluster-box" style="margin-bottom:1.2rem;border-color:#E8001C;background:#FFF0F0;">
    <div class="cluster-box-title">Ruoli</div>
    <ul><li>Ethics Expert</li><li>AI Ethics Specialist</li><li>Gender Equality Advisor</li></ul>
  </div>

  <div class="highlight-line" style="font-size:1.1rem;">
    Non costruiscono il sistema.<br>
    <span>Decidono che tipo di sistema<br>stiamo costruendo.</span>
  </div>
</div>

<div>
  <div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;margin-bottom:1rem;">
    <div class="cluster-box-title">Cosa fanno davvero</div>
    <ul>
      <li>Analizzano impatti sociali e culturali</li>
      <li>Identificano bias e rischi nei sistemi</li>
      <li>Guidano decisioni responsabili</li>
      <li>Rendono il tech pi&ugrave; equo e inclusivo</li>
    </ul>
  </div>

  <div class="data-box" style="font-size:0.82rem;">
    &Egrave; il lavoro che fa anche <strong>Donne 4.0</strong>:<br>
    chiedere &ldquo;per chi stiamo costruendo?&rdquo;
  </div>
</div>

</div>

---
layout: center
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Le competenze che fanno davvero la differenza
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:700px;margin:0 auto 1.2rem;">

<div class="cluster-box">
<div class="cluster-box-title">Le chiamano &ldquo;soft skill&rdquo;</div>
<ul>
<li>Comunicazione</li>
<li>Mediazione tra team diversi</li>
<li>Pensiero sistemico</li>
<li>Traduzione tra mondi</li>
</ul>
</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">In realt&agrave; sono</div>
<ul>
<li>Strutturali</li>
<li>Non sostituibili dalle macchine</li>
<li>Richieste in ogni cluster</li>
<li>Spesso gi&agrave; presenti in chi viene da fuori</li>
</ul>
</div>

</div>

<div style="text-align:center;">
  <div class="highlight-line" style="font-size:1.5rem;">
    Non sono &ldquo;soft&rdquo;. <span>Sono strutturali.</span>
  </div>
</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Pinelopi</div>

<h2 style="font-size:1.4rem;font-weight:700;color:#1a1f3a;margin-bottom:0.8rem;">
  Quando il linguaggio esclude
</h2>

<div style="font-size:1.8rem;font-weight:900;color:#E8001C;line-height:1.4;">
  Quando il lavoro diventa<br>incomprensibile
</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Pinelopi</div>

<h2 style="font-size:1.6rem;font-weight:700;color:#1a1f3a;margin-bottom:1rem;">
  Non &egrave; solo una sensazione.
</h2>

<div style="font-size:2rem;font-weight:900;color:#E8001C;">
  &Egrave; un dato.
</div>

---
layout: center
---

<div class="speaker-badge">Pinelopi</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Il filtro invisibile
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:680px;margin:0 auto 1.2rem;">

<div style="background:#F8F8F8;border-radius:12px;padding:1.2rem;text-align:center;">
  <div style="font-size:2.4rem;font-weight:900;color:#E8001C;">~60%</div>
  <div style="font-size:0.82rem;color:#1a1f3a;font-weight:600;margin-top:0.3rem;">Soglia media a cui<br>ci si candida comunque</div>
</div>

<div style="background:#FFF0F0;border-radius:12px;padding:1.2rem;text-align:center;">
  <div style="font-size:2.4rem;font-weight:900;color:#B8001A;">~100%</div>
  <div style="font-size:0.82rem;color:#1a1f3a;font-weight:600;margin-top:0.3rem;">Soglia percepita necessaria<br>da molte candidate</div>
</div>

</div>

<div class="data-box" style="max-width:680px;margin:0 auto;">
  Un pattern documentato da ricerche aziendali e accademiche:<br>
  <strong>le donne tendono ad autocensurarsi prima ancora di candidarsi.</strong><br>
  Non per mancanza di competenze &mdash; ma per come vengono scritti gli annunci.
  <div class="source-note">Fonte: ricerca interna HP citata in S. Sandberg, <em>Lean In</em> (2013); approfondita da T.S. Mohr, <em>Harvard Business Review</em>, agosto 2014</div>
</div>

---
layout: center
---

<div class="speaker-badge">Pinelopi</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Perch&eacute; succede?
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:680px;margin:0 auto 1.2rem;">

<div class="cluster-box">
<div class="cluster-box-title">Il problema nel testo</div>
<ul>
<li>Liste di requisiti gonfiate</li>
<li>Titoli incomprensibili</li>
<li>Linguaggio tecnico non necessario</li>
<li>Anni di esperienza irrealistici</li>
</ul>
</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">L&rsquo;effetto reale</div>
<ul>
<li>Chi si autocandida meno: si ferma</li>
<li>Chi viene da fuori: si sente escluso</li>
<li>Il settore perde talenti</li>
<li>Il divario si allarga</li>
</ul>
</div>

</div>

<div style="text-align:center;font-size:1rem;font-weight:600;color:#1a1f3a;">
  Un annuncio scritto male <strong style="color:#E8001C;">non &egrave; neutro</strong>. Esclude.
</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Federica</div>

<h2 style="font-size:1.2rem;font-weight:600;color:#E8001C;margin-bottom:1rem;">
  Qui entrano in gioco
</h2>

<div class="highlight-line" style="font-size:1.8rem;margin-bottom:0.5rem;">
  Ethics Expert
</div>

<div class="highlight-line" style="font-size:1.8rem;">
  <span>Gender Equality Advisor</span>
</div>

<div style="max-width:500px;margin:1.5rem auto 0;font-size:0.95rem;color:#555;line-height:1.6;">
  Il loro lavoro &egrave; identificare dove il sistema &mdash; incluso il linguaggio &mdash; produce esclusione. E cambiarlo.
</div>

---
layout: center
---

<div class="speaker-badge">Federica</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Cosa possiamo fare meglio
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:700px;margin:0 auto;">

<div class="cluster-box">
<div class="cluster-box-title">Chi scrive un annuncio</div>
<ul>
<li>Descrivere il lavoro, non solo il titolo</li>
<li>Spiegare il problema che si risolve</li>
<li>Separare &ldquo;essenziale&rdquo; da &ldquo;preferibile&rdquo;</li>
<li>Usare esempi concreti</li>
</ul>
</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">Chi legge un annuncio</div>
<ul>
<li>Cercare i pattern, non il titolo</li>
<li>Tradurre in attivit&agrave; reali</li>
<li>Non lasciarsi bloccare dalla lista</li>
<li>Al 60&ndash;70%? Vale la pena candidarsi</li>
</ul>
</div>

</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Tutte</div>

<h2 style="font-size:1.2rem;font-weight:600;color:#E8001C;margin-bottom:1rem;">Guida pratica</h2>

<div class="highlight-line" style="font-size:1.9rem;">
  Come leggere un job posting tech
</div>

<div style="margin-top:1rem;font-size:0.95rem;color:#555;">
  7 passi per decodificare qualsiasi annuncio
</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Passi 1 e 2</div>

<h2 style="font-size:1.3rem;font-weight:800;color:#1a1f3a;margin-bottom:0.8rem;">Passi 1 e 2</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">
<p><strong>1 &mdash; Ignora il titolo (all&rsquo;inizio)</strong></p>
<p>Il titolo pu&ograve; essere creativo, aziendale, non standard.</p>
<p><strong>Non partire da l&igrave;.</strong> Vai diretto alla descrizione delle attivit&agrave;.</p>
</div>

<div class="cluster-box">
<p><strong>2 &mdash; Cerca i verbi, non le tecnologie</strong></p>
<p>I verbi raccontano il lavoro reale:</p>
<p><strong>sviluppare &middot; progettare &middot; analizzare &middot; monitorare &middot; collaborare</strong></p>
<ul>
<li>&ldquo;design and implement&rdquo; &rarr; <span style="color:#E8001C;font-weight:700;">costruire</span></li>
<li>&ldquo;analyze data and build models&rdquo; &rarr; <span style="color:#E8001C;font-weight:700;">analizzare</span></li>
<li>&ldquo;ensure reliability&rdquo; &rarr; <span style="color:#E8001C;font-weight:700;">far funzionare</span></li>
</ul>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Esempio: Passi 1 e 2</div>

<h2 style="font-size:1.1rem;font-weight:800;color:#1a1f3a;margin-bottom:0.3rem;">
  Esempio reale: <span style="color:#E8001C;">TPU Software Tech Lead</span>
</h2>
<div style="font-size:0.72rem;color:#888;margin-bottom:0.8rem;">Applichiamo i passi 1 e 2 &mdash; ignoriamo il titolo, cerchiamo i verbi</div>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;">

<div class="job-post">
<div style="font-size:0.7rem;font-weight:700;color:#888;margin-bottom:0.5rem;text-transform:uppercase;letter-spacing:0.06em;">Responsibilities (estratto)</div>

<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-verb">Lead</span> the software design and development of Google&rsquo;s next-generation TPU systems</div>

<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-verb">Collaborate</span> with hardware engineers to <span class="ann-verb">define</span> software-hardware interfaces</div>

<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-verb">Build</span> and <span class="ann-verb">maintain</span> compilers, runtimes and performance libraries</div>

<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-verb">Mentor</span> and <span class="ann-verb">guide</span> a team of software engineers</div>

<div>&#9658; <span class="ann-verb">Drive</span> technical strategy across cross-functional teams</div>
</div>

<div style="display:flex;flex-direction:column;gap:0.8rem;">

  <div style="background:#F8F8F8;border-radius:8px;padding:0.8rem 1rem;font-size:0.85rem;">
    <div style="font-weight:700;color:#E8001C;font-size:0.72rem;text-transform:uppercase;letter-spacing:0.06em;margin-bottom:0.4rem;">Passo 1 &mdash; Ignora il titolo</div>
    <strong>&ldquo;TPU Software Tech Lead&rdquo;</strong> non ti dice nulla?<br>
    Normale. <strong>Salta il titolo</strong> e vai alla descrizione.<br>
    L&igrave; trovi il lavoro vero.
  </div>

  <div style="background:#F8F8F8;border-radius:8px;padding:0.8rem 1rem;font-size:0.85rem;">
    <div style="font-weight:700;color:#E8001C;font-size:0.72rem;text-transform:uppercase;letter-spacing:0.06em;margin-bottom:0.4rem;">Passo 2 &mdash; Cerca i verbi</div>
    <span style="background:#E8001C;color:white;border-radius:3px;padding:1px 6px;font-size:0.75rem;margin-right:4px;">lead</span>
    <span style="background:#E8001C;color:white;border-radius:3px;padding:1px 6px;font-size:0.75rem;margin-right:4px;">build</span>
    <span style="background:#E8001C;color:white;border-radius:3px;padding:1px 6px;font-size:0.75rem;margin-right:4px;">collaborate</span>
    <span style="background:#E8001C;color:white;border-radius:3px;padding:1px 6px;font-size:0.75rem;margin-right:4px;">mentor</span>
    <span style="background:#E8001C;color:white;border-radius:3px;padding:1px 6px;font-size:0.75rem;">drive</span>
    <div style="margin-top:0.5rem;font-size:0.82rem;color:#555;">
      = <strong>costruire</strong> + <strong>coordinare</strong> + <strong>guidare</strong>
    </div>
  </div>

  <div class="data-box" style="font-size:0.82rem;padding:0.7rem 0.9rem;">
    Gi&agrave; solo con 2 passi sai che questa persona <strong>scrive software e guida un team</strong>.
  </div>

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Passi 3 e 4</div>

<h2 style="font-size:1.3rem;font-weight:800;color:#1a1f3a;margin-bottom:0.8rem;">Passi 3 e 4</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">
<p><strong>3 &mdash; In quale cluster rientra?</strong></p>
<ul>
<li>scrive codice? &rarr; <span style="color:#E8001C;font-weight:700;">costruire</span></li>
<li>lavora sui dati? &rarr; <span style="color:#E8001C;font-weight:700;">analizzare</span></li>
<li>gestisce sistemi? &rarr; <span style="color:#E8001C;font-weight:700;">far funzionare</span></li>
<li>lavora sulla sicurezza? &rarr; <span style="color:#E8001C;font-weight:700;">proteggere</span></li>
<li>lavora con utenti o business? &rarr; <span style="color:#E8001C;font-weight:700;">tradurre</span></li>
</ul>
</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<p><strong>4 &mdash; Non farti bloccare dalla lista</strong></p>
<p>Quelle liste lunghe di requisiti? <strong>Sono wishlist.</strong></p>
<p>Nessuno le soddisfa al 100%. Neanche chi viene assunto.</p>
<p>Al 60&ndash;70% dei requisiti rilevanti?</p>
<p><strong>&rarr; Vale la pena candidarsi.</strong></p>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Esempio: Passi 3 e 4</div>

<h2 style="font-size:1.1rem;font-weight:800;color:#1a1f3a;margin-bottom:0.3rem;">
  Esempio reale: <span style="color:#E8001C;">TPU Software Tech Lead</span>
</h2>
<div style="font-size:0.72rem;color:#888;margin-bottom:0.8rem;">Applichiamo i passi 3 e 4 &mdash; identifichiamo il cluster e filtriamo la wishlist</div>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;">

<div class="job-post">
<div style="font-size:0.7rem;font-weight:700;color:#888;margin-bottom:0.5rem;text-transform:uppercase;letter-spacing:0.06em;">Requirements (estratto)</div>

<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-wishlist">8+ years of experience in systems software</span></div>
<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-wishlist">PhD or Master&rsquo;s in CS or related field</span></div>
<div style="margin-bottom:0.4rem;">&#9658; Proficiency in C++ or Python</div>
<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-wishlist">Experience with ML frameworks (TensorFlow, JAX)</span></div>

<div style="margin-top:1rem;font-size:0.7rem;font-weight:700;color:#888;margin-bottom:0.5rem;text-transform:uppercase;letter-spacing:0.06em;">Dalle Responsibilities</div>

<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-cluster">Build</span> and maintain compilers, runtimes</div>
<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-cluster">Lead</span> software design and development</div>
<div>&#9658; <span class="ann-cluster">Drive</span> technical strategy</div>
</div>

<div style="display:flex;flex-direction:column;gap:0.8rem;">

  <div style="background:#F8F8F8;border-radius:8px;padding:0.8rem 1rem;font-size:0.85rem;">
    <div style="font-weight:700;color:#E8001C;font-size:0.72rem;text-transform:uppercase;letter-spacing:0.06em;margin-bottom:0.4rem;">Passo 3 &mdash; Quale cluster?</div>
    <span style="background:#1a1f3a;color:white;border-radius:3px;padding:2px 8px;font-size:0.78rem;">build</span> +
    <span style="background:#1a1f3a;color:white;border-radius:3px;padding:2px 8px;font-size:0.78rem;">lead</span> +
    <span style="background:#1a1f3a;color:white;border-radius:3px;padding:2px 8px;font-size:0.78rem;">drive</span>
    <div style="margin-top:0.5rem;font-size:0.85rem;">
      Scrive codice? <strong>S&igrave;.</strong><br>
      Gestisce sistemi? <strong>S&igrave;.</strong><br>
      &rarr; <strong style="color:#E8001C;">Cluster 1: Costruire</strong> + leadership
    </div>
  </div>

  <div style="background:#F0F0F0;border-radius:8px;padding:0.8rem 1rem;font-size:0.85rem;">
    <div style="font-weight:700;color:#888;font-size:0.72rem;text-transform:uppercase;letter-spacing:0.06em;margin-bottom:0.4rem;">Passo 4 &mdash; La wishlist</div>
    <div style="text-decoration:line-through;color:#999;margin-bottom:0.3rem;">8+ anni di esperienza</div>
    <div style="text-decoration:line-through;color:#999;margin-bottom:0.3rem;">PhD o Master&rsquo;s</div>
    <div style="text-decoration:line-through;color:#999;margin-bottom:0.3rem;">TensorFlow, JAX</div>
    <div style="margin-top:0.5rem;font-size:0.82rem;color:#555;">
      Nessuno li ha tutti. <strong>Neanche chi viene assunto.</strong>
    </div>
  </div>

  <div class="data-box" style="font-size:0.82rem;padding:0.7rem 0.9rem;">
    Sai C++ o Python e ti piace costruire sistemi?<br>
    <strong>Hai le basi. Il resto si impara.</strong>
  </div>

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Passi 5 e 6</div>

<h2 style="font-size:1.3rem;font-weight:800;color:#1a1f3a;margin-bottom:0.8rem;">Passi 5 e 6</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">
<p><strong>5 &mdash; Individua le competenze trasversali</strong></p>
<p>Cerca nella descrizione:</p>
<p><strong>communication &middot; collaboration &middot; stakeholder management &middot; problem solving</strong></p>
<p>Questi segnali spesso contano <strong>pi&ugrave; delle tecnologie</strong>.</p>
</div>

<div class="cluster-box">
<p><strong>6 &mdash; Traduci in una frase</strong></p>
<p>Prova a completare:</p>
<p><em>&ldquo;Questa persona serve per&hellip;&rdquo;</em></p>
<ul>
<li>&ldquo;costruire sistemi backend scalabili&rdquo;</li>
<li>&ldquo;analizzare dati per supportare decisioni&rdquo;</li>
<li>&ldquo;rendere il prodotto usabile dagli utenti&rdquo;</li>
</ul>
<p>Se riesci a farlo, <strong>hai capito il ruolo</strong>.</p>
</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Esempio: Passi 5 e 6</div>

<h2 style="font-size:1.1rem;font-weight:800;color:#1a1f3a;margin-bottom:0.3rem;">
  Esempio reale: <span style="color:#E8001C;">TPU Software Tech Lead</span>
</h2>
<div style="font-size:0.72rem;color:#888;margin-bottom:0.8rem;">Applichiamo i passi 5 e 6 &mdash; le soft skill strutturali e la traduzione finale</div>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;align-items:start;">

<div class="job-post">
<div style="font-size:0.7rem;font-weight:700;color:#888;margin-bottom:0.5rem;text-transform:uppercase;letter-spacing:0.06em;">Dal posting originale</div>

<div style="margin-bottom:0.4rem;">&#9658; Collaborate with hardware engineers to define software-hardware interfaces</div>

<div style="margin-bottom:0.4rem;">&#9658; Mentor and guide a team of software engineers</div>

<div style="margin-bottom:0.4rem;">&#9658; Drive technical strategy across cross-functional teams</div>

<div style="margin-top:1rem;font-size:0.7rem;font-weight:700;color:#888;margin-bottom:0.5rem;text-transform:uppercase;letter-spacing:0.06em;">Requirements</div>

<div style="margin-bottom:0.4rem;">&#9658; <span class="ann-soft">Strong communication and leadership skills</span></div>

<div>&#9658; <span class="ann-soft">Ability to work across teams and manage stakeholders</span></div>
</div>

<div style="display:flex;flex-direction:column;gap:0.8rem;">

  <div style="background:#FFF0F0;border-radius:8px;padding:0.8rem 1rem;font-size:0.85rem;border:1px solid #FFD6D6;">
    <div style="font-weight:700;color:#E8001C;font-size:0.72rem;text-transform:uppercase;letter-spacing:0.06em;margin-bottom:0.4rem;">Passo 5 &mdash; Soft skill strutturali</div>
    <span style="background:#FFD6D6;color:#B8001A;border-radius:3px;padding:2px 8px;font-size:0.78rem;margin-right:4px;">communication</span>
    <span style="background:#FFD6D6;color:#B8001A;border-radius:3px;padding:2px 8px;font-size:0.78rem;margin-right:4px;">leadership</span>
    <span style="background:#FFD6D6;color:#B8001A;border-radius:3px;padding:2px 8px;font-size:0.78rem;">stakeholder mgmt</span>
    <div style="margin-top:0.5rem;font-size:0.82rem;color:#555;">
      Compaiono <strong>due volte</strong> nel posting.<br>
      Nelle responsibilities <em>e</em> nei requirements.<br>
      <strong>Contano pi&ugrave; di TensorFlow.</strong>
    </div>
  </div>

  <div style="background:#F8F8F8;border-radius:8px;padding:0.8rem 1rem;font-size:0.85rem;">
    <div style="font-weight:700;color:#E8001C;font-size:0.72rem;text-transform:uppercase;letter-spacing:0.06em;margin-bottom:0.4rem;">Passo 6 &mdash; Traduci in una frase</div>
    <div style="font-size:1.05rem;font-weight:700;color:#1a1f3a;line-height:1.5;font-style:italic;">
      &ldquo;Questa persona serve per costruire sistemi software di basso livello e guidare un team tecnico.&rdquo;
    </div>
  </div>

  <div class="data-box" style="font-size:0.82rem;padding:0.7rem 0.9rem;">
    <strong>= Cluster 1 (costruire) + leadership</strong><br>
    <span style="font-size:0.75rem;color:#888;font-style:italic;">Il &ldquo;TPU&rdquo; &egrave; solo il dominio. Il mestiere &egrave; chiaro.</span>
  </div>

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Passo 7</div>

<h2 style="font-size:1.3rem;font-weight:800;color:#1a1f3a;margin-bottom:0.8rem;">Passo 7 + Guida completa</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin-top:0.8rem;">

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<p><strong>7 &mdash; Fatti la domanda giusta</strong></p>
<p>Non: <em>&ldquo;Conosco tutte queste tecnologie?&rdquo;</em></p>
<p>Ma: <strong>&ldquo;Mi piace fare questo tipo di lavoro?&rdquo;</strong></p>
<p>Le tecnologie si imparano.</p>
<p>La motivazione no.</p>
</div>

<div style="display:flex;flex-direction:column;align-items:center;justify-content:center;gap:1rem;">

<div class="data-box" style="text-align:center;width:100%;">
  Vuoi la guida completa<br>con esempi e job posting annotati?
</div>

<div style="width:150px;height:150px;background:#F8F8F8;border:2px solid #E8001C;border-radius:12px;overflow:hidden;display:flex;align-items:center;justify-content:center;">
    <img src="https://github.com/kiaruzza/hack-the-job-title/blob/develop/public/qr-code.png?raw=true" class="h-35" />
</div>

<div style="font-size:0.75rem;color:#888;text-align:center;">
  donne4.it/hack-job-title
</div>

</div>

</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Chiara &mdash; chiusura</div>

<h2 style="font-size:1.2rem;font-weight:600;color:#E8001C;margin-bottom:1rem;">Hack the Job Title</h2>

<div style="font-size:1.5rem;font-weight:800;color:#1a1f3a;margin-bottom:0.5rem;">
  Dietro molti titoli del tech
</div>
<div style="font-size:1.6rem;font-weight:900;color:#1a1f3a;margin-bottom:1.2rem;">
  non ci sono mestieri alieni.
</div>

<div style="font-size:1.1rem;font-weight:600;color:#E8001C;line-height:1.9;">
  Ci sono persone che costruiscono, capiscono,<br>
  proteggono, traducono, fanno funzionare.
</div>

---
layout: center
class: text-center
---

<div style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:0.4rem;">
  Se non capisci un job title,
</div>
<div style="font-size:1.1rem;color:#555;margin-bottom:1.5rem;">
  non significa che non sei abbastanza.
</div>
<div style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:0.4rem;">
  Significa che quel lavoro
</div>
<div style="font-size:1.9rem;font-weight:900;color:#E8001C;">
  non &egrave; ancora stato tradotto<br>nel modo giusto.
</div>

---
layout: center
---

<div style="position:absolute;inset:0;background:linear-gradient(to right, rgba(232,0,28,0.88) 0%, rgba(232,0,28,0.65) 55%, rgba(0,0,0,0.25) 100%);"></div>

<div style="position:relative;z-index:10;display:flex;flex-direction:column;justify-content:center;height:100%;padding:0 3rem;">

<h1 style="font-size:2.8rem;font-weight:900;color:white;line-height:1.1;margin-bottom:0.5rem;text-shadow:0 2px 8px rgba(0,0,0,0.3);">
  Grazie &#10084;&#65039;
</h1>

<h2 style="font-size:1.1rem;font-weight:600;color:rgba(255,255,255,0.9);margin-bottom:1.5rem;">
    <div class="flex items-center justify-center gap-4">
        <img src="https://devfest.gdgpisa.it/_astro/logo_wtm_quadrato_2026.pWtoT8-u.png" class="h-10" />
          Hack the Job Title &mdash; Donne 4.0 &times; WTM Pisa
        <img src="https://donne4.it/wp-content/uploads/2021/08/Logo-donne4-rit-100px.png" class="h-10" />
    </div>
</h2>

<div style="display:flex;gap:1.5rem;flex-wrap:wrap;margin-bottom:1.8rem;align-items:flex-start;">

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.4rem;">
    <div class="avatar" style="width:52px;height:52px;border-width:2px;">
      <img src="https://sessionize.com/image/bbe0-400o400o1-GC45U3jx4Sw9b64DsYA27P.jpg" alt="Chiara" />
    </div>
    <div style="font-weight:700;color:white;font-size:0.78rem;text-align:center;">Chiara Corrado</div>
  </div>

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.4rem;">
    <div class="avatar" style="width:52px;height:52px;border-width:2px;">
      <img src="https://sessionize.com/image/9112-400o400o1-hraEvrgu5KGZL1xUam5LzQ.jpg" alt="Luciana" />
    </div>
    <div style="font-weight:700;color:white;font-size:0.78rem;text-align:center;">Luciana Bertoncini</div>
  </div>

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.4rem;">
    <div class="avatar" style="width:52px;height:52px;border-width:2px;">
      <img src="https://sessionize.com/image/1005-400o400o1-LiWyv11N1uKXiiE87fTsgx.png" alt="Pinelopi" />
    </div>
    <div style="font-weight:700;color:white;font-size:0.78rem;text-align:center;">Pinelopi Troullinou</div>
  </div>

  <div style="display:flex;flex-direction:column;align-items:center;gap:0.4rem;">
    <div class="avatar" style="width:52px;height:52px;border-width:2px;">
      <img src="https://sessionize.com/image/442b-400o400o1-9XRUwCu9oubMHygXNLLMiH.jpg" alt="Federica" />
    </div>
    <div style="font-weight:700;color:white;font-size:0.78rem;text-align:center;">Federica Merenda</div>
  </div>

</div>

<div style="display:flex;align-items:center;gap:1.5rem;">

  <div style="width:100px;height:100px;background:rgba(255,255,255,0.95);border-radius:10px;overflow:hidden;display:flex;align-items:center;justify-content:center;padding:4px;">
    <img src="https://github.com/kiaruzza/hack-the-job-title/blob/develop/public/qr-code.png?raw=true" class="h-20" />
  </div>

  <div style="text-align:left;">
    <div style="font-size:0.88rem;font-weight:700;color:white;margin-bottom:0.2rem;">donne4.it/hack-job-title</div>
    <div style="font-size:0.75rem;color:rgba(255,255,255,0.75);">Guida pratica &middot; Risorse &middot; Contatti</div>
  </div>

  <div style="text-align:left;">
    <div style="width:100px;height:100px;background:rgba(255,255,255,0.95);border-radius:10px;overflow:hidden;display:flex;align-items:center;justify-content:center;padding:4px;">
    <img src="https://github.com/kiaruzza/hack-the-job-title/blob/develop/public/feedback-qr-code.png?raw=true" class="h-20" />
    </div>
  </div>


  <div style="text-align:left;">
    <div style="font-size:0.88rem;font-weight:700;color:white;margin-bottom:0.2rem;">Feedback</div>
  </div>

</div>
</div>
