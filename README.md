<!DOCTYPE html>
<html lang="cs">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>GLJA EUROPE — Global Level of Justice Auditor</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Rajdhani:wght@300;400;600;700&family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">
<style>
  :root {
    --green: #00ff41;
    --green-dim: #00cc33;
    --green-ghost: rgba(0,255,65,0.07);
    --bg: #0a0a0a;
    --bg2: #111111;
    --border: #1e1e1e;
    --border-bright: #2a2a2a;
    --text: #c8c8c8;
    --text-dim: #888;
    --text-bright: #ebebeb;
    --red: #ff3333;
    --amber: #ffaa00;
    --blue: #00aaff;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Rajdhani', sans-serif;
    font-size: 16px;
    line-height: 1.7;
    padding: 4rem 6vw;
    max-width: 900px;
    margin: 0 auto;
  }
  h1 {
    font-family: 'Orbitron', sans-serif;
    font-size: clamp(1.8rem, 4vw, 2.6rem);
    color: var(--text-bright);
    margin-bottom: 0.5rem;
  }
  .quote {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.95rem;
    color: var(--green-dim);
    border-left: 2px solid var(--green);
    padding-left: 1rem;
    margin: 1rem 0 1.5rem 0;
  }
  .badges { display: flex; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 2rem; }
  .badge {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.68rem;
    padding: 0.3rem 0.7rem;
    border-radius: 2px;
    letter-spacing: 0.08em;
  }
  .badge-green { background: rgba(0,255,65,0.08); border: 1px solid rgba(0,255,65,0.4); color: var(--green); }
  .badge-red   { background: rgba(255,51,51,0.08); border: 1px solid rgba(255,51,51,0.4); color: var(--red); }

  h2 {
    font-family: 'Orbitron', sans-serif;
    font-size: 1.3rem;
    color: var(--text-bright);
    margin: 2.5rem 0 1rem 0;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid var(--border-bright);
  }
  h3 {
    font-family: 'Rajdhani', sans-serif;
    font-weight: 700;
    font-size: 1.05rem;
    color: var(--text-bright);
    margin: 1.5rem 0 0.8rem 0;
  }
  p { margin-bottom: 1rem; color: var(--text); }
  strong { color: var(--text-bright); }
  code {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.85em;
    background: rgba(0,255,65,0.06);
    border: 1px solid rgba(0,255,65,0.15);
    padding: 0.1em 0.4em;
    color: var(--green-dim);
    border-radius: 2px;
  }
  pre {
    background: var(--bg2);
    border: 1px solid var(--border-bright);
    padding: 1.2rem 1.5rem;
    overflow-x: auto;
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.78rem;
    color: var(--text-dim);
    line-height: 1.8;
    margin-bottom: 1.5rem;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 1.5rem;
    font-size: 0.9rem;
  }
  th, td {
    text-align: left;
    padding: 0.6rem 0.8rem;
    border: 1px solid var(--border-bright);
  }
  th {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.7rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--green);
    background: var(--bg2);
  }
  td { color: var(--text); }
  hr { border: none; border-top: 1px solid var(--border-bright); margin: 2.5rem 0; }
  .status-present { color: var(--green); font-family: 'Share Tech Mono', monospace; font-weight: 700; }
  .status-progress { color: var(--amber); font-family: 'Share Tech Mono', monospace; font-weight: 700; }
  .status-planned { color: var(--blue); font-family: 'Share Tech Mono', monospace; font-weight: 700; }
  ul { padding-left: 1.4rem; margin-bottom: 1rem; }
  li { margin-bottom: 0.4rem; }
  footer {
    margin-top: 3rem;
    padding-top: 1.5rem;
    border-top: 1px solid var(--border-bright);
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.75rem;
    color: var(--text-dim);
    text-align: center;
  }
</style>
</head>
<body>

<h1>GLJA EUROPE — Global Level of Justice Auditor</h1>
<div class="quote">"V bohatství je pokora."</div>

<div class="badges">
  <span class="badge badge-green">Status: In-Development (Alpha)</span>
  <span class="badge badge-green">PAdES-BASELINE-T Verified</span>
  <span class="badge badge-green">SHA-256 Chained</span>
  <span class="badge badge-red">License: Proprietary</span>
</div>

<hr>

<h2>Co je GLJA EUROPE?</h2>
<p><strong>GLJA EUROPE</strong> (Global Level of Justice Auditor) je neadvokátní LegalTech platforma zaměřená na procesní auditovatelnost a důkazní integritu. Projekt propojuje kryptografické důkazní řetězení (SHA-256 / Merkle tree), cloudovou infrastrukturu a AI orchestraci do jednoho transparentního systému.</p>
<p>Platforma <strong>není</strong> advokacie, neposkytuje právní zastoupení a nevydává právní rady. Měří <strong>procesní konzistenci</strong>, nikoli právo.</p>
<p><strong>Status projektu:</strong> Ve fázi aktivního vývoje (Alpha state). Zaměřeno na validaci metodiky a architektury procesních auditů.</p>

<h2>Architektura systému</h2>
<pre>GLJA EUROPE Ecosystem
│
├── 📋 Corpus (Konsolidované dokumenty)
│   ├── CATEGORY A – Manifesty (Zakládající dokumenty)
│   ├── CATEGORY B – Governance &amp; Právní rámec
│   ├── CATEGORY C – Audit &amp; Interní dokumentace
│   ├── CATEGORY D – Protokoly &amp; Manuály
│   └── CATEGORY E – Web &amp; Dashboard
│
├── 🔐 Kryptografická vrstva
│   ├── SHA-256 / SHA-512 Hash Registry (Annex B)
│   ├── Merkle Tree – řetězení důkazů
│   ├── PAdES-BASELINE-T časová razítka
│   └── Offline verifikace (air-gapped endpoint)
│
├── ☁️  Cloudová infrastruktura
│   ├── Microsoft Azure (AI orchestrace, datová integrace)
│   ├── Microsoft 365 (compliance, auditní logy)
│   └── WORM úložiště (neměnné záznamy)
│
└── 🌐 Web3 identita
    └── @glja.eu (institucionální uzel)</pre>

<h2>Klíčové principy (Doktrinální konstanty)</h2>
<table>
  <tr><th>Konstanta</th><th>Definice</th></tr>
  <tr><td><strong>AUTORSTVÍ ≠ PODPIS ≠ ODPOVĚDNOST</strong></td><td>Architektonické autorství metodiky nezakládá podpisovou autoritu ani právní/finanční odpovědnost za výstupy systému.</td></tr>
  <tr><td><strong>RMK-512</strong></td><td>Identifikátor provenance / brand only. Neslouží jako podpis, pečeť ani runtime klíč.</td></tr>
  <tr><td><strong>EVIDENCE RULE</strong></td><td>Striktní oddělení Audit Trail vs. Signature Artifact. Absence binárních dat = stav <code>UNKNOWN</code>. Extrapolace zakázána.</td></tr>
  <tr><td><strong>LEGAL STATUS</strong></td><td>GLJA EUROPE není advokacie. Projekt měří procesní konzistenci, nikoli právo.</td></tr>
</table>

<h2>Metodika SHA-256 a důkazní řetězení</h2>
<p>Každý auditní krok je zaznamenán, hashován a ukotven v decentralizovaném úložišti:</p>
<pre>Krok N  →  SHA-256(data_N + hash_{N-1})  →  Merkle Node
                                                  │
                                          Decentralizované
                                          úložiště (on-chain)</pre>
<p><strong>Forenzní vlastnosti:</strong></p>
<ul>
  <li>Kryptograficky ověřitelná integrita záznamu od okamžiku jeho vytvoření</li>
  <li>Nezávislá offline verifikace bez přístupu k provozovateli</li>
  <li>Navrženo v souladu s eIDAS standardy pro důvěryhodné služby</li>
</ul>

<h2>Druhý pilíř: koncept technologické podpory alternativních trestů</h2>
<p>GLJA EUROPE připravuje koncept technologické podpory v oblasti dohledu nad plněním alternativních trestů. Jde o <strong>časnou fázi přípravy</strong> — model prochází právní a metodickou revizí, dosud nemá žádnou právní platnost ani reálné nasazení.</p>
<p><strong>Základní princip:</strong> GLJA nerozhoduje o vině, trestu ani podmínkách propuštění — to zůstává výhradní pravomocí soudu. Výstupy systému by sloužily jako podklad pro rozhodování soudu/Probační a mediační služby, nikoli jako náhrada jejich rozhodovací pravomoci (analogie k modelu ratingových agentur).</p>
<p>Jakékoli zapojení konkrétní osoby by bylo podmíněno rozhodnutím soudu/PMS jako právním titulem pro zpracování dat — ne pouhým souhlasem — v souladu s čl. 10 GDPR. Bez takového rozhodnutí a bez uzavřené smlouvy o zpracování osobních údajů se žádný sběr dat nerealizuje.</p>

<h2>Struktura Corpusu a Master Deed</h2>
<p>Celý Corpus dokumentů je konsolidován v interním konsolidačním dokumentu (GLJA EUROPE), datovaném 30. 4. 2026, Znojmo, ČR.</p>
<h3>Hierarchie výkladu (při rozporu v Corpusu)</h3>
<pre>1. Manifesty (Zakládající dokumenty)
2. Governance a právní rámec
3. Memoranda
4. Protokoly a Manuály</pre>

<h3>Podpisový blok</h3>
<table>
  <tr><th>Podepisující</th><th>Role</th><th>Identifikační systém</th><th>Čas identifikace</th></tr>
  <tr><td>Roman Mužný Kašpar</td><td>Zakladatel / Architekt</td><td>Bankovní Identita</td><td>2026-05-01T08:47:56Z</td></tr>
  <tr><td>David Mužný</td><td>Partner / Spolupodepisující</td><td>Bankovní Identita</td><td>2026-05-01T08:51:43Z</td></tr>
</table>

<h2>Institucionální identita</h2>
<pre>Zakladatel / Architekt:  Roman Mužný Kašpar
IČO:                     04007689 (OSVČ → GLJA EUROPE s.r.o.)
Institucionální uzel:    @glja.eu
Místo baseline:          Znojmo, Česká republika
Datum baseline:          1. 5. 2026</pre>
<p><strong>Kontakt:</strong> <code>glja-europe@seznam.cz</code></p>

<h2>Stav Corpusu (Roadmapa)</h2>
<p><em>Aktuální stav k baseline 1. 5. 2026</em></p>
<ul>
  <li><span class="status-present">Phase 1: Foundations &amp; Architecture</span> — Ratified · základní metodika a strukturální návrh</li>
  <li><span class="status-progress">Phase 2: Data Validation &amp; Integration</span> — In Progress · binární ověření, kompletace hash registru</li>
  <li><span class="status-planned">Phase 3: Institutional Pilot</span> — Planned · externí právní a technický audit, první partnerská jednání</li>
  <li><span class="status-present">Audit Trail:</span> GLJA-LEG-002 dostupný (Podpisovna.cz, str. 6–7)</li>
</ul>

<h2>Právní upozornění</h2>
<p>GLJA EUROPE je <strong>neadvokátní LegalTech infrastruktura ve fázi vývoje</strong>. Veškeré výstupy systému jsou procesní a auditní povahy — nepředstavují právní rady, právní zastoupení ani soudní rozhodnutí. Architektonické autorství systému nezakládá osobní právní nebo finanční odpovědnost zakladatelů za výstupy platformy.</p>

<footer>GLJA EUROPE | Baseline 1. 5. 2026</footer>

</body>
</html>
