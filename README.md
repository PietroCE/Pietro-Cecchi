# Specola OS — Podere La Specola

Questo repository contiene la **prima base operativa** per costruire un cervello aziendale dedicato a Podere La Specola.

> Nota importante: questo repo risulta pubblico. Per questo motivo qui ho creato solo struttura, template e procedure **senza dati sensibili**. Prenotazioni, fatture, incassi, clienti e documenti fiscali devono stare in Google Drive/Sheets privati o in un repository privato.

## Obiettivo

Creare un sistema unico per gestire:

- sito nuovo su Netlify;
- richieste ospiti e preventivi;
- pre-contabilità;
- esperienze e servizi extra;
- operations e manutenzione;
- marketing e contenuti;
- report mensili;
- controllo qualità del brand.

## Struttura

```text
specola-os/
├── docs/                  # cervello aziendale e regole operative
├── prompts/               # prompt fissi per gli agenti
├── sheets/                # template colonne per Google Sheets
├── website-qa/            # checklist per sito/Netlify
└── roadmap/               # piano di sviluppo
```

## Moduli del cervello

1. **Podere Brain** — dati fissi della tenuta, servizi, ville, capienza, tono.
2. **Website Agent** — sito, QA, Netlify, link, mobile, IT/EN.
3. **Booking Agent** — richieste clienti, preventivi, follow-up.
4. **Pre-Accounting Agent** — incassi, spese, fatture, report commercialista.
5. **Marketing Agent** — testi, social, wedding kit, brochure.
6. **Operations Agent** — check-in, check-out, pulizie, piscina, manutenzione.
7. **Revenue Agent** — prezzi, stagioni, margini, report.

## Regola di sicurezza

L'agente può **preparare e proporre**, ma non deve fare da solo azioni critiche come:

- inviare preventivi vincolanti;
- confermare prenotazioni;
- pubblicare modifiche live al sito;
- inviare documenti fiscali;
- gestire pagamenti;
- modificare prezzi ufficiali senza approvazione.

