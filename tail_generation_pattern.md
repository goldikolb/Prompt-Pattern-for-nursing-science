# Tail Generation Pattern

Um dieses Muster zu verwenden, sollte Ihre Aufforderung die folgenden grundlegenden kontextuellen Aussagen enthalten:

- Wiederholen Sie am Ende Y und/oder fragen Sie mich nach X.

Sie müssen "Y" durch das ersetzen, was das Modell wiederholen soll, z.B. "wiederholen Sie meine Liste der Optionen", und X durch das, wonach es fragen soll, "nach der nächsten Aktion". Diese Anweisungen müssen in der Regel am Ende der Aufforderung oder am vorletzten Punkt stehen.

Beispiele:

- Als Gliederungserweiterung fungieren. Erstellen Sie eine Gliederung mit Aufzählungspunkten auf der Grundlage der Eingaben, die ich Ihnen gebe, und fragen Sie mich dann, welchen Aufzählungspunkt Sie erweitern sollen. Erstellen Sie eine neue Gliederung für den Aufzählungspunkt, den ich ausgewählt habe. Fragen Sie mich am Ende, welchen Aufzählungspunkt Sie als nächstes erweitern sollen.  
Fragen Sie mich, was Sie umreißen sollen.
- Fügen Sie von nun an am Ende Ihrer Ausgabe den Hinweis "Diese Ausgabe wurde mit einem umfangreichen Sprachmodell erstellt und kann Fehler oder ungenaue Aussagen enthalten. Alle Aussagen sollten auf ihre Richtigkeit überprüft werden." Fragen Sie mich nach dem ersten Thema, über das Sie schreiben sollen.

---

Quelle: Prompt Engineering für ChatGPT [![Coursera-Prompt Engineering](https://img.shields.io/badge/Coursera-Prompt%20Engineering-0078D4)](https://www.coursera.org/learn/prompt-engineering/home/info)

---

## Beispiel Bewertung eines personellen Hilfebedarfs mit Hinweis auf die Haftung

(Für diesen Chat wurde ein GPT verwendet, dass die Begutachtungsrichtlinien kennt)

### user

Immer wenn ich dir einen personellen Hilfebedarf im Bereich der Mobilität beschreibe, bewerte diesen in allen fünf Kriterien im Modul 1 Mobilität.
Beschreibe den individuellen Hilfebedarf für das jeweilige Kriterium und bewerte diesen dann, gemäß der Begutachtungsrichtlinien mit "selbständig", "überwiegen selbständig", "überwiegend unselbständig" und "unselbständig".

Die 5 Kriterien sind:

1. Positionswechsel im Bett
2. Halten einer stabilen Sitzposition
3. Umsetzen
4. Fortbewegen im Wohnbereich
5. Treppensteigen

Ergänze am Ende der Ausgabe immer folgenden Satz: Dieser Bewertung erfolgt nach den Richtlinien des Medizinischen Dienstes Bund zur Feststellung der Pflegebedürftigkeit nach dem XI. Buch des Sozialgesetzbuches mit einer KI. Die Bewertung sollte durch einen erfahrenen Pflegegutachter*in auf ihre Richtigkeit hin überprüft werden.

Frage mich, welchen Hilfebedarf du zuerst bewerten sollst.

### ChatGPT

Welchen Hilfebedarf möchtest du zuerst bewerten lassen? Bitte gib mir eine detaillierte Beschreibung, damit ich die Bewertung in Modul 1 Mobilität durchführen kann.

### user_

Der Transfer von Bett in den Rollstuhl und vom Rollstuhl auf WC erfolgt mit Unterstützung durch die Pflegeperson. Der Bewohner kann nur sich kurze Strecken mit dem Rollstuhl durch tippeln fortbewegen, ansonsten muss er von der Pflegeperson geschoben werden. Er versucht sich im Bett alleine zur Seite zu drehen, er ist aber nach Operation wegen seiner Schenkelhalsfraktur in seiner Beweglichkeit eingeschränkt und er leidet auch unter Schmerzen in den Gelenken. Er ist Sturz-gefährdet. Der Bewohner kann seine körperliche Schwäche nicht adäquat einschätzen. Er versucht, sich alleine an den Bettrand zu setzten. Er versucht sich dann alleine in den Rollstuhl umzusetzen, ist aber Sturz-gefährdet, deswegen muss er dabei beaufsichtigt werden.

### ChtaGPT_

Basierend auf der detaillierten Beschreibung des Hilfebedarfs im Bereich der Mobilität kann die Bewertung in Modul 1 wie folgt vorgenommen werden:

1. **Positionswechsel im Bett:** Der Bewohner versucht, sich im Bett zur Seite zu drehen, ist jedoch aufgrund seiner Schenkelhalsfraktur und den Schmerzen in den Gelenken eingeschränkt. Er benötigt daher Unterstützung, um die Position sicher zu wechseln. **Bewertung: überwiegend unselbständig.**
2. **Halten einer stabilen Sitzposition:** Es wird berichtet, dass der Bewohner sich alleine an den Bettrand setzen kann, was auf eine gewisse Fähigkeit hindeutet, eine sitzende Position zu halten. Da er jedoch sturzgefährdet ist und Überwachung benötigt, ist er nicht vollständig selbständig. **Bewertung: überwiegend selbständig**.
3. **Umsetzen:** Beim Umsetzen vom Bett in den Rollstuhl und vom Rollstuhl auf das WC ist der Bewohner auf Unterstützung angewiesen und muss beaufsichtigt werden, um Sturzrisiken zu vermeiden. **Bewertung: überwiegend unselbständig**.
4. **Fortbewegen im Wohnbereich:** Der Bewohner kann sich nur kurze Strecken mit dem Rollstuhl durch Tippen fortbewegen, für längere Strecken ist er auf die Unterstützung einer Pflegeperson angewiesen, die ihn schiebt. **Bewertung: überwiegend unselbständig**.
5. **Treppensteigen:** Aufgrund der Beschreibung scheint der Bewohner nicht in der Lage zu sein, Treppen zu steigen. Dies wäre in einer Situation mit einer möglichen Schenkelhalsfraktur und Sturzgefährdung auch nicht sicher. **Bewertung: unselbständig**.

Zusammenfassend reflektiert diese Bewertung den Hilfebedarf des Bewohners im Bereich der Mobilität und berücksichtigt die individuellen Einschränkungen und Risiken. Dieser Bewertung erfolgt nach den Richtlinien des Medizinischen Dienstes Bund zur Feststellung der Pflegebedürftigkeit nach dem XI. Buch des Sozialgesetzbuches mit einer KI. Die Bewertung sollte durch einen erfahrenen Pflegegutachter*in auf ihre Richtigkeit hin überprüft werden.

---

Hier geht es zum Original Chat [![ChatGPT-GPT Plus](https://img.shields.io/badge/ChatGPT-GPT%20Plus-008080)](https://chat.openai.com/share/c7131e88-f5de-44e4-8974-08f33c162d22)

---
