# Few-Shot Pattern

Few-Shot Learning ist eine Technik im maschinellen Lernen, bei der ein Modell mit einer sehr begrenzten Menge an Trainingsdaten (den "Shots") trainiert wird. Das Ziel ist es, das Modell so zu gestalten, dass es schnell aus einer kleinen Anzahl von Beispielen lernen und Muster erkennen kann, um dann neue, ähnliche Aufgaben zu lösen. Diese Methode ist besonders nützlich in Szenarien, in denen nicht viele Daten verfügbar sind oder wenn es schnell gehen muss, ein Modell auf spezifische, neue Situationen anzupassen. Few-Shot Learning ermöglicht es dem Modell, aus minimalen Informationen effektiv zu lernen und präzise Vorhersagen oder Klassifizierungen zu treffen.

---

Quelle: Prompt Engineering für ChatGPT [![Coursera-Prompt Engineering](https://img.shields.io/badge/Coursera-Prompt%20Engineering-0078D4)](https://www.coursera.org/learn/prompt-engineering/home/info)

---

## Beispiel anhand des Kriterium "Treppensteigen" des Modul Mobilität

### user

**Handlung:** Ein Patient geht ohne Festhalten am Geländer alleine die Treppe hoch.
**Grad der Selbständigkeit:** selbstständig

**Handlung:** Ein Patient geht mit Festhalten am Geländer die Treppe hoch. Eine Person muss ihn Beaufsichtigen, weil er alleine sich unsicher fühlt.
**Grad der Selbständigkeit:** überwiegend unselbstständig

**Handlung:** Ein Patient muss beim Treppensteigen gehalten werden von einer Pflegeperson, weil er sonst die Treppe nicht bewältigen kann.
**Grad der Selbständigkeit:** überwiegend unselbstständig

**Handlung:** Ein Patient kann keine Treppen steigen, wenn dann muss er getragen werden.
**Grad der Selbständigkeit:** unselbstständig

**Handlung:** Ein Patient kann alleine die Treppen steigen, er muss aber langsam gehen.
**Grad der Selbständigkeit:**

### ChatGPT

**Grad der Selbständigkeit:** selbstständig

---

Hier geht es zum Original Chat [![ChatGPT-GPT Plus](https://img.shields.io/badge/ChatGPT-GPT%20Plus-008080)](https://chat.openai.com/share/f6adc337-afa0-47ee-bbb2-6e11a3b26517)

---
