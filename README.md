# GLJA EUROPE — Global Level of Justice Auditor

> *"V bohatství je pokora."*

![Status](https://img.shields.io/badge/Status-In--Development%20(Alpha)-brightgreen)
![PAdES](https://img.shields.io/badge/PAdES--BASELINE--T-Verified-brightgreen)
![SHA256](https://img.shields.io/badge/SHA--256-Chained-brightgreen)
![License](https://img.shields.io/badge/License-Proprietary-red)

---

## Co je GLJA EUROPE?

**GLJA EUROPE** (Global Level of Justice Auditor) je neadvokátní LegalTech platforma zaměřená na procesní auditovatelnost a důkazní integritu. Projekt propojuje kryptografické důkazní řetězení (SHA-256 / Merkle tree), cloudovou infrastrukturu a AI orchestraci do jednoho transparentního systému.

Platforma **není** advokacie, neposkytuje právní zastoupení a nevydává právní rady. Měří **procesní konzistenci**, nikoli právo.

**Status projektu:** Ve fázi aktivního vývoje (Alpha state). Zaměřeno na validaci metodiky a architektury procesních auditů.

## Architektura systému

```
GLJA EUROPE Ecosystem
│
├── 📋 Corpus (Konsolidované dokumenty)
│   ├── CATEGORY A – Manifesty (Zakládající dokumenty)
│   ├── CATEGORY B – Governance & Právní rámec
│   ├── CATEGORY C – Audit & Interní dokumentace
│   ├── CATEGORY D – Protokoly & Manuály
│   └── CATEGORY E – Web & Dashboard
│
├── 🔐 Kryptografická vrstva
│   ├── SHA-256 / SHA-512 Hash Registry (Annex B)
│   ├── Merkle Tree – řetězení důkazů
│   ├── PAdES-BASELINE-T časová razítka
│   └── Offline verifikace (air-gapped endpoint)
│
├── ☁️ Cloudová infrastruktura
│   ├── Microsoft Azure (AI orchestrace, datová integrace)
│   ├── Microsoft 365 (compliance, auditní logy)
│   └── WORM úložiště (neměnné záznamy)
│
└── 🌐 Web3 identita
    └── @glja.eu (institucionální uzel)
```

## Klíčové principy (Doktrinální konstanty)

| Konstanta | Definice |
|---|---|
| **AUTORSTVÍ ≠ PODPIS ≠ ODPOVĚDNOST** | Architektonické autorství metodiky nezakládá podpisovou autoritu ani právní/finanční odpovědnost za výstupy systému. |
| **RMK-512** | Identifikátor provenance / brand only. Neslouží jako podpis, pečeť ani runtime klíč. |
| **EVIDENCE RULE** | Striktní oddělení Audit Trail vs. Signature Artifact. Absence binárních dat = stav `UNKNOWN`. Extrapolace zakázána. |
| **LEGAL STATUS** | GLJA EUROPE není advokacie. Projekt měří procesní konzistenci, nikoli právo. |

## Metodika SHA-256 a důkazní řetězení

Každý auditní krok je zaznamenán, hashován a ukotven v decentralizovaném úložišti:

```
Krok N  →  SHA-256(data_N + hash_{N-1})  →  Merkle Node
                                                  │
                                          Decentralizované
                                          úložiště (on-chain)
```

**Forenzní vlastnosti:**

- Kryptograficky ověřitelná integrita záznamu od okamžiku jeho vytvoření
- Nezávislá offline verifikace bez přístupu k provozovateli
- Navrženo v souladu s eIDAS standardy pro důvěryhodné služby

## Druhý pilíř: koncept technologické podpory alternativních trestů

GLJA EUROPE připravuje koncept technologické podpory v oblasti dohledu nad plněním alternativních trestů. Jde o **časnou fázi přípravy** — model prochází právní a metodickou revizí, dosud nemá žádnou právní platnost ani reálné nasazení.

**Základní princip:** GLJA nerozhoduje o vině, trestu ani podmínkách propuštění — to zůstává výhradní pravomocí soudu. Výstupy systému by sloužily jako podklad pro rozhodování soudu/Probační a mediační služby, nikoli jako náhrada jejich rozhodovací pravomoci (analogie k modelu ratingových agentur).

Jakékoli zapojení konkrétní osoby by bylo podmíněno rozhodnutím soudu/PMS jako právním titulem pro zpracování dat — ne pouhým souhlasem — v souladu s čl. 10 GDPR. Bez takového rozhodnutí a bez uzavřené smlouvy o zpracování osobních údajů se žádný sběr dat nerealizuje.

## Struktura Corpusu a Master Deed

Celý Corpus dokumentů je konsolidován v interním konsolidačním dokumentu (GLJA EUROPE), datovaném 30. 4. 2026, Znojmo, ČR.

### Hierarchie výkladu (při rozporu v Corpusu)

```
1. Manifesty (Zakládající dokumenty)
2. Governance a právní rámec
3. Memoranda
4. Protokoly a Manuály
```

### Podpisový blok

| Podepisující | Role | Identifikační systém | Čas identifikace |
|---|---|---|---|
| Roman Mužný Kašpar | Zakladatel / Architekt | Bankovní Identita | 2026-05-01T08:47:56Z |
| David Mužný | Partner / Spolupodepisující | Bankovní Identita | 2026-05-01T08:51:43Z |

## Institucionální identita

```
Zakladatel / Architekt:  Roman Mužný Kašpar
IČO:                     04007689 (OSVČ → GLJA EUROPE s.r.o.)
Institucionální uzel:    @glja.eu
Místo baseline:          Znojmo, Česká republika
Datum baseline:          1. 5. 2026
```

**Kontakt:** `glja-europe@seznam.cz`

## Stav Corpusu (Roadmapa)

*Aktuální stav k baseline 1. 5. 2026*

- 🟢 **Phase 1: Foundations & Architecture** — Ratified · základní metodika a strukturální návrh
- 🟡 **Phase 2: Data Validation & Integration** — In Progress · binární ověření, kompletace hash registru
- 🔵 **Phase 3: Institutional Pilot** — Planned · externí právní a technický audit, první partnerská jednání
- 🟢 **Audit Trail:** GLJA-LEG-002 dostupný (Podpisovna.cz, str. 6–7)

## Právní upozornění

GLJA EUROPE je **neadvokátní LegalTech infrastruktura ve fázi vývoje**. Veškeré výstupy systému jsou procesní a auditní povahy — nepředstavují právní rady, právní zastoupení ani soudní rozhodnutí. Architektonické autorství systému nezakládá osobní právní nebo finanční odpovědnost zakladatelů za výstupy platformy.

---

<p align="center"><sub>GLJA EUROPE | Baseline 1. 5. 2026</sub></p>
