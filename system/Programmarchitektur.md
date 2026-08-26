# Programmarchitektur – Modulares Entscheidungssystem

**Stand:** 26. August 2026  
**Status:** Arbeitsmodell für die fachliche Weiterentwicklung – noch nicht technisch spezifiziert und noch nicht final validiert  
**Zweck:** Diese Datei soll einen neuen Chat bzw. Live-1 in die Lage versetzen, unmittelbar an der Programmarchitektur weiterzuarbeiten.

---

## 1. Strategischer Ausgangspunkt

Das Unternehmen entwickelt ein **KI-gestütztes, modulares Entscheidungssystem für Frauen mit Zusatz-Einkommenswunsch**.

Die Eingangstür lautet vorläufig:

> **Du möchtest zusätzlich Geld verdienen und weißt noch nicht womit.**

Die KI entscheidet nicht für die Frau. Sie hilft ihr, ihre reale Lebenssituation zu verstehen, ein persönliches Bewertungsraster zu entwickeln, verschiedene Wege realistisch zu prüfen und anschließend die passende Umsetzung zu wählen.

Mögliche Ergebnisse der ersten großen Entscheidung sind unter anderem:

- zusätzliche Anstellung / Nebenjob
- Mischmodell
- Selbstständigkeit
- „jetzt noch nicht“

Die verbindliche strategische Grundlage steht in `strategie/Quelle-der-Wahrheit-2.1.md`.

Die fachliche Forschungsgrundlage steht in:

- `forschung/Forschungsbericht-1.0-Bewertungsraster.md`
- `forschung/Pruefung-Forschungsbericht-1.0.md`

---

## 2. Wichtige Erkenntnis: Die drei Ebenen sind noch nicht das Programm

Die aktuell entwickelte kleinste Strecke mit den drei Ebenen

1. Was ein Weg nicht verletzen darf
2. Wie Arbeit für die Frau sein soll
3. Wie der Weg wirklich ist

ist **nicht das gesamte Programm**.

Sie bildet das Herzstück des **ersten Entscheidungsmoduls**.

Sie soll eine Frau von

> „Ich möchte zusätzlich Geld verdienen und weiß nicht womit.“

zu einer begründeten ersten Richtung führen.

Das eigentliche modulare Programm beginnt davor mit der realen Ausgangslage und verzweigt danach abhängig vom Ergebnis.

---

# 3. Vorgeschlagene Gesamtarchitektur

Das Programm soll **kein linearer Riesenkurs** werden, den jede Frau vollständig durchlaufen muss.

Grundprinzip:

> **Gemeinsamer Kern → Entscheidung → passende Abzweigung → nur die Module, die diese Frau jetzt braucht.**

Die vorgeschlagene Gesamtarchitektur besteht aus drei großen Teilen:

## TEIL A – KLARHEIT

**Wo stehe ich? → Wie will ich arbeiten? → Welche Grundrichtung passt?**

Danach kann eine Frau bereits aussteigen, wenn ihre Frage beantwortet ist.

## TEIL B – MÖGLICHKEIT

Nur wenn ein eigener Einkommensweg / Selbstständigkeit / Mischmodell vertieft werden soll:

**Was bringe ich mit? → Wofür könnte jemand bezahlen? → Welche konkreten Modelle passen? → Realität testen → entscheiden.**

## TEIL C – UMSETZUNG

Nur die benötigten Bausteine:

**Angebot → Markt → Preis → Kundengewinnung → Sichtbarkeit → Technik → Planung usw.**

Ilse begleitet quer durch alle Teile. Sie ist **kein eigenes Modul**.

---

# 4. TEIL A – KLARHEIT

## Modul 1 – Wo stehe ich wirklich?

Hier entsteht ein realistisches Bild der Ausgangslage.

Mögliche Inhalte:

- Geldbedarf
- Dringlichkeit
- verfügbare Zeit
- Investitionsspielraum
- bestehender Job
- Lebenssituation
- Verpflichtungen
- praktische Grenzen
- echte No-Gos

Die Frau soll nicht in Idealbildern antworten, sondern in ihrer tatsächlichen Realität.

**Ergebnis:**

> Die Frau kennt ihren wirtschaftlichen und persönlichen Handlungsspielraum.

Forschungsbezug im Hintergrund: Life Design, Psychology of Working, Super, harte Grenzen / Nicht-Kompensierbarkeit.

Wichtig: Die Teilnehmerin muss diese Modelle nicht lernen. Die Forschung wirkt hinter den Kulissen in der Qualität der Fragen.

---

## Modul 2 – Wie soll Arbeit in meinem Leben aussehen?

Hier entsteht das persönliche Bewertungsraster.

Nicht zuerst:

> „Was ist dein Traumjob?“

Sondern:

> „Wie möchtest du eigentlich arbeiten und leben?“

Mögliche Themen sind zum Beispiel:

- Sicherheit
- Freiheit / Selbstbestimmung
- Flexibilität
- Planbarkeit
- Menschenkontakt
- allein oder im Team arbeiten
- Sinn / Beitrag
- Abwechslung
- Sichtbarkeit
- Verantwortung
- Ortsbindung
- Verkauf
- Arbeitsrhythmus

Entscheidend ist der Übersetzungsschritt:

> **Woran würdest du an einem normalen Dienstag merken, dass dieses Kriterium erfüllt ist?**

Beispiel:

- „Selbstbestimmung ist mir wichtig“ = noch nicht prüfbar
- „Ich möchte meine Arbeitszeiten weitgehend selbst festlegen können“ = prüfbar

Danach werden die wirklich persönlichen Kriterien gewichtet.

**Ergebnis:**

> Ein kleines persönliches Raster aus konkreten Kriterien plus harte Grenzen / No-Gos.

Noch nicht entschieden ist, welche Gewichtungsmethode langfristig am besten funktioniert. 1–10 ist ein Pilotvorschlag, keine endgültige Festlegung.

---

## Modul 3 – Welche Grundwege kommen für mich überhaupt infrage?

Jetzt erst werden grobe Erwerbsrichtungen betrachtet, zum Beispiel:

- zusätzliche Anstellung
- Nebenjob
- Mischmodell
- Selbstständigkeit
- jetzt noch nicht

Ilse strukturiert oder recherchiert für diese Wege unter anderem:

- wie schnell Einkommen entstehen kann
- typischer Investitionsbedarf
- Sicherheit / Planbarkeit
- Risiko
- typische Anforderungen
- grundsätzliche Arbeitsweise

Anschließend werden die Wege gegen harte Grenzen und das persönliche Raster gehalten.

**Ergebnis:**

> Eine begründete erste Richtungsentscheidung – noch nicht zwingend eine konkrete Geschäftsidee.

Wichtig: Die Forschung hat gezeigt, dass harte Grenzen nicht durch andere Vorteile kompensiert werden dürfen.

Beispiel:

> Wenn eine Frau in acht Wochen 800 Euro benötigt, darf ein Weg, der realistisch erst nach zwölf Monaten Geld bringt, nicht „gewinnen“, nur weil er kreativ, ortsunabhängig und sinnvoll ist.

---

# 5. Ein wichtiger offener Punkt im ersten Entscheidungsteil

„Selbstständigkeit“ oder „Nebenjob“ hat noch keinen eindeutigen normalen Dienstag.

Eine selbstständige Texterin lebt einen anderen Alltag als eine Etsy-Händlerin oder Beraterin. Ein Remote-Nebenjob unterscheidet sich stark vom Minijob im Einzelhandel.

Deshalb muss im Pilot getestet werden, wann aus einer groben Erwerbsform **ein konkreter Kandidat** werden muss, bevor ein seriöser Alltagstest möglich ist.

Noch nicht vorschnell als zusätzliche feste Frage spezifizieren.

---

# 6. Verzweigung nach Teil A

Nicht jede Frau geht automatisch weiter.

## Beispiel: Nebenjob passt

Eine Frau kommt zu dem Ergebnis:

> „Ein Nebenjob ist momentan die sinnvollste Lösung.“

Dann braucht sie **nicht** automatisch Positionierung, Instagram, Landingpage oder Geschäftsmodell.

Mögliche nächste Hilfe kann sein:

- Welche Art von Nebenjob passt zu meinem Raster?
- Wo suche ich sinnvoll?
- Welche Bedingungen prüfe ich bei Stellenangeboten?

Wo gute kostenlose oder staatliche Angebote existieren, sollen sie verlinkt statt nachgebaut werden.

## Beispiel: Selbstständigkeit / eigener Weg passt

Dann öffnet sich Teil B.

---

# 7. TEIL B – MÖGLICHKEIT

## Modul 4 – Mein wirtschaftliches Rohmaterial

Hier werden die besten Teile aus „Die Ideenfinderin“ / „Dein Herzensthema“ neu eingeordnet.

Leitfrage:

> **Was bringe ich bereits mit, aus dem wirtschaftlicher Wert entstehen könnte?**

Mögliche Inhalte:

- Berufserfahrung
- Lebens- und Lernerfahrungen
- nachweisbare Fähigkeiten
- informell erworbene Fähigkeiten
- Fachwissen
- Themen und Interessen
- Dinge, nach denen andere die Frau bereits fragen
- energisierende Tätigkeiten
- Kontakte / Netzwerke
- vorhandene Ressourcen

Wichtige Forschungsregel:

> **Fähigkeit ≠ Wunsch ≠ Selbstvertrauen.**

Beispiel:

„Du kannst gut organisieren“ bedeutet noch nicht „Du möchtest mit Organisation Geld verdienen“.

**Ergebnis:**

> Eine Landkarte des vorhandenen wirtschaftlichen Rohmaterials.

Diese Informationen sind überwiegend Ressourcen- und Passungsinformationen – nicht automatisch Bewertungskriterien.

---

## Modul 5 – Von „Ich kann etwas“ zu „Dafür bezahlt jemand“

Hier liegt eine zentrale Brücke des neuen Systems.

Nicht bei Stärken oder Interessen stehen bleiben.

Fragen:

- Wem hilft dieses Wissen oder Können?
- Welches Problem löst es?
- Welches Ergebnis kann dadurch entstehen?
- In welcher Form könnte jemand dafür bezahlen?

Beispiel:

> „Ich kann komplizierte Dinge gut erklären.“

Daraus könnten unterschiedliche wirtschaftliche Formen entstehen:

- Unterricht
- Beratung
- Freelancing
- Workshop
- Content
- digitales Produkt
- Buch
- Schulung
- Kundenservice

**Ergebnis:**

> Mehrere wirtschaftlich plausible Kandidaten – nicht vorschnell eine einzige „Herzensidee“.

---

## Modul 6 – Welches Geschäftsmodell passt dazu – und zu mir?

Ein Thema und ein Geschäftsmodell sind nicht dasselbe.

Dass eine Frau ein Thema liebt, sagt noch nicht, **wie sie damit Geld verdienen möchte**.

Mögliche Geschäftsmodelle:

- Dienstleistung
- Beratung
- Freelancing
- Gruppenangebot
- digitales Produkt
- physisches Produkt
- lokales Angebot
- Plattformgeschäft
- Empfehlungsmarketing
- weitere Modelle

Das bereits entwickelte persönliche Raster wird hier **wiederverwendet**.

Beispiel:

Eine Beratung kann fachlich hervorragend passen, aber nicht zu einer Frau, die keine regelmäßigen Kundentermine möchte.

**Ergebnis:**

> 1–3 konkrete, plausible Einkommensmodelle.

---

## Modul 7 – Realität statt Kopfkino

Hier werden konkrete Kandidaten mit realen Informationen geprüft.

Für jeden ernsthaften Kandidaten wird geklärt:

- Was muss tatsächlich getan werden?
- Wie entstehen Kundinnen / Aufträge / Einnahmen?
- Was kostet der Start?
- Wie lange dauert es realistisch bis zu ersten Einnahmen?
- Was muss gelernt werden?
- Welche administrativen Aufgaben fallen an?
- Wie sieht eine normale Woche aus?

Wo möglich gilt:

> **Kleiner Test statt großer Entscheidung.**

Mögliche Prototypen:

- mit einer Person sprechen, die den Weg bereits geht
- einen Mini-Auftrag übernehmen
- ein Angebot testweise formulieren
- einen Probetag machen
- potenzielle Kundinnen befragen

**Ergebnis:**

> Erfahrung und reale Informationen statt Fantasie über den Weg.

Forschungsbezug im Hintergrund: Designing Your Life, Entscheidungspsychologie, Alltagstest.

---

## Modul 8 – Meine Entscheidung

Erst jetzt erfolgt bei konkreten Kandidaten der vertiefte Vergleich.

Das Ergebnis soll ausdrücklich **nicht** so klingen:

> „Option B hat 82,4 % Match und gewinnt.“

Sondern beispielsweise:

> „A und B erfüllen beide deine harten Bedingungen. A passt stärker zu deinem Wunsch nach Sicherheit. B erfüllt deine Flexibilität besser. Für B wissen wir über die tatsächliche Kundennachfrage noch zu wenig. Deshalb wäre vor einer Entscheidung ein kleiner Markttest sinnvoll.“

Oder:

> „Keine der derzeit geprüften Möglichkeiten erfüllt deine Mindestbedingungen.“

Dann ist „jetzt noch nicht“ ein vollwertiges Ergebnis.

**Ergebnis:**

> Eine begründete Entscheidung oder ein klar definierter nächster Test.

Ilse soll Unsicherheit sichtbar machen und nicht künstlich in Gewissheit verwandeln.

---

# 8. TEIL C – UMSETZUNG

Nach einer Entscheidung beginnt der größere modulare Umsetzungsbereich.

Nicht jede Frau braucht alle Bausteine.

Mögliche spätere Umsetzungsbausteine:

- Angebot
- Positionierung
- Zielgruppe / Kundin
- Marktprüfung
- Preis
- Einnahmemodell
- Verkauf / Kundengewinnung
- Sichtbarkeit
- Social Media
- Content
- Landingpage / Website
- digitale Produkte
- Plattformwahl
- Organisation und Zeit
- Finanzen / Administration
- KI-Unterstützung
- Technik
- 90-Tage-Planung / Umsetzung

Grundsatz:

> **Jeder Baustein muss ein echtes, klar umrissenes Problem lösen und für sich ein brauchbares Ergebnis liefern.**

Die Module dürfen nicht künstlich zerstückelt werden.

---

# 9. „Mein kleiner Laden“ innerhalb der Architektur

„Mein kleiner Laden“ bleibt ein möglicher konkreter Umsetzungspfad innerhalb des Gesamtsystems.

Er ist **nicht das Ziel der Entscheidungsstrecke**.

Wenn eine Frau über ihr eigenes Raster und die reale Prüfung zu dem Ergebnis kommt, dass Empfehlungsmarketing / Lifeplus / Petra zu ihr passen, kann „Mein kleiner Laden“ ihr Umsetzungsweg sein.

Die Ausbildung und Begleitung dort bleibt für Petras Lifeplus-Downline kostenlos.

---

# 10. Rolle von Ilse

Ilse ist kein eigenes Programm-Modul.

Sie begleitet quer durch die gesamte Architektur.

Ihre mögliche Rolle:

- Kontext der Frau behalten
- gute Fragen stellen
- Antworten strukturieren
- harte Grenzen von Präferenzen unterscheiden
- Werte in konkrete Kriterien übersetzen
- Widersprüche sichtbar machen
- recherchieren bzw. Recherche unterstützen
- Wege vergleichen
- Unsicherheit benennen
- das persönliche Raster später erneut verwenden
- nächste passende Module öffnen bzw. empfehlen

Grundsatz:

> **Ilse hilft denken. Die Frau entscheidet.**

Vier Aussagen dürfen niemals vermischt werden:

1. Ich will das.
2. Ich kann das.
3. Ich traue mir das zu.
4. Unter meinen jetzigen Bedingungen geht das.

---

# 11. Rolle der Forschung

Die Teilnehmerin soll keinen Kurs über Schein, Schwartz, Deci & Ryan, Career Construction, MCDA, RIASEC oder Entscheidungspsychologie bekommen.

Die Forschung gehört **hinter die Kulissen**.

Sie sorgt dafür, dass Ilse gute Fragen stellt, typische Denkfehler vermeidet und das Raster fachlich sauber konstruiert.

Beispiel:

Die Teilnehmerin erlebt:

> „Was bedeutet Sicherheit für dich ganz konkret?“

Sie muss nicht hören:

> „Nach Schwartz und der Selbstbestimmungstheorie …“

Das Programm soll **leicht wirken und fachlich tief sein**.

---

# 12. Wichtige Bauprinzipien aus der Forschung

Diese Prinzipien sollen bei der Weiterentwicklung erhalten bleiben:

### 1. Harte Grenzen sind nicht kompensierbar

Ein Weg, der eine echte Mindestbedingung verletzt, darf nicht durch andere Pluspunkte gewinnen.

### 2. Fähigkeiten und Stärken sind nicht automatisch Kriterien

Sie beantworten vor allem:

> „Was bringe ich mit?“

nicht automatisch:

> „Wie muss mein Weg aussehen?“

### 3. Werte müssen übersetzt werden

„Sicherheit ist mir wichtig“ ist noch kein prüfbares Kriterium.

Aus einem Wert können unterschiedliche Dinge entstehen:

- harte Grenze
- gewichtbare Präferenz

### 4. Die Option muss selbst untersucht werden

Ilse kann keinen Weg seriös bewerten, den sie nicht kennt.

### 5. Keine Scheingenauigkeit

Keine pseudowissenschaftlichen Prozent-Matches wie „82,4 % passend“.

### 6. Unsicherheit darf als Unsicherheit stehen bleiben

Ein gutes Ergebnis kann sein:

> „Zwei Wege passen. Eine entscheidende Information fehlt noch.“

### 7. Das Raster darf beim Alltagstest lernen

Neue No-Gos oder Kriterien können erst sichtbar werden, wenn die Frau einen konkreten Alltag vor sich sieht.

---

# 13. Was noch NICHT entschieden ist

Diese Punkte sind Arbeitsmodelle und müssen durch Pilotierung geprüft werden:

- genaue Anzahl der Kriterien im persönlichen Raster
- endgültige Gewichtungsmethode
- wann grobe Erwerbsformen konkretisiert werden müssen
- welche Module tatsächlich gebraucht und bezahlt werden
- genaue Reihenfolge in Teil B
- Umfang einer möglichen 90-Tage-Umsetzungsstrecke
- welche Aufgaben Ilse selbst übernimmt und wofür Spezialagenten nötig sind
- welche Bestandteile später technisch automatisiert werden

Keine dieser offenen Fragen rechtfertigt derzeit vorschnelles Bauen.

---

# 14. Zusammenhang mit den bisherigen 14 Stationen

Die bisherigen 14 Stationen aus „Die Ideenfinderin“ / „Dein Herzensthema“ werden **nicht verworfen**.

Sie sollen jetzt gegen diese neue Architektur geprüft werden.

Für jede bisherige Station ist zu entscheiden:

- **bleibt**
- **wird geteilt**
- **wird verschoben**
- **wird optional**
- **entfällt**

Arbeitshypothese:

Viele Inhalte aus Vita, Fähigkeiten, Interessen und Themen werden in **Teil B** wieder auftauchen.

Viele Inhalte aus Positionierung, Social Media, Content, Landingpage, KI und Planung werden in **Teil C** wieder auftauchen.

Sie sollen aber nicht länger Pflichtreise für jede Frau sein.

---

# 15. Nächster empfohlener Arbeitsschritt für Live-1

**Noch keine technische Spezifikation bauen.**

Als Nächstes:

1. die bestehenden 14 Stationen vollständig heranziehen
2. jede Station gegen diese Architektur prüfen
3. für jede Station markieren: bleibt / teilen / verschieben / optional / entfällt
4. prüfen, welche Inhalte in Teil A, B oder C gehören
5. Lücken sichtbar machen
6. danach die kleinste Strecke mit Petra als Pilotin 0 weiter testen

Das Ziel des nächsten Gesprächs ist **nicht**, sofort ein endgültiges Programm zu bauen, sondern herauszufinden, welche bereits vorhandenen Inhalte in der neuen modularen Architektur tatsächlich gebraucht werden.

---

# 16. Kurzfassung für einen neuen Chat

> Wir entwickeln kein lineares Kursprogramm, sondern ein modulares Entscheidungssystem. Die drei Ebenen „harte Grenzen – gewünschte Arbeitsweise – Realität des Weges“ sind nur das Herzstück des ersten Entscheidungsmoduls. Die aktuelle Arbeitsarchitektur besteht aus Teil A Klarheit, Teil B Möglichkeit und Teil C Umsetzung. Teil A führt von Lebensrealität und persönlichem Bewertungsraster zu einer ersten Erwerbsrichtung. Nur Frauen, die einen eigenen Einkommensweg vertiefen wollen, gehen in Teil B: wirtschaftliches Rohmaterial → Bezahlbarkeit → Geschäftsmodell → Realitätstest → Entscheidung. Teil C enthält nur die für den gewählten Weg nötigen Umsetzungsbausteine. Ilse begleitet quer durch alle Teile und entscheidet nicht für die Frau. Die Forschung bleibt Hintergrundlandkarte, nicht Fragebogen. Als nächstes sollen die vorhandenen 14 Stationen aus „Die Ideenfinderin“ / „Dein Herzensthema“ gegen diese Architektur geprüft und als bleibt / teilen / verschieben / optional / entfällt eingeordnet werden.
