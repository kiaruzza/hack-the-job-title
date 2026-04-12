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

.tag {
  font-size: 0.75rem;
  font-weight: 600;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--red-main);
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

.highlight-line span {
  color: var(--red-main);
}

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

.qr-placeholder {
  width: 150px;
  height: 150px;
  background: #F8F8F8;
  border: 2px dashed #E8001C;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 0.4rem;
}

.qr-placeholder-sm {
  width: 100px;
  height: 100px;
  background: #F8F8F8;
  border: 2px dashed #E8001C;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 0.3rem;
}
</style>

---
layout: cover
background: https://www.donne4.it/wp-content/uploads/2023/10/foto-gruppo.jpg
---

<div style="position:absolute;inset:0;background:linear-gradient(to right, rgba(232,0,28,0.85) 0%, rgba(232,0,28,0.6) 50%, rgba(0,0,0,0.3) 100%);"></div>

<div style="position:relative;z-index:10;display:flex;flex-direction:column;justify-content:center;height:100%;padding:0 3rem;">

<div style="margin-bottom:0.5rem;">
  <span style="font-size:0.75rem;font-weight:700;letter-spacing:0.2em;text-transform:uppercase;color:rgba(255,255,255,0.8);">Talk · Career · Tech Culture</span>
</div>

<h1 style="font-size:3rem;font-weight:900;color:white;line-height:1.1;margin-bottom:0.8rem;text-shadow:0 2px 8px rgba(0,0,0,0.3);">
  Hack the Job Title
</h1>

<p style="font-size:1.3rem;font-weight:600;color:rgba(255,255,255,0.92);margin-bottom:2rem;text-shadow:0 1px 4px rgba(0,0,0,0.3);">
  Il lavoro reale dietro i titoli del tech
</p>

<div style="display:flex;gap:1.5rem;flex-wrap:wrap;margin-bottom:2rem;">
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.6rem 1rem;">
    <div style="font-weight:700;color:white;font-size:0.88rem;">Chiara Corrado</div>
    <div style="font-size:0.7rem;color:rgba(255,255,255,0.75);">Tech & Orientamento</div>
  </div>
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.6rem 1rem;">
    <div style="font-weight:700;color:white;font-size:0.88rem;">Luciana Bertoncini</div>
    <div style="font-size:0.7rem;color:rgba(255,255,255,0.75);">Tech & Ruoli</div>
  </div>
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.6rem 1rem;">
    <div style="font-weight:700;color:white;font-size:0.88rem;">Pinelopi Troullinou</div>
    <div style="font-size:0.7rem;color:rgba(255,255,255,0.75);">Ethics & Linguaggio</div>
  </div>
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.6rem 1rem;">
    <div style="font-weight:700;color:white;font-size:0.88rem;">Federica Merenda</div>
    <div style="font-size:0.7rem;color:rgba(255,255,255,0.75);">Gender Equality</div>
  </div>
</div>

<div style="font-size:0.82rem;color:rgba(255,255,255,0.7);font-weight:600;letter-spacing:0.05em;">
  WTM Pisa × Donne 4.0
</div>

</div>

---
layout: center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Chi siamo — Donne 4.0
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;max-width:720px;margin:0 auto 1.2rem;">

<div class="cluster-box">

<div class="cluster-box-title">La missione</div>

Rendere **protagoniste le donne** nell'affrontare le sfide globali e costruire con le tecnologie un futuro **inclusivo e sostenibile**.

</div>

<div class="cluster-box">

<div class="cluster-box-title">I nostri valori</div>

- ❤️ Solidarietà
- 🌍 Agenda ONU 2030
- 🎓 Cultura e formazione
- 🤝 Rappresentanza e rete

</div>

</div>

<div class="data-box" style="max-width:720px;margin:0 auto;">
  Questo talk è esattamente il lavoro di Donne 4.0:<br>
  <strong>tradurre il tech in un linguaggio che includa, non escluda.</strong>
</div>

---
layout: center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Chi parla oggi
</h2>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;max-width:680px;margin:0 auto;">

<div class="cluster-box">
  <div class="cluster-box-title">Tech & Orientamento</div>
  <div style="font-size:1rem;font-weight:700;color:#1a1f3a;">Chiara Corrado</div>
  <div style="font-size:0.8rem;color:#666;margin-top:0.3rem;">Introduce il tema e guida la mappa dei ruoli tech</div>
</div>

<div class="cluster-box">
  <div class="cluster-box-title">Tech & Ruoli</div>
  <div style="font-size:1rem;font-weight:700;color:#1a1f3a;">Luciana Bertoncini</div>
  <div style="font-size:0.8rem;color:#666;margin-top:0.3rem;">Approfondisce i cluster e le competenze strutturali</div>
</div>

<div class="cluster-box">
  <div class="cluster-box-title">Ethics & Linguaggio</div>
  <div style="font-size:1rem;font-weight:700;color:#1a1f3a;">Pinelopi Troullinou</div>
  <div style="font-size:0.8rem;color:#666;margin-top:0.3rem;">Il linguaggio che esclude e i dati sul gender gap</div>
</div>

<div class="cluster-box">
  <div class="cluster-box-title">Gender Equality</div>
  <div style="font-size:1rem;font-weight:700;color:#1a1f3a;">Federica Merenda</div>
  <div style="font-size:0.8rem;color:#666;margin-top:0.3rem;">Ethics Expert, cosa possiamo fare meglio</div>
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
    "Ok… ma quindi questa persona cosa fa?"
  </div>
</div>

---
layout: two-cols
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

<div style="padding-left:2rem;display:flex;flex-direction:column;justify-content:center;height:100%;">
  <div style="font-size:1.3rem;font-weight:800;color:#1a1f3a;margin-bottom:0.8rem;">
    Sembrano lavori diversi.
  </div>
  <div style="font-size:1.8rem;font-weight:900;color:#E8001C;line-height:1.3;">
    Ma spesso…<br>non lo sono.
  </div>
</div>

---
layout: center
class: text-center
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.2rem;font-weight:600;color:#E8001C;margin-bottom:1rem;">Il problema</h2>

<div class="highlight-line" style="margin-bottom:0.8rem;">
  Non è che i lavori sono complessi.
</div>

<div class="highlight-line">
  È che li <span>raccontiamo male.</span>
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
  <div style="color:#E8001C;font-size:1.6rem;line-height:1;">↓</div>
  <div style="background:#FFD6D6;color:#B8001A;font-weight:700;font-size:1rem;padding:0.7rem 2.5rem;border-radius:8px;width:100%;text-align:center;">Specializzazione</div>
  <div style="color:#E8001C;font-size:1.6rem;line-height:1;">↓</div>
  <div style="background:#FFD6D6;color:#B8001A;font-weight:700;font-size:1rem;padding:0.7rem 2.5rem;border-radius:8px;width:100%;text-align:center;">Titoli sempre più specifici</div>
  <div style="color:#E8001C;font-size:1.6rem;line-height:1;">↓</div>
  <div style="background:#1a1f3a;color:white;font-weight:700;font-size:1rem;padding:0.7rem 2.5rem;border-radius:8px;width:100%;text-align:center;">Sempre meno comprensibili</div>
</div>

---
layout: two-cols
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:0.5rem;">Esempio</h2>
<h3 style="font-size:1.1rem;font-weight:700;color:#E8001C;margin-bottom:1.2rem;">TPU Software Tech Lead</h3>

<div class="cluster-box">

<div class="cluster-box-title">🔴 Sembra</div>

- Qualcosa di iper-specialistico
- Quasi incomprensibile
- Molto lontano da "sviluppo software"

</div>

<div style="margin-top:1.5rem;" class="highlight-line">
  Cambia il contesto.<br>
  <span>Non il mestiere.</span>
</div>

::right::

<div style="padding-left:1.5rem;margin-top:3rem;">

<div class="cluster-box" style="margin-bottom:1rem;">

<div class="cluster-box-title">🟢 È</div>

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
  <span>in ciò che fanno davvero</span>
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

<div class="cluster-box-title">1 · Costruire</div>

- Software Engineer
- ML Engineer
- Application Engineer

</div>

<div class="cluster-box">

<div class="cluster-box-title">2 · Capire & sperimentare</div>

- Data Scientist
- Research Scientist
- Student Researcher

</div>

<div class="cluster-box">

<div class="cluster-box-title">3 · Far funzionare</div>

- DevOps Engineer
- SRE
- Performance Engineer

</div>

<div class="cluster-box">

<div class="cluster-box-title">4 · Proteggere</div>

- Security Engineer
- IT Security Specialist

</div>

<div class="cluster-box">

<div class="cluster-box-title">5 · Tradurre</div>

- UX/UI Designer
- BI Developer
- Help Client Service

</div>

<div class="cluster-box">

<div class="cluster-box-title">6 · Specializzarsi</div>

- Silicon Engineer
- Display Test Engineer

</div>

</div>

<div style="text-align:center;margin-top:0.8rem;font-size:0.75rem;color:#888;">
  + Cluster 7: Dare direzione e senso → slide successiva
</div>

---
layout: two-cols
---

<div class="speaker-badge">Chiara</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 1 — Costruire
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

<div style="padding-left:1.5rem;margin-top:3rem;">

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
---

<div class="speaker-badge">Chiara → Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 2 — Capire e sperimentare
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

<div style="padding-left:1.5rem;margin-top:3rem;">

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
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 3 — Far funzionare
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">

<div class="cluster-box-title">Ruoli</div>

- DevOps Coordinator
- System Performance Engineer
- SRE (Site Reliability Engineer)

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Non costruiscono la feature.<br>
  <span>Fanno sì che funzioni davvero.</span>
</div>

::right::

<div style="padding-left:1.5rem;margin-top:3rem;">

<div class="cluster-box">

<div class="cluster-box-title">Cosa fanno davvero</div>

- Gestiscono il "mettere online" i sistemi
- Monitorano performance e affidabilità
- Intervengono quando qualcosa si rompe
- Garantiscono che tutto regga sotto carico

</div>

</div>

---
layout: two-cols
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 4 — Proteggere
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

<div style="padding-left:1.5rem;margin-top:3rem;">

<div class="cluster-box">

<div class="cluster-box-title">Cosa fanno davvero</div>

- Mettono in sicurezza sistemi e dati
- Analizzano vulnerabilità
- Prevengono attacchi e incidenti
- Riducono il rischio operativo

</div>

</div>

---
layout: two-cols
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 5 — Tradurre per le persone
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">

<div class="cluster-box-title">Ruoli</div>

- UX/UI Designer
- BI Developer
- Help & Client Service

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Il tech da solo non basta.<br>
  <span>Servono persone che traducano.</span>
</div>

::right::

<div style="padding-left:1.5rem;margin-top:3rem;">

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
---

<div class="speaker-badge">Luciana</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 6 — Specializzazioni estreme
</h2>

<div class="cluster-box" style="margin-bottom:1.2rem;">

<div class="cluster-box-title">Ruoli</div>

- Silicon Engineer
- Display Test Engineer

</div>

<div class="highlight-line" style="font-size:1.3rem;">
  Sempre ingegneria.<br>
  <span>Solo più vicino al silicio.</span>
</div>

::right::

<div style="padding-left:1.5rem;margin-top:3rem;">

<div class="cluster-box">

<div class="cluster-box-title">Cosa fanno davvero</div>

- Lavorano vicino all'hardware fisico
- Ottimizzano chip, schermi, sensori
- Testano e raffinano sistemi a basso livello
- Richiedono profondità tecnica molto alta

</div>

</div>

---
layout: two-cols
---

<div class="speaker-badge">Federica</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;">
  Cluster 7 — Dare direzione e senso
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

<div style="padding-left:1.5rem;margin-top:3rem;">

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;margin-bottom:1rem;">

<div class="cluster-box-title">Cosa fanno davvero</div>

- Analizzano impatti sociali e culturali
- Identificano bias e rischi nei sistemi
- Guidano decisioni responsabili
- Rendono il tech più equo e inclusivo

</div>

<div class="data-box" style="font-size:0.82rem;">
  È il lavoro che fa anche <strong>Donne 4.0</strong>:<br>
  chiedere "per chi stiamo costruendo?"
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

<div class="cluster-box-title">Le chiamano "soft skill"</div>

- Comunicazione
- Mediazione tra team diversi
- Pensiero sistemico
- Traduzione tra mondi

</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">

<div class="cluster-box-title">In realtà sono</div>

- Strutturali
- Non sostituibili dalle macchine
- Richieste in ogni cluster
- Spesso già presenti in chi viene da fuori

</div>

</div>

<div style="text-align:center;">
  <div class="highlight-line" style="font-size:1.5rem;">
    Non sono "soft". <span>Sono strutturali.</span>
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
  Non è solo una sensazione.
</h2>

<div style="font-size:2rem;font-weight:900;color:#E8001C;">
  È un dato.
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
  Non per mancanza di competenze — ma per come vengono scritti gli annunci.
  <div class="source-note">Fonte: ricerca interna HP citata in S. Sandberg, <em>Lean In</em> (2013); approfondita da T.S. Mohr, <em>Harvard Business Review</em>, agosto 2014</div>
</div>

---
layout: center
---

<div class="speaker-badge">Pinelopi</div>

<h2 style="font-size:1.4rem;font-weight:800;color:#1a1f3a;margin-bottom:1.2rem;text-align:center;">
  Perché succede?
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
  Un annuncio scritto male <strong style="color:#E8001C;">non è neutro</strong>. Esclude.
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
  Il loro lavoro è identificare dove il sistema — incluso il linguaggio — produce esclusione. E cambiarlo.
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
- Separare "essenziale" da "preferibile"
- Usare esempi concreti

</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">

<div class="cluster-box-title">Chi legge un annuncio</div>

- Cercare i pattern, non il titolo
- Tradurre in attività reali
- Non lasciarsi bloccare dalla lista
- Al 60–70%? Vale la pena candidarsi

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

<div class="speaker-badge">Tutte — Guida pratica 1/4</div>

## Passi 1 e 2

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">

**1 — Ignora il titolo (all'inizio)**

Il titolo può essere creativo, aziendale, non standard.

👉 **Non partire da lì.** Vai diretto alla descrizione delle attività.

</div>

<div class="cluster-box">

**2 — Cerca i verbi, non le tecnologie**

I verbi raccontano il lavoro reale:

**sviluppare · progettare · analizzare · monitorare · collaborare**

- "design and implement" → <span style="color:#E8001C;font-weight:700;">costruire</span>
- "analyze data and build models" → <span style="color:#E8001C;font-weight:700;">analizzare</span>
- "ensure reliability" → <span style="color:#E8001C;font-weight:700;">far funzionare</span>

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte — Guida pratica 2/4</div>

## Passi 3 e 4

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">

**3 — In quale cluster rientra?**

- scrive codice? → <span style="color:#E8001C;font-weight:700;">costruire</span>
- lavora sui dati? → <span style="color:#E8001C;font-weight:700;">analizzare</span>
- gestisce sistemi? → <span style="color:#E8001C;font-weight:700;">far funzionare</span>
- lavora sulla sicurezza? → <span style="color:#E8001C;font-weight:700;">proteggere</span>
- lavora con utenti o business? → <span style="color:#E8001C;font-weight:700;">tradurre</span>

</div>

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">

**4 — Non farti bloccare dalla lista**

Quelle liste lunghe di requisiti? **Sono wishlist.**

Nessuno le soddisfa al 100%. Neanche chi viene assunto.

Al 60–70% dei requisiti rilevanti?

**→ Vale la pena candidarsi.**

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte — Guida pratica 3/4</div>

## Passi 5 e 6

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;margin-top:0.8rem;">

<div class="cluster-box">

**5 — Individua le competenze trasversali**

Cerca nella descrizione:

**communication · collaboration · stakeholder management · problem solving**

👉 Questi segnali spesso contano **più delle tecnologie**.

</div>

<div class="cluster-box">

**6 — Traduci in una frase**

Prova a completare:

> *"Questa persona serve per…"*

- "costruire sistemi backend scalabili"
- "analizzare dati per supportare decisioni"
- "rendere il prodotto usabile dagli utenti"

Se riesci a farlo, **hai capito il ruolo**.

</div>

</div>

---
layout: default
---

<div class="speaker-badge">Tutte — Guida pratica 4/4</div>

## Passo 7 + Guida completa

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin-top:0.8rem;">

<div class="cluster-box" style="border-color:#E8001C;background:#FFF0F0;">

**7 — Fatti la domanda giusta**

❌ Non: *"Conosco tutte queste tecnologie?"*

✅ Ma: **"Mi piace fare questo tipo di lavoro?"**

Le tecnologie si imparano.

La motivazione no.

</div>

<div style="display:flex;flex-direction:column;align-items:center;justify-content:center;gap:1rem;">

<div class="data-box" style="text-align:center;width:100%;">
  Vuoi la guida completa<br>con esempi e job posting annotati?
</div>

<div class="qr-placeholder">
  <div style="font-size:0.65rem;color:#E8001C;font-weight:700;text-transform:uppercase;letter-spacing:0.1em;">QR Code</div>
  <div style="display:grid;grid-template-columns:repeat(5,1fr);gap:3px;padding:6px;">
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#FFF0F0;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
    <div style="width:10px;height:10px;background:#E8001C;border-radius:1px;"></div>
  </div>
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

<div class="speaker-badge">Chiara — chiusura</div>

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
  non è ancora stato tradotto<br>nel modo giusto.
</div>

---
layout: cover
background: https://www.donne4.it/wp-content/uploads/2023/10/foto-gruppo.jpg
---

<div style="position:absolute;inset:0;background:linear-gradient(to right, rgba(232,0,28,0.88) 0%, rgba(232,0,28,0.65) 55%, rgba(0,0,0,0.25) 100%);"></div>

<div style="position:relative;z-index:10;display:flex;flex-direction:column;justify-content:center;height:100%;padding:0 3rem;">

<h1 style="font-size:2.8rem;font-weight:900;color:white;line-height:1.1;margin-bottom:0.6rem;text-shadow:0 2px 8px rgba(0,0,0,0.3);">
  Grazie ❤️
</h1>

<h2 style="font-size:1.2rem;font-weight:600;color:rgba(255,255,255,0.9);margin-bottom:1.8rem;">
  Hack the Job Title — WTM Pisa × Donne 4.0
</h2>

<div style="display:flex;gap:1rem;flex-wrap:wrap;margin-bottom:2rem;">
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.5rem 0.9rem;">
    <div style="font-weight:700;color:white;font-size:0.85rem;">Chiara Corrado</div>
  </div>
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.5rem 0.9rem;">
    <div style="font-weight:700;color:white;font-size:0.85rem;">Luciana Bertoncini</div>
  </div>
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.5rem 0.9rem;">
    <div style="font-weight:700;color:white;font-size:0.85rem;">Pinelopi Troullinou</div>
  </div>
  <div style="background:rgba(255,255,255,0.15);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,0.3);border-radius:10px;padding:0.5rem 0.9rem;">
    <div style="font-weight:700;color:white;font-size:0.85rem;">Federica Merenda</div>
  </div>
</div>

<div style="display:flex;align-items:center;gap:1.5rem;">
  <div class="qr-placeholder-sm" style="background:rgba(255,255,255,0.9);border-color:white;">
    <div style="font-size:0.55rem;color:#E8001C;font-weight:700;text-transform:uppercase;">QR</div>
    <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:2px;padding:4px;">
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#FFF0F0;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#FFF0F0;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#FFF0F0;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#FFF0F0;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#FFF0F0;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#E8001C;border-radius:1px;"></div>
      <div style="width:8px;height:8px;background:#FFF0F0;border-radius:1px;"></div>
    </div>
  </div>
  <div style="text-align:left;">
    <div style="font-size:0.88rem;font-weight:700;color:white;">donne4.it/hack-job-title</div>
    <div style="font-size:0.75rem;color:rgba(255,255,255,0.75);">Guida pratica · Risorse · Contatti</div>
  </div>
</div>

</div>