---
title: "EmfGraphicsMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "GraphicsMode-enumerationen används för att ange hur formdata såsom rektangelkoordinater ska tolkas."
type: docs
weight: 24
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

GraphicsMode-enumerationen används för att ange hur formdata såsom rektangelkoordinater ska tolkas.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | TrueType‑text MÅSTE skrivas från vänster till höger och med rätt sida uppåt, även om resten av grafiken är roterad kring x‑axeln eller y‑axeln på grund av den aktuella world-to-device‑transformeringen i uppspelningsenhetens kontext. |
| [GM_ADVANCED](#GM-ADVANCED) | TrueType‑textutdata MÅSTE fullt ut följa den aktuella world-to-device‑transformeringen i uppspelningsenhetens kontext. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


TrueType‑text MÅSTE skrivas från vänster till höger och med rätt sida uppåt, även om resten av grafiken är roterad kring x‑axeln eller y‑axeln på grund av den aktuella world-to-device‑transformeringen i uppspelningsenhetens kontext. Endast textens höjd SKA skalas. Bågar MÅSTE ritas med den aktuella båg‑riktningen i uppspelningsenhetens kontext, men de MÅSTE INTE följa den aktuella world-to-device‑transformeringen, vilket kan kräva en rotation kring x‑axeln eller y‑axeln. world-to-device‑transformeringen SKA endast ändras genom att ändra fönster‑ och vy‑utbredningar och ursprung, med hjälp av EMR\_SETWINDOWEXTEX (avsnitt 2.3.11.30) och EMR\_SETVIEWPORTEXTEX (avsnitt 2.3.11.28) poster, samt EMR\_SETWINDOWORGEX (avsnitt 2.3.11.31) och EMR\_SETVIEWPORTORGEX (avsnitt 2.3.11.30) poster, respektive. bChanging transformeringen direkt genom att använda EMR\_MODIFYWORLDTRANSFORM (avsnitt 2.3.12.1) eller EMR\_SETWORLDTRANSFORM (avsnitt 2.3.12.2) poster FÅR INTE stödjas. I GM\_COMPATIBLE‑grafikläge SKA de nedersta och högra kanterna uteslutas när rektanglar ritas.

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


TrueType‑textutdata MÅSTE fullt ut följa den aktuella world-to-device‑transformeringen i uppspelningsenhetens kontext. Bågar MÅSTE ritas i moturs riktning i world‑space; dock måste både bågkontrollpunkter och själva bågarna fullt ut respektera den aktuella world-to-device‑transformeringen i uppspelningsenhetens kontext. world-to-device‑transformeringen KAN ändras direkt genom att använda EMR\_MODIFYWORLDTRANSFORM‑ eller EMR\_SETWORLDTRANSFORM‑poster, eller indirekt genom att ändra fönster‑ och vy‑utbredningar och ursprung, med hjälp av EMR\_SETWINDOWEXTEX (avsnitt 2.3.11.30) och EMR\_SETVIEWPORTEXTEX (avsnitt 2.3.11.28) poster, samt EMR\_SETWINDOWORGEX (avsnitt 2.3.11.31) och EMR\_SETVIEWPORTORGEX (avsnitt 2.3.11.30) poster, respektive. I GM\_ADVANCED‑grafikläge SKA de nedersta och högra kanterna inkluderas när rektanglar ritas.

