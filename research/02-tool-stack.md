# Tool-Stack und Kosten (Entwurf)

Stand 2026-09-29. Preise stammen aus Websuche (Blogs/Vergleichsseiten), nicht direkt von den Anbietern. **Vor Kauf auf den offiziellen Seiten prüfen.** Preise meist in USD, teils Jahresrabatt.

## Übersicht
| Aufgabe | Tool | Preis (laut Recherche) | Empfehlung Pilot |
|---|---|---|---|
| KI-Zentrale, Skripte, Workflows | Claude | Pro ~$20, Max $100/$200, Team Standard $25 (Jahr $20), Premium $125 (Jahr $100) pro Nutzer | Mit Niels klären, siehe unten |
| Avatar-Video | HeyGen | Free $0 (wasserzeichen), Creator $29, Pro $49, Business $149 + $20/Seat. Avatar IV ca. 20 Credits/Min, Creator = 600 Credits ≈ 30 Min | Creator zum Testen |
| Stimme | ElevenLabs | Free, Starter $5, Creator $22, Pro $99. Instant Clone ab Starter, Professional Clone ab Creator | Starter, bei Bedarf Creator |
| Posting/Planung | Buffer (Free, unter ~$10), Metricool (Free, Starter ~$22–25/5 Marken), Later (~$18.75), Meta Business Suite (Free) | Meta Business Suite/Buffer Free zum Start |
| Recherche/Trends | Perplexity Pro (Niels hat es), Gemini Pro (Niels hat es), Claude Deep Research | vorhandene Zugänge nutzen |
| Schnitt | Freelancer (Fiverr/Upwork) oder KI-Schnitt (Claude-gestützt, DaVinci) | erst KI-Test, dann Freelancer |
| Ton | Adobe Enhance o. ä. | nur bei Bedarf |
| Website Praxis/Studio | Astro + Netlify | später |
| Speicher Rohmaterial | Drive/Dropbox/NAS | mit Niels klären |

## Claude-Lizenzmodell (Entscheidung nötig)
Niels zahlt Max $200 und will keinen zweiten Max kaufen.
- **A) Team-Plan:** Standard-Seats ($20–25) für Semih, Premium ($100–125) für Niels. Vorteil: geteilter Workspace, zentrale Abrechnung. Nachteil: Niels müsste seinen Max wechseln oder zusätzlich zahlen.
- **B) Getrennt:** Semih bleibt bei Pro, Niels behält Max. Günstig, aber Kontext/Skills liegen getrennt. Repo (GitHub) als gemeinsamer Speicher löst das teilweise.
- **C) Semih bekommt Max:** $100. Teuer, nur bei viel Nutzung.
Empfehlung: erst B mit Repo als geteiltem Kontext, nach dem Pilot A prüfen.

## Grobe Monatskosten (Pilot, 4 Wochen)
| Posten | Minimal | Realistisch |
|---|---|---|
| Claude (Semih Pro, Niels vorhanden) | ~$20 | ~$20 |
| HeyGen Creator | $29 | $29 |
| ElevenLabs Starter/Creator | $5 | $22 |
| Posting (Buffer/Meta Suite) | $0 | ~$10 |
| Freelancer-Schnitttest (5 Tests à ~30–60 €) | 0 | ~150–300 € einmalig |
| **Summe** | **~$54** | **~$81 + Freelancer** |

Zum Vergleich (Niels im Gespräch): Agentur ca. 1.000 €/Monat und mehr.

## Kostenfallen
- HeyGen: Credits laufen nach Avatarmodell unterschiedlich schnell weg, Zusatz-Avatare kosten extra ($29/Monat pro Slot).
- ElevenLabs: Zeichen-/Minutenlimits, Klon nur mit Nachweis der Rechte an der Stimme.
- Claude: Limits (Niels hat schon überzogen). Skills sparsam einsetzen, große Aufgaben planen.

## Schnittstellen
Claude ↔ GitHub (Skripte, Kontext), Claude ↔ Zapier (Automation, sofern gewünscht), Perspectiv ist Niels' bestehendes E-Mail-Tool (nur lesen). Gmail/Kalender bleiben aus.

## Offene Punkte
- Autopost-API-Zugänge (Meta/YouTube/TikTok) brauchen Zugriff auf Niels' Konten.
- Kennzeichnung KI-Inhalte (Shop noch offen).
