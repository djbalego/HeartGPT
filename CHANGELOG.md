# HeartGPT – Changelog

In diesem Changelog werden die öffentlich veröffentlichten Versionen von HeartGPT dokumentiert.

HeartGPT 2.3 Stable ist die erste öffentliche Version. Frühere Entwicklungsstände wurden nicht öffentlich veröffentlicht und werden deshalb nicht als öffentliche Releases geführt.

---
## [2.3.1] – Stable (08.10.2026)

### Neutralitätskorrektur

HeartGPT 2.3.1 erweitert die bestehende Version 2.3 um zusätzliche methodische Schutzmechanismen für die neutrale Analyse mehrerer Entscheidungswege.

**Verbessert:**
- Zusätzliche Kontrolle von Reihenfolge- und Analyse-Anker-Bias.
- Strengere Behandlung unterschiedlich umfangreicher Informationen.
- Vermeidung vorzeitiger Gesamtpassungsbewertungen.
- Keine zusätzliche Gewichtung durch wiederholte Zwischenbilanzen.
- Abschlussregel für ausreichend untersuchte Entscheidungskriterien.
- Verpflichtende methodische Kontrolle vor übergreifenden Passungsbewertungen.
- Deutlichere Trennung zwischen belegten Einzelunterschieden und langfristiger Gesamtpassung.

### Neue Dateien

- `HeartGPT-2.3.1.md` – vollständiger Stable-Prompt.
- `HeartGPT-2.3-auf-2.3.1-Update.md` – Update-Prompt für bereits laufende Chats.
- `Chat-Transfer.md` – aktualisierte Chat-Übergabe für Version 2.3.1.

### Kompatibilität

Die grundlegende Struktur von HeartGPT bleibt erhalten.

Bestehende HeartGPT-2.3-Chats können mithilfe des Update-Prompts auf 2.3.1 umgestellt werden. Dabei werden bisherige Nutzerinformationen beibehalten und frühere Modellbewertungen methodisch neu geprüft.

### Validierung

Die Neutralitätskorrektur wurde anhand fiktiver Entscheidungsszenarien mit vertauschten Wegbezeichnungen und gegensätzlichen emotionalen Ausgangslagen praktisch getestet.

Die Tests zeigten eine verbesserte Trennung zwischen gegenwärtiger emotionaler Orientierung und langfristiger Beziehungspassung. Einzelne verbleibende Risiken durch wiederholte Zwischenbewertungen wurden identifiziert und durch zusätzliche Regeln adressiert.

Eine vollständige Bias-Freiheit wird nicht beansprucht.

## 2.3 Stable

**Erste öffentliche Stable-Version von HeartGPT**

### Grundprinzipien

- Konsequente Trennung von Fakten, Interpretationen, Befürchtungen, Hoffnungen, Hypothesen und Schlussfolgerungen.
- Möglichkeit und Wahrscheinlichkeit werden getrennt behandelt.
- Schutz vor unbelegter Szenario-Explosion.
- Keine künstliche 50:50-Unsicherheit.
- Keine künstliche Eindeutigkeit bei tatsächlich unklarer Evidenzlage.
- Evidenzqualität wird höher gewichtet als Evidenzmenge.
- Wiederholte Fragen des Nutzers bleiben ausdrücklich erlaubt.
- Produktive Reanalyse, Gegenargumente und Falsifikation werden unterstützt.
- Neue Evidenz kann bestehende Hypothesen verändern oder widerlegen.
- Korrekturen des Nutzers haben Vorrang.
- Frühere Spekulationen oder Fehler des KI-Modells dürfen nicht zu vermeintlichen Fakten werden.

### Analyse-Anker

- Fortlaufender interner Analyse-Anker für längere Gespräche.
- Dokumentation von Hauptthese, stärkster Evidenz, stärkstem Gegenbeleg, offener entscheidender Frage und Falsifikationskriterium.
- Anker-Reset bei relevanter neuer Evidenz.
- Schutz davor, dass emotionale Intensität mit Evidenzstärke verwechselt wird.

### Multi-Anker

- Getrennte Unteranker für eigenständige Probleme, Personen, Wege oder Handlungsalternativen.
- Unabhängige Analyse neuer Stränge.
- Möglichkeit eines übergeordneten Gesamtankers.
- Belegte Wechselwirkungen zwischen Unterankern werden separat behandelt.

### Schutz vor Analyse-Bias

- Schutz vor Reihenfolge-Bias.
- Die zuerst genannte Alternative erhält keinen automatischen Vorrang.
- Schutz vor Informationsasymmetrie.
- Fehlende negative Information wird nicht als positive Evidenz behandelt.
- Fehlende positive Information wird nicht als negative Evidenz behandelt.
- Alternativen werden zunächst unabhängig und anschließend gemeinsam geprüft.
- Schutz vor verdeckter Richtungsvorgabe durch die Formulierung von Fragen oder Empfehlungen.

### Informationsgewinnung

- Prüfung, ob eine entscheidende Informationslücke durch eine angemessene reale Handlung geschlossen werden kann.
- Reale Informationsgewinnung wird gegenüber weiterer Spekulation bevorzugt, wenn sie sinnvoll, relevant und angemessen ist.
- Die Stop-Regel beendet spekulative Gedankenschleifen, ohne sinnvolle Informationsgewinnung zu verhindern.

### Anker-Routing

- Bereits bestehende Themenanker können nach einem Themenwechsel gezielt reaktiviert werden.
- Neue Informationen werden dem tatsächlich betroffenen Anker zugeordnet und nicht automatisch dem zuletzt aktiven Thema.
- Inaktive Anker verlieren nicht allein durch Zeit oder Themenwechsel ihre Gültigkeit.
- Mehrdeutige Zuordnungen sollen geklärt statt automatisch angenommen werden.

### Evidenzbasierte Entscheidungshilfe

- Entscheidungskriterien, Bedürfnisse, Werte und Ziele werden aus den Aussagen des Nutzers abgeleitet.
- Reale Alternativen werden anhand derselben relevanten Kriterien geprüft.
- Pro- und Contra-Punkte werden nach Evidenzqualität statt bloßer Anzahl bewertet.
- Informationsasymmetrie wird bei Vergleichen berücksichtigt.
- Erkennbare Passungen können anhand der vom Nutzer selbst gesetzten Kriterien transparent benannt werden.
- Zielkonflikte und verbleibende Unsicherheiten werden sichtbar gemacht.
- HeartGPT gibt bei persönlichen Lebensentscheidungen keinen Befehl wie „Wähle X“.
- Die endgültige Entscheidung bleibt beim Nutzer.

### Sicherheit und Grenzen

- Keine Ferndiagnosen des Nutzers oder anderer Personen.
- Reale Gefahren dürfen nicht als Overthinking wegargumentiert werden.
- Sicherheitsgrenze für Gewalt, sexuellen Missbrauch, Selbstverletzung, Suizidgedanken, akute Gefahr und vergleichbar schwere Situationen.
- HeartGPT ist ein Werkzeug zum Strukturieren von Gedanken und keine Therapie oder Garantie für richtige Entscheidungen.

### Chat-Übergabe

- Übergabe-System für sehr lange Chats.
- Relevante Fakten, Chronologie, Analyse-Anker, geprüfte Hypothesen, Korrekturen, Informationslücken und offene Fragen können strukturiert in einen neuen Chat übertragen werden.

---

© 2026 Dirk Baur – HeartGPT  
Licensed under CC BY-NC-ND 4.0.
