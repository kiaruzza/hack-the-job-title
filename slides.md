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
  sans: 'Inter'
  serif: 'Inter'
  mono: 'Fira Code'
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
</style>

---
layout: cover
background: https://donne4.it/wp-content/uploads/2025/10/C52A12D2-65AE-4353-B2E9-1C68C0E75E9B.jpg?id=19999
---

<div style="position:absolute;inset:0;background:linear-gradient(to right, rgba(232,0,28,0.88) 0%, rgba(232,0,28,0.65) 55%, rgba(0,0,0,0.25) 100%);"></div>

<div style="position:relative;z-index:10;display:flex;flex-direction:column;justify-content:center;height:100%;padding:0 3rem;">

<div style="margin-bottom:0.6rem;">
  <span style="font-size:0.75rem;font-weight:700;letter-spacing:0.2em;text-transform:uppercase;color:rgba(255,255,255,0.8);">Talk &middot; Career &middot; Tech Culture</span>
</div>

<h1 style="font-size:3rem;font-weight:900;color:white;line-height:1.1;margin-bottom:0.8rem;text-shadow:0 2px 8px rgba(0,0,0,0.3);">
<div class="flex items-center justify-center gap-4">
    <img src="https://devfest.gdgpisa.it/_astro/logo_wtm_quadrato_2026.pWtoT8-u.png" class="h-10" />
    Hack the Job Title
    <img src="https://donne4.it/wp-content/uploads/2021/08/Logo-donne4-rit-100px.png" class="h-10" />

</div>
</h1>

<p style="font-size:1.3rem;font-weight:600;color:rgba(255,255,255,0.92);margin-bottom:2rem;">
  Il lavoro reale dietro i titoli del tech
</p>

<div style="display:flex;gap:2rem;flex-wrap:wrap;margin-bottom:2rem;align-items:flex-start;">

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

<div style="font-size:0.82rem;color:rgba(255,255,255,0.75);font-weight:600;">
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

Rendere **protagoniste le donne** nell'affrontare le sfide globali e costruire con le tecnologie un futuro **inclusivo e
sostenibile**.

</div>

<div class="cluster-box">
<div class="cluster-box-title">I nostri valori</div>

- Solidarietà
- Agenda ONU 2030
- Cultura e formazione
- Rappresentanza e rete

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
layout: two-cols
class: items-center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.5rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Titoli dal mondo reale
</h2>

<div style="display:flex;flex-direction:column;gap:0.6rem;">
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">TPU Software Tech Lead</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">Silicon Engineer</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">DevOps Coordinator</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">BI Developer</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">UX/UI Designer</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">Research Scientist</div>
  <div style="background:#F8F8F8;border-radius:8px;padding:0.65rem 1rem;font-weight:600;color:#1a1f3a;font-size:0.92rem;border-left:3px solid #E8001C;">Ethics Expert</div>
</div>

::right::

<div style="padding-left:2rem;">
  <div style="font-size:1.3rem;font-weight:800;color:#1a1f3a;margin-bottom:0.8rem;">
    Sembrano lavori diversi.
  </div>
  <div style="font-size:1.8rem;font-weight:900;color:#E8001C;line-height:1.3;">
    Ma spesso&hellip;<br>non lo sono.
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
layout: two-cols
class: items-center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:0.5rem;">Esempio</h2>
<h3 style="font-size:1.1rem;font-weight:700;color:#E8001C;margin-bottom:1.2rem;">TPU Software Tech Lead</h3>

<div class="cluster-box">
<div class="cluster-box-title">Sembra</div>

- Qualcosa di iper-specialistico
- Quasi incomprensibile
- Molto lontano da "sviluppo software"

</div>

<div style="margin-top:1.5rem;" class="highlight-line">
  Cambia il contesto.<br>
  <span>Non il mestiere.</span>
</div>

::right::

<div style="padding-left:1.5rem;">

<div class="cluster-box" style="margin-bottom:1rem;">
<div class="cluster-box-title">&Egrave;</div>

- Sviluppo software
- Progettazione architetturale
- Coordinamento tecnico del team

</div>

<div class="data-box" style="font-size:0.82rem;">
  <strong>= Software Engineer + Leadership + dominio specifico</strong><br>
  <span style="font-size:0.75rem;color:#666;">TPU = chip di Google per l'intelligenza artificiale</span>
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

- Software Engineer
- ML Engineer
- Application Engineer

</div>

<div class="cluster-box">
<div class="cluster-box-title">2 &middot; Capire &amp; sperimentare</div>

- Data Scientist
- Research Scientist
- Student Researcher

</div>

<div class="cluster-box">
<div class="cluster-box-title">3 &middot; Far funzionare</div>

- DevOps Engineer
- SRE
- Performance Engineer

</div>

<div class="cluster-box">
<div class="cluster-box-title">4 &middot; Proteggere</div>

- Security Engineer
- IT Security Specialist

</div>

<div class="cluster-box">
<div class="cluster-box-title">5 &middot; Tradurre</div>

- UX/UI Designer
- BI Developer
- Help Client Service

</div>

<div class="cluster-box">
<div class="cluster-box-title">6 &middot; Specializzarsi</div>

- Silicon Engineer
- Display Test Engineer

</div>

</div>

<div style="text-align:center;margin-top:0.8rem;font-size:0.75rem;color:#888;">
  + Cluster 7: Dare direzione e senso &rarr; slide successiva
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 1 &mdash; Costruire
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">
<div class="cluster-box-title">Ruoli</div>

- Software Engineer
- ML Software Engineer
- Application Engineer

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Cambia il contesto.<br>
  <span>Non il mestiere.</span>
</div>

::right::

<div style="padding-left:1.5rem;">
<div class="cluster-box">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Scrivono codice
- Progettano componenti software
- Costruiscono sistemi e applicazioni
- Risolvono problemi tecnici concreti

</div>
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Chiara &rarr; Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 2 &mdash; Capire e sperimentare
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">
<div class="cluster-box-title">Ruoli</div>

- Data Scientist
- Research Scientist
- Student Researcher

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Non sempre codice.<br>
  <span>Ma sempre problem solving.</span>
</div>

::right::

<div style="padding-left:1.5rem;">
<div class="cluster-box">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Analizzano dati per trovare pattern
- Costruiscono modelli predittivi
- Testano ipotesi con esperimenti
- Trasformano dati in decisioni

</div>
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 3 &mdash; Far funzionare
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">
<div class="cluster-box-title">Ruoli</div>

- DevOps Coordinator
- System Performance Engineer
- SRE (Site Reliability Engineer)

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Non costruiscono la feature.<br>
  <span>Fanno s&igrave; che funzioni davvero.</span>
</div>

::right::

<div style="padding-left:1.5rem;">
<div class="cluster-box">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Gestiscono il "mettere online" i sistemi
- Monitorano performance e affidabilit&agrave;
- Intervengono quando qualcosa si rompe
- Garantiscono che tutto regga sotto carico

</div>
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 4 &mdash; Proteggere
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">
<div class="cluster-box-title">Ruoli</div>

- Security Engineer
- IT Security Software Engineer

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Il tech viene attaccato ogni giorno.<br>
  <span>Loro costruiscono le difese.</span>
</div>

::right::

<div style="padding-left:1.5rem;">
<div class="cluster-box">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Mettono in sicurezza sistemi e dati
- Analizzano vulnerabilit&agrave;
- Prevengono attacchi e incidenti
- Riducono il rischio operativo

</div>
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 5 &mdash; Tradurre per le persone
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">
<div class="cluster-box-title">Ruoli</div>

- UX/UI Designer
    - BI Developer
    - Help &amp; Client Service

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Il tech da solo non basta.<br>
  <span>Servono persone che traducano.</span>
</div>

::right::

<div style="padding-left:1.5rem;">
<div class="cluster-box">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Progettano esperienze usabili
- Trasformano dati in informazioni leggibili
- Collegano il sistema alle persone reali
- Rendono il tech comprensibile

</div>
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 6 &mdash; Specializzazioni estreme
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">
<div class="cluster-box-title">Ruoli</div>

- Silicon Engineer
    - Display Test Engineer

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Sempre ingegneria.<br>
  <span>Solo pi&ugrave; vicino al silicio.</span>
</div>

::right::

<div style="padding-left:1.5rem;">
<div class="cluster-box">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Lavorano vicino all'hardware fisico
- Ottimizzano chip, schermi, sensori
- Testano e raffinano sistemi a basso livello
- Richiedono profondit&agrave; tecnica molto alta

</div>
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Federica</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 7 &mdash; Dare direzione e senso
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">Ruoli</div>

- Ethics Expert
- AI Ethics Specialist
- Gender / Equality Advisor

</div>

<div class="highlight-line" style="font-size:1.1rem;">
  Non costruiscono il sistema.<br>
  <span>Decidono che tipo di sistema<br>stiamo costruendo.</span>
</div>

::right::

<div style="padding-left:1.5rem;">

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;margin-bottom:1rem;">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Analizzano impatti sociali e culturali
- Identificano bias e rischi nei sistemi
- Guidano decisioni responsabili
- Rendono il tech pi&ugrave; equo e inclusivo

</div>

<div class="data-box" style="font-size:0.82rem;">
  &Egrave; il lavoro che fa anche <strong>Donne 4.0</strong>:<br>
  chiedere &ldquo;per chi stiamo costruendo?&rdquo;
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
layout: center
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Le competenze che fanno davvero la differenza
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:700px;margin:0 auto 1.2rem;">

<div class="cluster-box">
<div class="cluster-box-title">Le chiamano &ldquo;soft skill&rdquo;</div>

- Comunicazione
- Mediazione tra team diversi
- Pensiero sistemico
- Traduzione tra mondi

</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">In realt&agrave; sono</div>

- Strutturali
- Non sostituibili dalle macchine
- Richieste in ogni cluster
- Spesso gi&agrave; presenti in chi viene da fuori

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

- Liste di requisiti gonfiate
- Titoli incomprensibili
- Linguaggio tecnico non necessario
- Anni di esperienza irrealistici

</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">L'effetto reale</div>

- Chi si autocandida meno: si ferma
- Chi viene da fuori: si sente escluso
- Il settore perde talenti
- Il divario si allarga

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
  <span>Gender / Equality Advisor</span>
</div>

<div style="max-width:500px;margin:1.5rem auto 0;font-size:0.95rem;color:#555;line-height:1.6;">
  Il loro lavoro &egrave; identificare dove il sistema &mdash; incluso il linguaggio &mdash; produce esclusione. E cambiarlo.
</div>

---
layout: two-cols
class: items-center
---

<div class="speaker-badge">Federica</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 7 &mdash; Dare direzione e senso
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">Ruoli</div>

- Ethics Expert
    - AI Ethics Specialist
    - Gender / Equality Advisor

</div>

<div class="highlight-line" style="font-size:1.1rem;">
  Non costruiscono il sistema.<br>
  <span>Decidono che tipo di sistema<br>stiamo costruendo.</span>
</div>

::right::

<div style="padding-left:1.5rem;">

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;margin-bottom:1rem;">
<div class="cluster-box-title">Cosa fanno davvero</div>

- Analizzano impatti sociali e culturali
- Identificano bias e rischi nei sistemi
- Guidano decisioni responsabili
- Rendono il tech pi&ugrave; equo e inclusivo

</div>

<div class="data-box" style="font-size:0.82rem;">
  &Egrave; il lavoro che fa anche <strong>Donne 4.0</strong>:<br>
  chiedere &ldquo;per chi stiamo costruendo?&rdquo;
</div>

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

- Descrivere il lavoro, non solo il titolo
- Spiegare il problema che si risolve
- Separare &ldquo;essenziale&rdquo; da &ldquo;preferibile&rdquo;
- Usare esempi concreti

</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">
<div class="cluster-box-title">Chi legge un annuncio</div>

- Cercare i pattern, non il titolo
- Tradurre in attivit&agrave; reali
- Non lasciarsi bloccare dalla lista
- Al 60&ndash;70%? Vale la pena candidarsi

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

<div class="speaker-badge">Tutte &mdash; Guida pratica 1/4</div>

## Passi 1 e 2

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">

**1 &mdash; Ignora il titolo (all'inizio)**

Il titolo pu&ograve; essere creativo, aziendale, non standard.

**Non partire da l&igrave;.** Vai diretto alla descrizione delle attivit&agrave;.

</div>

<div class="cluster-box">

**2 &mdash; Cerca i verbi, non le tecnologie**

I verbi raccontano il lavoro reale:

**sviluppare &middot; progettare &middot; analizzare &middot; monitorare &middot; collaborare**

- "design and implement" &rarr; <span style="color:#E8001C;font-weight:700;">costruire</span>
    - "analyze data and build models" &rarr; <span style="color:#E8001C;font-weight:700;">analizzare</span>
    - "ensure reliability" &rarr; <span style="color:#E8001C;font-weight:700;">far funzionare</span>

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Guida pratica 2/4</div>

## Passi 3 e 4

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">

**3 &mdash; In quale cluster rientra?**

- scrive codice? &rarr; <span style="color:#E8001C;font-weight:700;">costruire</span>
- lavora sui dati? &rarr; <span style="color:#E8001C;font-weight:700;">analizzare</span>
- gestisce sistemi? &rarr; <span style="color:#E8001C;font-weight:700;">far funzionare</span>
- lavora sulla sicurezza? &rarr; <span style="color:#E8001C;font-weight:700;">proteggere</span>
- lavora con utenti o business? &rarr; <span style="color:#E8001C;font-weight:700;">tradurre</span>

</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">

**4 &mdash; Non farti bloccare dalla lista**

Quelle liste lunghe di requisiti? **Sono wishlist.**

Nessuno le soddisfa al 100%. Neanche chi viene assunto.

Al 60&ndash;70% dei requisiti rilevanti?

**&rarr; Vale la pena candidarsi.**

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Guida pratica 3/4</div>

## Passi 5 e 6

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">

**5 &mdash; Individua le competenze trasversali**

Cerca nella descrizione:

**communication &middot; collaboration &middot; stakeholder management &middot; problem solving**

Questi segnali spesso contano **pi&ugrave; delle tecnologie**.

</div>

<div class="cluster-box">

**6 &mdash; Traduci in una frase**

Prova a completare:

*"Questa persona serve per&hellip;"*

- "costruire sistemi backend scalabili"
- "analizzare dati per supportare decisioni"
- "rendere il prodotto usabile dagli utenti"

Se riesci a farlo, **hai capito il ruolo**.

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte &mdash; Guida pratica 4/4</div>

## Passo 7 + Guida completa

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin-top:0.8rem;">

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">

**7 &mdash; Fatti la domanda giusta**

Non: *"Conosco tutte queste tecnologie?"*

Ma: **"Mi piace fare questo tipo di lavoro?"**

Le tecnologie si imparano.

La motivazione no.

</div>

<div style="display:flex;flex-direction:column;align-items:center;justify-content:center;gap:1rem;">

<div class="data-box" style="text-align:center;width:100%;">
  Vuoi la guida completa<br>con esempi e job posting annotati?
</div>

<div style="width:150px;height:150px;background:#F8F8F8;border:2px solid #E8001C;border-radius:12px;overflow:hidden;display:flex;align-items:center;justify-content:center;">
  <img src="https://cdn.qr-code-generator.com/qrcode-preview?background_color=%23FFFFFF&foreground_color=%23cf2e2e&marker_left_inner_color=%23cf2e2e&marker_left_outer_color=%23cf2e2e&marker_right_inner_color=%23cf2e2e&marker_right_outer_color=%23cf2e2e&marker_bottom_inner_color=%23cf2e2e&marker_bottom_outer_color=%23cf2e2e&marker_left_template=version4&marker_right_template=version4&marker_bottom_template=version4&qr_code_pattern=rounded-2&qr_code_logo=_logotemplates%2Fen%2Fall%2Ficon-generator-scan-me-2.svg&qr_code_text=https%3A%2F%2Fqrco.de%2Fcc_hack_the_job_title&frame_name=no-frame&frame_color=%23000000&frame_text=Scan%20Me&frame_text_color=&image_format=PNG&image_width=500&Expires=1776039453&Signature=M6axIvrLMelp59R50vl8KV2rqR34ULR~B1j36cwQrIyJTEtkUg3DhTAIg6KqiNyKCv7zHGy9c1hGV8mAANb1C08B5apSFc8dgrmhtOd2svP57SoU-3I9E-gDV9LmWYi2hWHxh3F8vazgoyawLGG92vwoYVInztPAhe0ljPJ2apr02ujePA1HuBiky9~0Rws774ZIAwseDXIMXV2V8vh3kHYz3L2WFEWWZbVAmbJYPtBhTzqd5tYq~BunZvg9Kw8KubbBUOBgS~CCea---Ieaiyal2Y0twdWwnuBBnJl74UOyJOOuZ8hV5UERmIZNGEd7OxXkz5S2~eQvRBquyRZ2~Q__&Key-Pair-Id=KKMPOJU8AYATR" alt="QR code guida pratica" style="width:140px;height:140px;object-fit:contain;" />
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
layout: cover
background: https://donne4.it/wp-content/uploads/2025/10/C52A12D2-65AE-4353-B2E9-1C68C0E75E9B.jpg?id=19999
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
    <img src="https://cdn.qr-code-generator.com/qrcode-preview?background_color=%23FFFFFF&foreground_color=%23cf2e2e&marker_left_inner_color=%23cf2e2e&marker_left_outer_color=%23cf2e2e&marker_right_inner_color=%23cf2e2e&marker_right_outer_color=%23cf2e2e&marker_bottom_inner_color=%23cf2e2e&marker_bottom_outer_color=%23cf2e2e&marker_left_template=version4&marker_right_template=version4&marker_bottom_template=version4&qr_code_pattern=rounded-2&qr_code_logo=_logotemplates%2Fen%2Fall%2Ficon-generator-scan-me-2.svg&qr_code_text=https%3A%2F%2Fqrco.de%2Fcc_hack_the_job_title&frame_name=no-frame&frame_color=%23000000&frame_text=Scan%20Me&frame_text_color=&image_format=PNG&image_width=500&Expires=1776039453&Signature=M6axIvrLMelp59R50vl8KV2rqR34ULR~B1j36cwQrIyJTEtkUg3DhTAIg6KqiNyKCv7zHGy9c1hGV8mAANb1C08B5apSFc8dgrmhtOd2svP57SoU-3I9E-gDV9LmWYi2hWHxh3F8vazgoyawLGG92vwoYVInztPAhe0ljPJ2apr02ujePA1HuBiky9~0Rws774ZIAwseDXIMXV2V8vh3kHYz3L2WFEWWZbVAmbJYPtBhTzqd5tYq~BunZvg9Kw8KubbBUOBgS~CCea---Ieaiyal2Y0twdWwnuBBnJl74UOyJOOuZ8hV5UERmIZNGEd7OxXkz5S2~eQvRBquyRZ2~Q__&Key-Pair-Id=KKMPOJU8AYATR" alt="QR code" style="width:90px;height:90px;object-fit:contain;" />
  </div>

  <div style="text-align:left;">
    <div style="font-size:0.88rem;font-weight:700;color:white;margin-bottom:0.2rem;">donne4.it/hack-job-title</div>
    <div style="font-size:0.75rem;color:rgba(255,255,255,0.75);">Guida pratica &middot; Risorse &middot; Contatti</div>
  </div>


  <div style="text-align:left;">
    <div style="font-size:0.88rem;font-weight:700;color:white;margin-bottom:0.2rem;"></div>
      <img src="https://github.com/kiaruzza/hack-the-job-title/blob/develop/public/feedback-qr-code.png?raw=true" class="h-20" />
  </div>


  <div style="text-align:left;">
    <div style="font-size:0.88rem;font-weight:700;color:white;margin-bottom:0.2rem;">Feedback</div>
  </div>

</div>
</div>
