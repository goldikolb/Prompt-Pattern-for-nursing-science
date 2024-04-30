# Semantic Filter Pattern

Um dieses Muster zu verwenden, sollte Ihre Eingabeaufforderung die folgenden grundlegenden kontextbezogenen Aussagen machen:

- Filtern Sie diese Informationen, um X zu entfernen

Sie müssen "X" durch eine geeignete Definition dessen ersetzen, was Sie entfernen möchten, z.B.. "Namen und Daten" oder "Kosten von mehr als $100".

Beispiele:

- Filtern Sie die folgende Beschreibung eines Hilfebedarfs eines Pflegeheimbewohners, nach allen persönlichen Informationen oder Informationen, die zur Re-Identifizierung des Bewohners verwendet werden könnten, und entferne diese.
- Filtern Sie diese E-Mail, um überflüssige Informationen zu entfernen.

---

Quelle: Prompt Engineering für ChatGPT [![Coursera-Prompt Engineering](https://img.shields.io/badge/Coursera-Prompt%20Engineering-0078D4)](https://www.coursera.org/learn/prompt-engineering/home/info)

---

## Beispiel Filtern von Datenschutz relevanten Informationen

### user

Filtern Sie die folgende Beschreibung eines Hilfebedarfs eines Pflegeheimbewohners, nach allen persönlichen Informationen oder Informationen, die zur Re-Identifizierung des Bewohners verwendet werden könnten, und entferne diese.

Beschreibung:

Herr Bernd Meier benötigt bei dem Transfer von Bett in den Rollstuhl und vom Rollstuhl auf WC immer Unterstützung von der Pflegefachkraft Frau Irmgard Grün. Herr Meier kann sich nur kurze Strecken mit dem Rollstuhl durch tippeln fortbewegen, ansonsten muss Bern von Irmgard geschoben werden. Er versucht sich im Bett alleine zur Seite zu drehen, er ist aber nach der Operation bei Dr. Sägezahn wegen seiner Schenkelhalsfraktur in seiner Beweglichkeit eingeschränkt und er leidet auch unter Schmerzen in den Gelenken. Herr Meier ist Sturz-gefährdet. Herr Meier kann seine körperliche Schwäche nicht adäquat einschätzen. Bernd versucht, sich alleine an den Bettrand zu setzten. Bernd versucht sich dann alleine in den Rollstuhl umzusetzen, ist aber Sturz-gefährdet, deswegen muss er von Frau grün beaufsichtigt werden.

### ChatGPT

Hier ist die gefilterte Beschreibung des Hilfebedarfs eines Pflegeheimbewohners ohne persönliche oder wiedererkennbare Informationen:

Beschreibung:

Der Bewohner benötigt bei dem Transfer von Bett in den Rollstuhl und vom Rollstuhl auf das WC immer Unterstützung. Er kann sich nur kurze Strecken mit dem Rollstuhl fortbewegen, muss ansonsten geschoben werden. Er versucht sich im Bett alleine zur Seite zu drehen, ist aber aufgrund einer Operation am Schenkelhals in seiner Beweglichkeit eingeschränkt und leidet unter Gelenkschmerzen. Der Bewohner ist sturzgefährdet und kann seine körperliche Schwäche nicht adäquat einschätzen. Er versucht, sich alleine an den Bettrand zu setzen und sich in den Rollstuhl umzusetzen, ist jedoch sturzgefährdet, daher muss er beaufsichtigt werden.

---

Hier geht es zum Original Chat [![ChatGPT-GPT Plus](https://img.shields.io/badge/ChatGPT-GPT%20Plus-008080)](https://chat.openai.com/share/55ebc1f7-8b92-4bcc-b283-fc71b5647e78)

---
