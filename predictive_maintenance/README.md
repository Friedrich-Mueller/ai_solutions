# Predictive Maintenance

### Aufgabe:
- Durchführung von einem Experiment, das untersucht, wie sich Anpassungen der Modellarchitektur auf die Performance bei Zeitreihendaten auswirken.

### Training einer KI auf Zeitreihendaten
- Geeigneten Datensatz auswählen zu den Themen Automatisierung (Merkmal oder Zustand erkennen) oder Predictive Maintenance
- Initiale KI-Architektur auf CNN-Basis auswählen und trainieren (ohne viel Optimierung)

### Hypothese / These aufstellen
- Hypothese aufstellen, mit welcher Architekturanpassung bessere Ergebnisse erzielt werden könnten
- Diese Hypothese muss Eigenschaften des Datensatzes oder Kontext vom Entwickler nutzen, die vor dem KI-Training bekannt sind, und damit Handlungsempfehlungen für die CNN-Architektur definieren.

### Beispiele für Hypothesen aus Bildanalyse
- Wenn es mehrere Eingangsbilder aus derselben Position gibt, die ein Mensch miteinander vergleichen würde, sollte man ein separates CNN nutzen, das nur die Bilddifferenz analysiert, welches mit dem ursprünglichen CNN am Ende konkateniert wird.
- Die Anzahl der notwendigen Filter in der ersten Convolution hängt sublinear mit der Anzahl der zu erkennenden Klassen zusammen.
- (Die eigene Hypothese sollte nicht nur diese beiden Beispiele auf Zeitreihendaten übertragen)

### Experimentelle Überprüfung
- Passe das zuvor trainierte CNN nach der Hypothese an
- Trainiere erneut die KI
- Prüfe, ob die Hypothese erfüllt ist

### Hilfsmittel
- Nutze alle Tools (inklusive allen KI-Tools)
- Du solltest trotzdem erklären können, warum du welche Entscheidungen getroffen hast
