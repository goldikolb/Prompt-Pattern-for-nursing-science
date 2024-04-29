# Chain of thought

Chain of Thought ist eine Methode, bei der komplexe Probleme schrittweise in kleinere, handhabbare Teile aufgeteilt und gelöst werden. Bei der Anwendung dieses Musters wird jeder Denkschritt klar dargestellt, was hilft, die Überlegungen transparent zu machen und zu einer endgültigen Antwort oder Lösung zu führen. Das Ziel ist es, den gesamten Denkprozess sichtbar zu machen, um so das Verständnis zu erleichtern und nachvollziehbare Ergebnisse zu erzielen.

___

Mehr Informationen zu dieser Methodik in diesem wissenschaftlichen Artikel [![arXiv-Paper](https://img.shields.io/badge/arXiv-2201.11903-B31B1B)](https://arxiv.org/abs/2201.11903)

Quelle: Prompt Engineering für ChatGPT [![Coursera-Prompt Engineering](https://img.shields.io/badge/Coursera-Prompt%20Engineering-0078D4)](https://www.coursera.org/learn/prompt-engineering/home/info)

___

## Beispiel anhand der korrekten Beurteilung des Kriterium Treppensteigen

_user_
**Situation:** Der Bewohner kann die Treppen bewältigen. Der Patient muss sich beim Treppensteigen aber immer an einem Geländer festhalten. Mehr wie drei Etagen schafft er nicht.
**Bewertung der Grad der Selbständigkeit:** Der Bewohner benutzt beim Treppenstiegen ein Geländer, das ist ein Hilfsmittel und bei jeder DIN genormten Treppe in Deutschland vorhanden. Er kann zudem sich zwischen zwei Etagen ohne die Hilfe von einer anderen Person bewegen. Er schafft sogar 3 Etagen. - Die Antwort ist _selbständig_.

**Situation:** Der Bewohner muss beim Treppensteigen wegen seiner Gangunsicherheit und Sturzgefahr begleitet werden. Es reicht aus, wenn jemand hinter dem Patienten hergeht, damit er sich sicher fühlt.
**Bewertung der Grad der Selbständigkeit:** Der Versicherte benötigt beim Treppensteigen personelle Hilfe in Form von Beaufsichtigung. Der Bewohner muss aber festgehalten werden, es reicht, wenn jemand hinter ihm hergeht. - Die Antwort ist _überwiegend selbständig_.

**Situation:** Der Bewohner muss beim Treppensteigen immer gehalten werden, sonst schafft er es nicht eine ganze Etage zu bewältigen. Ein Geländer alleine reicht nicht aus.
**Bewertung der Grad der Selbständigkeit:** Der Bewohner schafft keine ganze Etage ohne personelle Hilfe. Beim Treppensteigen muss er gehalten werden. - Die Antwort ist _überwiegend unselbständig_.

**Situation:** Der Patient schafft es nur noch mit personeller Hilfe die 2 Stufen vor meiner Haustüre zu bewältigen. Eine ganze Etage schafft er nicht mehr, selbst nicht, wenn eine Pflegeperson ihn hält.
**Bewertung der Grad der Selbständigkeit:** Der Bewohner schafft es nur eine komplette Treppe zwischen zwei Etagen zu steigen, wenn eine andere Person ihn hält. - Die Antwort ist _unselbständig_.

Situation: Der Bewohner ist blind, er kann die Stufen nicht erkennen. Es muss immer jemand vor ihm hergehen. Der Patient muss nicht gehalten werden.
Bewertung der Grad der Selbständigkeit: Erklärung \<Erklärung\> - Antwort \<Antwort\>

_ChatGPT_
**Situation:** Der Bewohner ist blind, er kann die Stufen nicht erkennen. Es muss immer jemand vor ihm hergehen. Der Patient muss nicht gehalten werden.

**Bewertung der Grad der Selbständigkeit:**

- **Erklärung:** Der Bewohner benötigt eine visuelle Hilfestellung in Form einer Person, die ihm den Weg weist, da er die Stufen aufgrund seiner Blindheit nicht selbst erkennen kann.
- **Antwort:** _Überwiegend selbständig_, da keine physische Unterstützung benötigt wird, aber dennoch eine kontinuierliche personelle Unterstützung erforderlich ist.
