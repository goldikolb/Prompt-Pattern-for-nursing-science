# Gameplay Pattern

Um dieses Muster zu verwenden, sollte Ihre Aufforderung die folgenden grundlegenden kontextuellen Aussagen machen:

- Erfinden Sie für mich ein Spiel zum Thema X ODER wir werden ein Spiel zum Thema X spielen
- Eine oder mehrere Grundregeln des Spiels

Sie müssen "X" durch ein geeignetes Spielthema ersetzen, z. B. "Mathematik" oder "Höhlenforschungsspiel zur Entdeckung einer verlorenen Sprache". Dann müssen Sie Regeln für das Spiel aufstellen, wie z.B. "Beschreiben Sie, was sich in der Höhle befindet und geben Sie mir eine Liste von Aktionen, die ich ausführen kann" oder "Stellen Sie mir Fragen zu Brüchen und erhöhen Sie meine Punktzahl jedes Mal, wenn ich eine richtig beantwortet habe."

_Beispiele:_

- Entwickeln Sie ein Höhlenforschungsspiel, bei dem ich eine verlorene Sprache entdecken soll. Beschreiben Sie, wo ich mich in der Höhle befinde und was ich tun kann. Ich sollte in jedem Bereich der Höhle, den ich besuche, neue Wörter und Symbole für die verlorene Zivilisation entdecken. Jeder Bereich sollte auch einen Teil einer Geschichte enthalten, in der die Sprache verwendet wird. Ich sollte alle Wörter und Symbole sammeln müssen, um die Geschichte verstehen zu können. Erzählen Sie mir von dem ersten Bereich und fragen Sie mich dann, was ich tun soll.
- Entwerfen Sie für mich ein Gruppenspiel mit DALL-E. Das Spiel sollte darin bestehen, Aufforderungen zu erstellen, die sich auf ein Thema beziehen, das Sie in jeder Runde auflisten. Jeder kreiert eine Aufforderung und erstellt ein Bild mit DALL-E. Die Teilnehmer stimmen dann über die beste Aufforderung ab, basierend auf dem Bild, das sie erzeugt. Fragen Sie mich am Ende jeder Runde, wer die Runde gewonnen hat und nennen Sie dann den aktuellen Punktestand. Beschreiben Sie die Regeln und nennen Sie dann das erste Thema.

---

Quelle: Prompt Engineering für ChatGPT [![Coursera-Prompt Engineering](https://img.shields.io/badge/Coursera-Prompt%20Engineering-0078D4)](https://www.coursera.org/learn/prompt-engineering/home/info)

---

## Beispiel Python lernen mit ChatGPT

### user

Ich möchte ein interaktives Python-Spiel erstellen, bei dem ich eine Aufgabe gestellt bekomme und den Code dafür schreiben muss. Du sollst mir die Aufgabe stellen und meinen Code bewerten. Wenn ich etwas falsch mache, gibst du mir Feedback und erklärst mir, was ich falsch gemacht habe. Hier ist ein Beispiel für eine Aufgabe: Schreibe 'Hallo Welt'.

### ChatGPT

Super, dann legen wir gleich los mit der ersten Aufgabe:

Aufgabe:
Erstelle ein Python-Programm, das eine Zahl zwischen 1 und 100 vom Benutzer einliest und dann ausgibt, ob diese Zahl gerade oder ungerade ist.

Wenn du deinen Code geschrieben hast, kannst du ihn hier einfügen, und ich werde ihn bewerten.

### user_

        # Frage den Benutzer nach einer Zahl zwischen 1 und 100
        num = int(input("Bitte gib eine Zahl zwischen 1 und 100 ein: "))

        # Überprüfe, ob die Zahl im Bereich liegt
        if num < 1 or num > 100:
            print("Die Zahl muss zwischen 1 und 100 liegen.")
        else:
            # Überprüfe, ob die Zahl gerade oder ungerade ist
            if num % 2 == 0:
                print("Die Zahl ist gerade.")
            else:
                print("Die Zahl ist ungerade.")

### ChatGPT_

Dein Code sieht gut aus! Hier sind die Punkte, die du gut gemacht hast:

- Du hast die Benutzereingabe korrekt implementiert und in einen Integer umgewandelt.
- Die Überprüfung, ob die Zahl im vorgegebenen Bereich liegt, ist korrekt.
- Du hast richtig erkannt, wie man testet, ob eine Zahl gerade oder ungerade ist.

**Feedback:**
Es gibt keinen direkten Verbesserungsbedarf in deinem Code, er erfüllt die Aufgabe wie vorgesehen. Wenn du willst, könnten wir die Funktionalität erweitern oder eine neue Aufgabe versuchen. Möchtest du eine neue Aufgabe probieren oder etwas anderes an deinem aktuellen Code ändern?
