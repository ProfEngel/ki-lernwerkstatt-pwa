# KI-Lernwerkstatt

Eine interaktive Lernwerkstatt für BWL und künstliche Intelligenz: Begriffe verstehen, Kosten vergleichen und eigene Gedanken festhalten.

**[KI-Lernwerkstatt öffnen](https://profengel.github.io/ki-lernwerkstatt-pwa/)**

## Funktionen

- **Karteikarten:** Zehn vorbefüllte Karten zu KI-Grundlagen, Sicherheit und Wirtschaftlichkeit. Eigene Karten können ergänzt und als gelernt markiert werden.
- **ROI- und Token-Kostenrechner:** Vergleicht ein Frontier-Modell mit einem Mini- oder lokalen Modell anhand frei wählbarer Annahmen. Er zeigt monatliche Kosten, Ersparnis, Amortisationsdauer und den ROI nach zwölf Monaten. Die voreingestellten Preise sind Beispiele und keine aktuellen Preisangebote.
- **Notizen und Lernstand:** Daten bleiben im lokalen Browserspeicher. Eine JSON-Sicherung kann exportiert und auf einem anderen Gerät importiert werden; beim Import wird der dortige Stand ersetzt.
- **Offline nutzbar:** Nach dem ersten vollständigen Laden über HTTPS speichert ein Service Worker die App-Dateien für die weitere Nutzung ohne Internet. Browser können lokale Daten oder den Cache löschen; deshalb empfiehlt sich ein regelmäßiger Export.

## Installieren

Die [App](https://profengel.github.io/ki-lernwerkstatt-pwa/) im Browser öffnen. Auf iPhone oder iPad in Safari **Teilen → Zum Home-Bildschirm** wählen. Auf Android im Browsermenü **App installieren** oder **Zum Startbildschirm hinzufügen** auswählen. Auf unterstützten Desktop-Browsern lässt sich die App über das Installationssymbol oder das Browsermenü installieren.

## Lokal starten

Den Ordner mit einem lokalen Webserver öffnen, beispielsweise mit `python -m http.server` im Projektordner, und anschließend `http://localhost:8000/` aufrufen. Für Service Worker und Installation sind HTTPS oder localhost erforderlich; ein direktes Öffnen über `file://` reicht dafür nicht aus.

Die App verwendet keine externen Bibliotheken oder Tracker. Rechnerwerte sind vereinfachte Schätzungen; zusätzliche Kosten und Qualitätsunterschiede müssen bei Entscheidungen berücksichtigt werden. Hinweise zum EU AI Act ersetzen keine Rechtsberatung und sollten anhand des jeweils aktuellen Rechtsstands überprüft werden.
