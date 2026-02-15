# PROTOCOL — Inhoudelijke Toetsing & Audit (v1.0)

Dit protocol beschrijft hoe inhoudelijke toetsing en tegenspraak werkt voor **zzp-paradox v1.0**.

## 1) Canon en citeerregel
- De **canon** is de **PDF in de GitHub Release**.
- Citeer uitsluitend met **sectie (x.x.x)** en een **korte quote** uit de canon-PDF.
- NotebookLM/LLM-output is **geen bron** zonder sectie + quote uit de canon-PDF.

## 2) Scope van toetsing
Wel:
- Errata: feitelijke of tekstuele fouten.
- Counterarguments: tegenwerping op mechanisme-niveau.
- Vragen: verduidelijking over begrippen, scope of leesroute.
- Misquote/misframing: onjuiste externe weergave.

Niet:
- Geen beoordeling van individuele dossiers, contracten of arbeidsrelaties.
- Geen procesadvies, handhavingsadvies of “hoe win ik een zaak”.
- Geen discussie zonder bronanker.

## 3) Bronanker (vereist)
Een inhoudelijke reactie bevat minimaal:
- **Sectie (x.x.x)** uit de canon-PDF
- **Quote** (1–5 regels) exact overgenomen uit de canon-PDF
- Korte toelichting (max 10 regels)

Zonder bronanker is een reactie niet auditbaar en wordt deze niet inhoudelijk behandeld.

## 4) Eén ingang: Audit-formulier
Gebruik het audit-formulier via GitHub Issues:
- `Issues → New issue` (audit-formulier)

Kies in het formulier het type:
- Erratum
- Counterargument
- Vraag
- Misquote/misframing

## 5) Wat telt als een geldig counterargument?
Een geldig counterargument levert:
- Eén **schaalbaar, praktisch beslispunt vooraf** dat in complexe organisatiecontexten voorspelbaar werkt,
- En onderbouwt dit met sectie (x.x.x) + quote.

Een casus zonder mechanisme of zonder bronanker is onvoldoende.

## 6) Triage en uitkomst
Elke melding wordt gelabeld en krijgt één van deze uitkomsten:
- **Accepted (major/minor)**: leidt tot correctie of verduidelijking in een volgende release.
- **Clarify**: aanvullende informatie nodig (nog steeds met bronanker).
- **No-change**: geen wijziging (met korte motivatie).

## 7) Integriteit
- De canon-PDF is bevroren per release.
- Verifieer met `CHECKSUMS.txt` dat u de juiste versie gebruikt.