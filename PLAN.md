# Plan: KI-gestützter Social-Media-Aufbau für Dr. Niels Freitag

Stand: 2026-09-29 · Basis: Transkript Gespräch Niels × Semih (Plaud, 1h22)
Status: **Entwurf v0.1**. Offene Punkte stehen unten unter „Offene Fragen".

## 1. Was Niels will (aus dem Gespräch)

**Ziel:** Sichtbarkeit und Markenaufbau (Social Media) für Kosmetikstudio + Praxis + neuen Shop, mit minimalem Zeiteinsatz. „Minimaler Einsatz, maximaler Output." Alles KI-orchestriert, kein manuelles Wochen-Dreh-und-Schnitt-Modell.

**Positionierung:** kritischer, evidenzbasierter Arzt („glaub nicht jedem Hype"), Gegenpol zu den überwiegend jungen, weiblichen Beauty-Docs. Kontrovers in der Sache, nicht pöbelnd (kein „Oliver Pocher").

**Zielgruppe:** Kaufkräftige Frauen ca. 40+ (Köln, Rodenkirchen/Hahnwald, „Dame aus dem Golfclub"). Junge TikTok-Zielgruppe ist bewusst nicht Kern, außer bei Skincare-Produkten. Russischsprachiger Markt ist relevant (Shop ist DE/EN/RU).

**Kanäle:** YouTube (Long + Shorts), Instagram, Facebook (wichtig für die Klientel), TikTok nur als Nebenkanal. Später: Live Shopping (testen, nicht zuerst).

**Die „Maschine" (Zielbild):**
1. Trend- und Wettbewerbsradar (wöchentlich): virale Formate, Hooks, CTAs, Plattform, Länge; Asien-Trends → Prognose für DE.
2. Evidenz-Filter: Studienlage zu jedem Hype (Niels' Einordnung als Arzt).
3. Skript-Generator in Niels' Stimme → Niels prüft und gibt frei.
4. Produktion: HeyGen (Avatar) + ElevenLabs (Stimme) + B-Roll-Bibliothek + Captions + Schnitt (Stille, Füllwörter über Transkript).
5. Plattformspezifische Aufbereitung + Autopost (3–4 Posts/Tag ohne Niels' Zutun).
6. Auswertung: Reaktionen/Shares/Kommentare (nicht Follower), Wettbewerbsvergleich, organisch testen, Gewinner als Ads (Meta/TikTok).
7. Zusätzlich: Videopodcast (echt gedreht, Niels solo oder Zoom-Gäste) → Clips „verwursten".

**Leitprinzipien:** Pareto (erst Low-hanging-Fruits), Tool-Budget ist kein Blocker („alles billiger als der Mensch"), erst kleines Pilotprojekt (Kosmetikstudio + Behandlungen + Skincare + Shop), Ärztlicher Bereich später.

## 2. Leitplanken, die in jedes System müssen

- **Heilmittelwerbung/Kosmetik:** keine Heilversprechen, kein Wort „Akne" im Kosmetik-Kontext (stattdessen „Unreinheiten/Rötungen"), nie „Ich als Arzt empfehle …". Einblendung „Inhaber Kosmetikstudio Dr. Niels Freitag" statt Arzt-Aussage.
- **Bildrechte:** keine fremden Screenshots/Fälle kommentieren ohne Rechte (TikTok-Duett/Stitch nur dort).
- **KI-Kennzeichnung:** KI-Bilder/Avatare im Shop sind noch nicht gekennzeichnet (To-do bei Niels) → gilt auch für Avatar-Videos.
- **Voice & Freigabe:** Nichts geht ohne Niels' Freigabe live (Human-in-the-loop bei Skripten).
- **Secrets:** API-Keys nur als GitHub Secrets/1Password, nie im Klartext im Chat/Repo (Semih-Repo war öffentlich → Repo hier **privat** halten).
- **Backup/Versionierung:** alles in Git, Skills mit versioniert.

## 3. Rollen

| Wer | Rolle |
|---|---|
| Niels | Inhaber, Gesicht/Stimme, fachliche Freigabe, Kontext-Lieferant (Social-Media-Claude-Projekt, Shop-Daten) |
| Semih | KI-Orchestrator: Tools evaluieren, Workflows bauen, Freelancer-Suche, Auswertung. Pilotprojekt, Vergütung erst nach erstem Ergebnis besprechen |
| Claude | Recherche (Deep Search), Priorisierung nach Pareto, Skripte, Workflow-Bau |
| Freelancer (später) | Videoschnitt (Fiverr/Upwork), 5 testen, besten behalten |
| Marcel | Semiths Chef: **offen und transparent** halten, keine Konkurrenz zur Arbeitszeit |

## 4. Phasen (Vorschlag, Daten sind Platzhalter bis du Kapazität bestätigst)

### Phase 0 – Onboarding (diese Woche, bis zum Call nächste Woche)
- [ ] Transkript + Niels' „fetter Report"/Datenbasis aus dem Social-Media-Projekt einsammeln → `context/`
- [ ] Shop und Preisliste durchgehen (VIP-Club, Gold-Pakete, SIO-Skin-Health-Protokolle, 130 Produkte)
- [ ] Astro + Netlify kurz ansehen (Praxis-/Studio-Homepage folgt)
- [ ] Repo-Struktur, Leitplanken-Datei und Secrets-Konzept anlegen (dieses Repo)
- [ ] Klären: Team-/Lizenzmodell für Claude (Niels zahlt Pro Max, kein zweiter Plan)
- [ ] 1-Seiten-Vorschlag „Erstes Projekt" für den Call (Pareto-sortiert)

### Phase 1 – Fundament (Woche 1–2)
- [ ] Brand/Voice-Dokument: Tonalität, Positionierung, No-Gos, Beispiel-Hooks (Basis: Niels' Claude-Projekt)
- [ ] Wettbewerbs-/Vorbild-Analyse (Beauty-Docs DE, kritische Stimmen, US-Beispiele) → fehlt Niels laut Transkript
- [ ] B-Roll-Bibliothek planen (Tag-/Ordnerschema), Produktbilder (130) sammeln, Praxis-Alltagsclips
- [ ] Erster Kleindreh mit Niels (Anlass: neuer Shop, iPhone reicht, Ton über Adobe-KI-Enhance)
- [ ] KI-Schnitt-Test (Stille/Füllwörter/Untertitel/Einblendungen) am ersten Dreh

### Phase 2 – Pilot-Maschine, klein (Woche 3–6)
- [ ] Trend-Radar v1: wöchentlicher Report (Beauty/Skincare, Hooks, Formate, Evidenz-Check)
- [ ] Skript-Pipeline v1: Trend → Evidenz → Skript in Niels' Voice → Freigabe
- [ ] Avatar-Test: HeyGen + ElevenLabs (Foto/Video + Stimmprobe von Niels)
- [ ] Format-Mix testen: YouTube Shorts, Instagram Reels, Facebook, Karussells
- [ ] Freelancer-Test Schnitt: 5 Kandidaten, gleiches Rohmaterial
- [ ] Autopost-Anbindung (Tool offen)
- [ ] 4-Wochen-Test wie von Niels beschrieben, dann Auswertung

### Phase 3 – Auswerten und skalieren (ab Woche 7)
- [ ] Auswertung: Shares/Kommentare/Reaktionen, Vergleich mit Wettbewerb, Wachstumskurven (Ausgangswert dokumentieren!)
- [ ] Gewinner-Content → Ads (Meta/TikTok), Funnel zu VIP-Club/Shop
- [ ] Videopodcast-Format + Clip-Verwertung
- [ ] Optional: Live Shopping-Experiment, Übersetzungen (RU/EN), eigene Skincare-Brand-Vorbereitung
- [ ] Danach: ärztlicher Bereich (Körperform, Praxis) öffnen

## 5. Wo passiert was

| Was | Wo |
|---|---|
| Kontext, Pläne, Skills, Skripte, Prompts | dieses **privates** GitHub-Repo (`NielsFreitag`) |
| Secrets/API-Keys | GitHub Secrets bzw. 1Password (Niels) |
| Rohvideos/B-Roll (groß) | Cloud-Speicher (offen: Drive/Dropbox/…), im Repo nur Index/Tags |
| Termine/Follow-ups | Google Kalender + Gmail (via Claude) |
| E-Mail-Kampagnen Shop | bestehend bei Niels (Perspectiv), nur lesen/abgleichen |
| Wissensbasis (optional) | Obsidian-Vault, von Semih vorgeschlagen |

Vorgeschlagene Repo-Struktur:
```
context/      Transkripte, Niels' Report, Brand-Voice, Preisliste, Leitplanken
research/     Trend-Reports, Wettbewerb, Evidenz-Checks
scripts/      Videoskripte (Entwurf → freigegeben)
workflows/    Beschreibung der Pipelines, Prompts, Skills
assets/       Index der B-Roll-Bibliothek (Tags, Links)
analytics/    Wochenauswertungen
```

## 6. Workflow für jedes Kundengespräch (wiederverwendbar)
Plaud-Transkript → in `context/transcripts/` → Zusammenfassung, Entscheidungen, To-dos mit Owner/Datum → Plan aktualisieren → Follow-up-Mail-Entwurf (Versand nur nach Freigabe) → Kalendertermine vorschlagen.

## 7. Entscheidungen (Stand 2026-09-29)
- Kapazität Semih: ca. 10 Std/Woche, schwankend → Phasen sind Richtwerte, nicht Fixtermine.
- Lieferung für den Call nächste Woche: **alles** (Erstes-Projekt-Vorschlag, Trend-/Wettbewerbsradar, Tool-Stack + Kosten), jeweils als Kurzfassung in `research/`.
- Ablage: privates GitHub-Repo für die Arbeit + Zusammenfassung in Google Drive für Niels.
- Gmail/Kalender: Claude fasst nichts an (keine Entwürfe, keine Termine).

## 7b. Antworten von Semih (Update)
- Kunde: Dr. med. Niels Freitag, Kosmetikstudio (Pilot zuerst Studio + Skincare + Shop).
- Umfang: Pilotprojekt.
- Rolle: Semih macht alles selbst, allein, in Absprache mit Niels.
- Kanäle: alle (Priorität laut Gespräch: YouTube, Instagram, Facebook; TikTok Nebenkanal). Es gibt **keine Brand-Guidelines** → Phase 1 muss sie erstellen; Rest muss Semih bei Niels erfragen.
- Tools: alle dürfen genutzt werden (Kosten trägt laut Niels das Projekt, Budget wird gemeinsam festgelegt).
- Ablage: Repo ist die Hauptablage (Drive-Zusammenfassung nur bei Bedarf).
- Automatisierung: so viel wie möglich, aber Gmail/Kalender bleiben tabu und Skripte brauchen Niels' Freigabe.
- Automatischer Transkript-Workflow (Abschnitt 6): nicht gewünscht, nur auf Zuruf.

### Fragen, die Semih bei Niels klären muss
- Brand-Guidelines: Farben, Logo, Schriften, Tonalität, Do/Don't
- Zugang zu Social-Media-Claude-Projekt und Report
- Budget, Tool-Accounts und Lizenzmodell (Team statt zweitem Pro Max)
- Account-Handles und Zugänge der Kanäle
- Zustimmung Avatar/Stimmklon
- Rahmen/Vergütung nach dem ersten Ergebnis und Absprache mit Marcel

## 8. Offene Fragen
- Ab wann/mit welchem Datum ist der Call mit Niels genau?
- Läuft das als Nebenjob, Werkstudent (geht wegen dualem Studium nicht) oder auf Projektbasis? Vergütung: erst nach erstem Ergebnis.
- Ist Marcel schon informiert, dass du für Niels arbeitest?
- Lizenzmodell Claude: Team-Plan oder Nutzung über Niels' Pro Max?
- Zugang zu Niels' Social-Media-Claude-Projekt / Report (Format, Übergabe).
- Aktueller Stand der Kanäle (Handles, Follower, letzter Post) für die Ausgangskurve.
- Erlaubt Niels Voice-/Gesichtsklon (HeyGen/ElevenLabs) schriftlich, und wer hält die Rechte?
