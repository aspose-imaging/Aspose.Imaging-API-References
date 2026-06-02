---
title: "EmfGraphicsMode Aufzählung"
type: docs
weight: 150
url: /de/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

Die GraphicsMode-Aufzählung wird verwendet, um anzugeben, wie Formdaten wie Rechteckkoordinaten interpretiert werden.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| GM_ADVANCED | TrueType-Textausgabe MUSS vollständig der aktuellen Welt‑zu‑Gerät‑Transformation im Wiedergabegeräte‑Kontext entsprechen.<br/>            Bögen MUSS im Gegenuhrzeigersinn im Weltraum gezeichnet werden; jedoch müssen sowohl die Bogen‑Steuerpunkte <br/>            als auch die Bögen selbst die aktuelle Welt‑zu‑Gerät‑Transformation im Wiedergabegeräte‑Kontext vollständig respektieren.<br/>            Die Welt‑zu‑Gerät‑Transformation KANN direkt durch Verwendung der EMR_MODIFYWORLDTRANSFORM‑ oder <br/>            EMR_SETWORLDTRANSFORM‑Datensätze geändert werden, oder indirekt durch Ändern der Fenster‑ und Ansichtsport‑Ausmaße und Ursprünge, <br/>            unter Verwendung der EMR_SETWINDOWEXTEX (Abschnitt 2.3.11.30) und EMR_SETVIEWPORTEXTEX (Abschnitt 2.3.11.28) Datensätze, <br/>            sowie der EMR_SETWINDOWORGEX (Abschnitt 2.3.11.31) und EMR_SETVIEWPORTORGEX (Abschnitt 2.3.11.30) Datensätze, jeweils.<br/>            Im Grafikmodus GM_ADVANCED MÜSSEN die unteren und rechtesten Kanten einbezogen werden, wenn Rechtecke gezeichnet werden. |
| GM_COMPATIBLE | TrueType-Text MUSS von links nach rechts und rechtsseitig oben geschrieben werden, selbst wenn der Rest der Grafiken <br/>            aufgrund der aktuellen Welt‑zu‑Gerät‑Transformation im Wiedergabegeräte‑Kontext um die x‑Achse oder y‑Achse gedreht ist. Nur die Höhe des Textes SOLL skaliert werden. Bögen MUSS unter Verwendung der aktuellen Bogenausrichtung im Wiedergabegeräte‑Kontext gezeichnet werden, aber sie DÜRFEN die aktuelle <br/>            Welt‑zu‑Gerät‑Transformation nicht berücksichtigen, die eine Drehung um die x‑Achse oder y‑Achse erfordern könnte.<br/>            Die Welt‑zu‑Gerät‑Transformation SOLL nur durch Ändern der Fenster‑ und Ansichtsport‑Ausmaße und Ursprünge geändert werden, unter Verwendung der EMR_SETWINDOWEXTEX (Abschnitt 2.3.11.30) und EMR_SETVIEWPORTEXTEX <br/>            (Abschnitt 2.3.11.28) Datensätze, sowie der EMR_SETWINDOWORGEX (Abschnitt 2.3.11.31) und EMR_SETVIEWPORTORGEX <br/>            (Abschnitt 2.3.11.30) Datensätze, jeweils. bChanging die Transformation direkt durch Verwendung der <br/>            EMR_MODIFYWORLDTRANSFORM (Abschnitt 2.3.12.1) oder EMR_SETWORLDTRANSFORM (Abschnitt 2.3.12.2) Datensätze KANN NICHT unterstützt werden.<br/>            Im Grafikmodus GM_COMPATIBLE MÜSSEN die unteren und rechtesten Kanten ausgeschlossen werden, wenn Rechtecke gezeichnet werden. |
