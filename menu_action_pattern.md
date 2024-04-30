# Menu Action Pattern

Um dieses Muster zu verwenden, sollte Ihre Eingabeaufforderung die folgenden grundlegenden kontextbezogenen Aussagen machen:

- Wann immer ich tippe: X, werden Sie Y tun.
- (Optional, bieten Sie zusätzliche Menüpunkte an) Immer wenn ich Z tippe, werden Sie Q tun.
- Am Ende werden Sie mich nach der nächsten Aktion fragen.

Sie müssen "X" durch ein geeignetes Muster ersetzen, z.B. "\<Aufgabenzeit\> schätzen" oder "Lebensmittel hinzufügen". Anschließend müssen Sie eine Aktion angeben, die der Menüpunkt auslösen soll, z.B. "FOOD zu meiner Einkaufsliste hinzufügen und meine geschätzte Lebensmittelrechnung aktualisieren".

Beispiele:

- Immer wenn ich eingebe: "FOOD hinzufügen", werden Sie FOOD zu meiner Einkaufsliste hinzufügen und meine geschätzte Lebensmittelrechnung aktualisieren. Immer wenn ich "FOOD entfernen" tippe, entfernen Sie FOOD von meiner Einkaufsliste und aktualisieren meine geschätzte Einkaufsrechnung. Wenn ich "sparen" eintippe, werden Sie mir Alternativen zu den hinzugefügten Lebensmitteln auflisten, um Geld zu sparen. Am Ende werden Sie mich nach der nächsten Aktion fragen.
Fragen Sie mich nach der ersten Aktion.

---

Quelle: Prompt Engineering für ChatGPT [![Coursera-Prompt Engineering](https://img.shields.io/badge/Coursera-Prompt%20Engineering-0078D4)](https://www.coursera.org/learn/prompt-engineering/home/info)

---

## Beispiel Erstellen der Absätze in unserem Qualitätshandbuch (Teil 2)

(Fortsetzung dieser Datei: [Outline Extension Pattern](outline_expansion_pattern.md))

### user

Immer wenn ich schreibe: "schreibe \<Listenpunkt\>\<Absatz\>, dann schreibst du den Inhalt für diesen Listenpunkt. Du schreibst den Text für \<Absatz\>. Immer wenn ich nur den \<Listenpunkt\> schreibe, dann wirst du diesen Entwurf erweitern. Am Ende fragst du mich immer, was du als Nächstes machen sollst.

### ChatGPT

Verstanden! Ich werde die Anweisungen genau so umsetzen. Bitte gib mir den ersten Listenpunkt und den entsprechenden Absatz, den ich für dich ausarbeiten soll. Was möchtest du als Nächstes machen lassen?

### user_

7.1

### ChatGPT_

Hier ist die Erweiterung für den Abschnitt 7.1 "Qualitätssicherung und Evaluation" im Rahmen des Qualitätsmanagement-Handbuchs für deine stationäre Pflegeeinrichtung:

7.1 Qualitätssicherung und Evaluation

- 7.1.1 Einsatz von Audit-Instrumenten
  - Auswahl spezifischer Instrumente zur Überwachung der Ernährungsmanagementprozesse
  - Regelmäßige Audits zur Überprüfung der Einhaltung von Standards und Richtlinien
- 7.1.2 Kontinuierliche Verbesserungsprozesse
  - Einführung von Feedbackmechanismen für das Pflegepersonal und die beteiligten Fachkräfte
  - Analyse der Audit-Ergebnisse zur Identifikation von Verbesserungspotenzialen
- 7.1.3 Schulungen und Anpassungen
  - Regelmäßige Schulungen basierend auf den Ergebnissen der Audits
  - Anpassungen der Standards und Praktiken zur Optimierung der Patientenversorgung
  - Möchtest du zu einem dieser Punkte weitere Details erhalten, oder gibt es einen anderen Bereich, den du weiter ausgebaut haben möchtest?

### user__

schreibe 4.1.1

### ChatGPT__

Hier der ausgearbeitete Inhalt für den Listenpunkt 4.1.1 "Implementierung des Screenings" im Rahmen des Qualitätsmanagement-Handbuchs für deine stationäre Pflegeeinrichtung:

4.1.1 Implementierung des Screenings

- Auswahl geeigneter Screening-Tools: Die Auswahl der Screening-Tools sollte auf der Basis wissenschaftlicher Evidenz und der spezifischen Bedürfnisse der Patientenpopulation erfolgen. Wichtige Kriterien sind Validität, Reliabilität und Benutzerfreundlichkeit der Tools. Empfohlen werden Tools wie das Mini Nutritional Assessment (MNA), das speziell für ältere Erwachsene entwickelt wurde.
- Festlegung der Screening-Intervalle: Screening sollte bei Aufnahme aller Patienten durchgeführt werden sowie regelmäßig während des Aufenthalts. Für Patienten mit erhöhtem Risiko einer Mangelernährung oder bei signifikanten Veränderungen des Gesundheitszustands sind häufigere Screenings angezeigt.
- Schulung des Personals zur Durchführung des Screenings: Es ist essentiell, dass das gesamte Pflegepersonal in der korrekten Anwendung der Screening-Tools geschult wird. Die Schulungen sollten neben der praktischen Anwendung auch die Interpretation der Ergebnisse und die notwendigen Folgemaßnahmen umfassen.

Welchen Abschnitt oder Punkt möchtest du als Nächstes erweitern lassen?

---

Hier geht es zum Original Chat [![ChatGPT-GPT Plus](https://img.shields.io/badge/ChatGPT-GPT%20Plus-008080)](https://chat.openai.com/share/316fbee8-c02b-4c8a-a185-85aac78da883)

---
