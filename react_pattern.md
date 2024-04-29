# ReAct Pattern

Das ReAct Pattern ist eine Methode, die bei der Analyse und Bewertung von Situationen hilft, indem sie strukturiert vorgeht. "ReAct" steht für Reflexion, Aktion und Ergebnis. Hierbei werden drei Schritte durchlaufen:

1. **Reflexion:** In diesem Schritt wird die Situation oder das Problem genau betrachtet und analysiert. Was sind die Umstände? Was sind die Bedürfnisse der betroffenen Person?
2. **Aktion:** Basierend auf der Reflexion wird eine Handlung oder eine Frage formuliert, um weitere Informationen zu sammeln oder eine Lösung zu erarbeiten.
3. **Ergebnis:** Die Ergebnisse der Aktion werden festgehalten. Wie hat die betroffene Person reagiert? Welche neuen Informationen wurden gewonnen?
Diese Methode wird oft verwendet, um systematisch Daten zu sammeln und Entscheidungen fundiert zu treffen.

___

Mehr Informationen zu dieser Methodik in diesem wissenschaftlichen Artikel [![arXiv-Paper](https://img.shields.io/badge/arXiv-2210.03629-B31B1B)](https://arxiv.org/abs/2210.03629)

Quelle: Prompt Engineering für ChatGPT [![Coursera-Prompt Engineering](https://img.shields.io/badge/Coursera-Prompt%20Engineering-0078D4)](https://www.coursera.org/learn/prompt-engineering/home/info)

___

## Beispiel für das Abfragen eines Hilfebedarfs für den Grad der Selbständigkeit beim Gehen und Treppensteigen

### user

**Aufgabe:** Bewerte den Grad der Selbständigkeit beim Gehen für das Kriterium Fortbewegen im Wohnbereich in dem Modul 1 der Begutachtungsrichtlinien zur Bewertung des Pflegegrades für deine Pflegedokumentation.

**Denk nach:** Du musst von dem Bewohner erfahren, benötigt er ein Hilfsmittel beim Gehen. Schafft er es mindestens 8 m alleine zu auf gerader Ebene zu gehen. Muss ihm jemand beim Gehen beaufsichtigen, ihn halten oder braucht er Hilfe beim Fahren mit einem Rollstuhl?

**Aktion:** Frage den Bewohner, ob er beim Gehen ein Hilfsmittel, wie einen Rollator oder Rollstuhl benötigt?
Ergebnis: Der Bewohner sagt er kann mehr als 8 m gehen, er benötigt aber dabei immer einen Rollator.

**Denk nach:**  Benötigt er auch immer beim Gehen eine Pflegeperson, die ihn beaufsichtigt, weil er sonst Angst hat zu stürzen und sie somit immer in seiner Nähe ist um ihn zu helfen. Oder benötigt er sogar immer eine Person, die ihn beim Gehen hält, weil er sonst keine 8 m schafft.

**Aktion:** Frag den Bewohner, ob er jemanden benötigt, der in Beaufsichtigen oder Halten muss, beim Gehen.
Ergebnis: Der Bewohner sagt, er muss beim Gehen immer gehalten werden trotz Rollator, weil er sonst stürzt.

**Aktion:** Ich weiß, dass er trotz eines Hilfsmittels beim Gehen immer gehalten werden muss. Der Grad der Selbständigkeit ist - _überwiegend unselbständig_.

**Aufgabe:** Bewerte den Grad der Selbständigkeit beim Treppensteigen für das Kriterium Treppensteigen in dem Modul 1 der Begutachtungsrichtlinien zur Bewertung des Pflegegrades für deine Pflegedokumentation.
**Denk nach:**

Bitte benutze das ReAct Muster und erfinde einen hypothetischen Bewohner.

### ChatGPT

**Aufgabe:** Bewertung des Grades der Selbständigkeit beim Treppensteigen

**Reflexion:**

* Muss der Bewohner beim Treppensteigen unterstützt werden?
* Ist der Bewohner in der Lage, Treppen ohne Hilfe zu steigen?
* Benötigt der Bewohner Hilfsmittel wie einen Treppenlift oder Handläufe?

Aktion:

* Frage den hypothetischen Bewohner, ob er beim Treppensteigen Hilfsmittel benötigt oder ob eine Person zur Unterstützung erforderlich ist.

**Ergebnis:**

* Der hypothetische Bewohner gibt an, dass er Treppen nicht ohne Hilfe einer Pflegeperson steigen kann, da er ohne Unterstützung Gefahr läuft zu stürzen. Er benötigt zudem einen Handlauf.

**Reflexion:**

* Muss der Bewohner beim Treppensteigen immer von einer Person begleitet werden, um physische Unterstützung zu erhalten?
* Ist der Bewohner ohne diese Unterstützung nicht in der Lage, Treppen zu steigen?

**Aktion:**

Frage den hypothetischen Bewohner, ob die Begleitung ständig nötig ist, um Sicherheit beim Treppensteigen zu gewährleisten.

**Ergebnis:**

* Der Bewohner bestätigt, dass er ohne physische Unterstützung einer Pflegeperson keine Treppen steigen kann.

**Bewertung:**

Der Grad der Selbständigkeit des hypothetischen Bewohners beim Treppensteigen ist _überwiegend unselbständig_. Der Bewohner benötigt ständige Unterstützung durch eine Pflegeperson und zusätzliche Sicherheitsmaßnahmen wie Handläufe.
