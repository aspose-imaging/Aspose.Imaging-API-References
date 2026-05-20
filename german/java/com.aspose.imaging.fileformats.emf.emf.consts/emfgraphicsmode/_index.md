---
title: "EmfGraphicsMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Aufzählung GraphicsMode wird verwendet, um anzugeben, wie Formdaten wie Rechteckkoordinaten interpretiert werden."
type: docs
weight: 24
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

Die Aufzählung GraphicsMode wird verwendet, um anzugeben, wie Formdaten wie Rechteckkoordinaten interpretiert werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | TrueType-Text MUSS von links nach rechts und rechtsseitig geschrieben werden, selbst wenn der Rest der Grafiken um die x‑Achse oder y‑Achse gedreht ist aufgrund der aktuellen world-to-device-Transformation im Wiedergabegerätekontext. |
| [GM_ADVANCED](#GM-ADVANCED) | TrueType-Textausgabe MUSS vollständig der aktuellen world-to-device-Transformation im Wiedergabegerätekontext entsprechen. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


TrueType-Text MUSS von links nach rechts und rechtsseitig geschrieben werden, selbst wenn der Rest der Grafiken um die x‑Achse oder y‑Achse gedreht ist aufgrund der aktuellen world-to-device-Transformation im Wiedergabegerätekontext. Nur die Höhe des Textes SOLL skaliert werden. Bögen MUSS mit der aktuellen Bogenausrichtung im Wiedergabegerätekontext gezeichnet werden, dürfen jedoch die aktuelle world-to-device-Transformation NICHT berücksichtigen, die eine Drehung um die x‑Achse oder y‑Achse erfordern könnte. Die world-to-device-Transformation SOLL nur durch Ändern der Fenster‑ und Viewport‑Ausmaße und -Ursprünge modifiziert werden, wobei die EMR\_SETWINDOWEXTEX (Abschnitt 2.3.11.30) und EMR\_SETVIEWPORTEXTEX (Abschnitt 2.3.11.28) Datensätze sowie die EMR\_SETWINDOWORGEX (Abschnitt 2.3.11.31) und EMR\_SETVIEWPORTORGEX (Abschnitt 2.3.11.30) Datensätze verwendet werden, jeweils. bChanging die Transformation direkt mittels EMR\_MODIFYWORLDTRANSFORM (Abschnitt 2.3.12.1) oder EMR\_SETWORLDTRANSFORM (Abschnitt 2.3.12.2) Datensätze KANN NICHT unterstützt werden. Im Grafikmodus GM\_COMPATIBLE MUSS die untere und rechte Kante ausgeschlossen werden, wenn Rechtecke gezeichnet werden.

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


TrueType-Textausgabe MUSS vollständig der aktuellen world-to-device-Transformation im Wiedergabegerätekontext entsprechen. Bögen MUSS in Gegen-Uhrzeigersinn im Weltraum gezeichnet werden; jedoch müssen sowohl die Bogenkontrollpunkte als auch die Bögen selbst die aktuelle world-to-device-Transformation im Wiedergabegerätekontext vollständig berücksichtigen. Die world-to-device-Transformation KANN direkt mittels EMR\_MODIFYWORLDTRANSFORM oder EMR\_SETWORLDTRANSFORM Datensätzen geändert werden, oder indirekt durch Ändern der Fenster‑ und Viewport‑Ausmaße und -Ursprünge, wobei die EMR\_SETWINDOWEXTEX (Abschnitt 2.3.11.30) und EMR\_SETVIEWPORTEXTEX (Abschnitt 2.3.11.28) Datensätze sowie die EMR\_SETWINDOWORGEX (Abschnitt 2.3.11.31) und EMR\_SETVIEWPORTORGEX (Abschnitt 2.3.11.30) Datensätze verwendet werden, jeweils. Im Grafikmodus GM\_ADVANCED MUSS die untere und rechte Kante eingeschlossen werden, wenn Rechtecke gezeichnet werden.

