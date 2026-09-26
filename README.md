# HeartGPT

**HeartGPT** ist ein strukturiertes KI-Werkzeug zum Sortieren von Gedanken.

Es wurde entwickelt, um zu verhindern, dass Overthinking durch immer neue hypothetische Szenarien, unbelegte Interpretationen, künstliche Unsicherheit oder wiederholte Rückversicherung weiter verstärkt wird.

HeartGPT versucht nicht, möglichst schnell zu beruhigen oder möglichst viele denkbare Erklärungen zu erzeugen. Stattdessen sollen vorhandene Informationen strukturiert, Fakten von Interpretationen getrennt und Schlussfolgerungen nach ihrer tatsächlichen Evidenz bewertet werden.

> **Aktuelle Version: HeartGPT / Overthinking Modus 2.3 Stable**  
> Erste öffentliche Stable-Version.

---

## Was HeartGPT anders macht

Normale KI-Gespräche können Overthinking unbeabsichtigt verstärken:

Auf eine Unsicherheit folgen mehrere denkbare Erklärungen, daraus entstehen neue Fragen und daraus wiederum neue Szenarien.

HeartGPT versucht genau diese Spirale zu vermeiden.

Unter anderem gilt:

- Fakten werden von Interpretationen, Hoffnungen und Befürchtungen getrennt.
- Eine theoretische Möglichkeit wird nicht automatisch wie eine wahrscheinliche Erklärung behandelt.
- Unbelegte „Es könnte auch …“-Szenarien sollen nicht endlos erweitert werden.
- Evidenzqualität ist wichtiger als die bloße Anzahl von Indizien.
- Wiederholte Fragen sind erlaubt.
- Neue Evidenz darf bestehende Einschätzungen verändern oder widerlegen.
- Bestehende Hypothesen dürfen gezielt angegriffen und falsifiziert werden.
- Korrigierte Informationen haben Vorrang.
- Eigene frühere Spekulationen des KI-Modells dürfen später nicht zu vermeintlichen Fakten werden.
- Ein interner Analyse-Anker hält längere Gespräche konsistent.
- Mehrere eigenständige Themen oder Alternativen können mit getrennten Unterankern analysiert werden.
- Die Reihenfolge, in der Alternativen genannt werden, darf die Analyse nicht beeinflussen.
- Fehlende Informationen über eine Alternative sind weder positive noch negative Evidenz.
- Bei realen Entscheidungen werden die Kriterien des Nutzers verwendet, nicht die Prioritäten des KI-Modells.
- Die endgültige Entscheidung bleibt beim Nutzer.

---

## Schnellstart

Du musst nicht lernen, besonders „richtig“ mit HeartGPT zu sprechen.

### 1. Neuen Chat öffnen

Öffne einen neuen Chat mit einem kompatiblen KI-Assistenten.

### 2. HeartGPT 2.3 Stable kopieren

Öffne:

**[HeartGPT 2.3 Stable](prompts/v2.3-stable/HeartGPT-2.3-Stable.md)**

Kopiere den vollständigen Prompt und füge ihn als erste Nachricht in den neuen Chat ein.

### 3. Thema normal beschreiben

Danach kannst du einfach schreiben, was dich beschäftigt – so, wie du es auch einer vertrauten Person erzählen würdest.

Zum Beispiel:

- „Ich zerdenke gerade, warum sie mir nicht antwortet.“
- „Ich habe eine Entscheidung getroffen, zweifle aber ständig wieder daran.“
- „Ich glaube, ich bin nicht gut genug für ihn. Kannst du das mit mir sortieren?“
- „Ich schwanke zwischen zwei Wegen. Bitte analysiere beide zunächst unabhängig voneinander.“
- „Versuche unsere aktuelle These zu zerstören. Welche Fakten sprechen wirklich dagegen?“
- „Hat diese neue Information etwas an unserer bisherigen Einschätzung verändert?“

Du musst deine Gedanken vorher nicht perfekt ordnen. Genau beim Sortieren soll HeartGPT helfen.

---

## Wiederholungen sind erlaubt

HeartGPT ist ausdrücklich nicht darauf ausgelegt, eine wiederholte Frage automatisch als störend oder unnötig zu behandeln.

Wenn du über einen anderen Gedankengang wieder bei derselben Frage ankommst, soll geprüft werden:

- Gibt es neue Evidenz?
- Gibt es ein neues Argument?
- Gibt es einen echten Widerspruch?
- Wird eine bisherige Annahme sinnvoll angegriffen?

Enthält die Frage nichts Neues, soll HeartGPT nicht einfach eine neue Erklärung erfinden, sondern erklären, warum sich die bisherige Einschätzung nicht verändert.

---

## Analyse-Anker und Multi-Anker

Bei längeren Gesprächen verwendet HeartGPT einen internen **Analyse-Anker**.

Dieser hält unter anderem fest:

- aktuelle Hauptthese
- stärkste Evidenz
- stärksten Gegenbeleg
- offene entscheidende Frage
- Falsifikationskriterium

Wenn mehrere eigenständige Themen, Personen, Wege oder Alternativen relevant werden, können getrennte **Unteranker** verwendet werden.

Dadurch soll verhindert werden, dass eine später eingeführte Alternative automatisch durch die bereits bestehende Geschichte interpretiert wird.

---

## Entscheidungshilfe

HeartGPT 2.3 kann bei realen Entscheidungen über das reine Sortieren von Gedanken hinausgehen.

Dabei soll HeartGPT:

1. die Kriterien, Bedürfnisse, Werte und Ziele des Nutzers herausarbeiten,
2. reale Alternativen anhand derselben Kriterien prüfen,
3. Evidenz nach ihrer Qualität gewichten,
4. Informationslücken sichtbar machen,
5. Alternativen fair miteinander vergleichen,
6. erkennbare Passungen transparent benennen,
7. relevante Gegenargumente und Unsicherheiten erhalten.

HeartGPT soll dabei keine persönlichen Lebensprioritäten für den Nutzer festlegen und keinen Befehl wie **„Wähle X“** geben.

**Die Entscheidung bleibt beim Nutzer.**

---

## Wenn ein Chat zu lang wird

Für lange Gespräche enthält HeartGPT einen eigenen Übergabe-Prompt:

**[HeartGPT 2.3 – Chat-Übergabe](prompts/v2.3-stable/Chat-Transfer.md)**

Damit kann der relevante Faktenstand, die Chronologie, der Analyse-Anker, geprüfte Hypothesen, Korrekturen und offene Fragen für einen neuen Chat strukturiert zusammengefasst werden.

Im neuen Chat wird zuerst HeartGPT 2.3 Stable eingefügt und anschließend die erzeugte Übergabe.

So kann die Analyse am bisherigen Stand fortgesetzt werden, ohne die gesamte Geschichte neu erzählen zu müssen.

---

## Wie HeartGPT entstanden ist

HeartGPT entstand nicht als geplantes Softwareprojekt.

Am Anfang stand mein eigenes Overthinking.

Über einen längeren Zeitraum nutzte ich ChatGPT, um Gedanken zu sortieren, Situationen zu analysieren und immer wieder neue Fragen zu prüfen.

Dabei zeigte sich: Je länger und komplexer ein Gespräch wurde, desto wichtiger wurden klare Regeln. Möglichkeiten wurden teils stärker gewichtet als die Fakten, alte Annahmen beeinflussten neue Gedanken und Informationen mussten von Interpretationen, Ängsten und Hoffnungen getrennt werden.

Also begann ich, Regeln dafür zu entwickeln.

Aus einzelnen Korrekturen wurden feste Prinzipien. Aus diesen Prinzipien wurde ein Prompt.

Am Ende eines sehr langen Chats entstand die Idee:

**Wenn mir diese Struktur hilft, könnte sie auch anderen helfen.**

Daraus wurde **HeartGPT**.

Ziel ist es nicht, jemandem zu sagen, was er fühlen, denken oder entscheiden soll.

HeartGPT soll dabei helfen, Gedanken zu sortieren, Fakten von Befürchtungen zu unterscheiden, Möglichkeiten fair zu betrachten und Entscheidungen anhand der eigenen Prioritäten klarer zu sehen.

**HeartGPT ist kostenlos**, weil es aus Overthinking entstanden ist und anderen helfen soll, darin nicht allein den Überblick behalten zu müssen.

---

## Grenzen und Sicherheit

HeartGPT ist ein Werkzeug zum Strukturieren von Gedanken.

Es ist **keine Therapie, keine medizinische Beratung und keine Garantie für richtige Entscheidungen**.

Nicht jedes Problem ist ein Overthinking-Problem.

Bei Gewalt, sexuellem Missbrauch, Selbstverletzung, Suizidgedanken, akuter Gefahr oder vergleichbar schweren Situationen dürfen reale Sicherheitsbedenken nicht als bloße Gedankenschleife behandelt oder wegargumentiert werden.

In solchen Situationen kann geeignete professionelle Unterstützung wichtiger sein als weitere Analyse.

HeartGPT soll außerdem weder den Nutzer noch andere Personen anhand einer Erzählung diagnostizieren.

---

## Praxistest und Feedback

HeartGPT 2.3 wurde durch gezielte Stresstests weiterentwickelt, unter anderem mit:

- spät eingeführten gleichwertigen Alternativen,
- mehreren parallelen Analyse-Strängen,
- Informationsasymmetrie,
- Reihenfolge-Bias,
- Themenwechseln und Reaktivierung bestehender Anker.

Diese Tests ersetzen keine breite Erprobung mit unabhängigen realen Nutzern.

Ein unerwartetes oder unangenehmes Ergebnis ist dabei nicht automatisch ein Fehler.

HeartGPT soll **nicht zu einem bestimmten Ergebnis führen**. Entscheidend ist, ob die Arbeitsweise sauber bleibt und die vorhandene Evidenz korrekt behandelt wird.

Feedback zu reproduzierbaren Problemen ist willkommen.

**Kontakt:** HeartGPT@web.de

---

## Version

### HeartGPT 2.3 Stable

Erste öffentlich veröffentlichte Stable-Version von HeartGPT.

Die vollständige Versionshistorie wird im `CHANGELOG.md` dokumentiert.

---

## Lizenz

HeartGPT soll kostenlos verfügbar sein.

Die genaue Open-Source-Lizenz und die Bedingungen für Weitergabe, Veränderung und kommerzielle Nutzung werden vor der ersten offiziellen Veröffentlichung festgelegt.

---

## Projektstatus

HeartGPT 2.3 Stable befindet sich in Vorbereitung auf die erste öffentliche Veröffentlichung.

Neben dem GitHub-Repository entsteht eine eigene **GitHub-Pages-Webseite** für HeartGPT.
