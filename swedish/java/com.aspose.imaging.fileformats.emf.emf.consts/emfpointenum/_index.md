---
title: "EmfPointEnum"
second_title: "Aspose.Imaging för Java API-referens"
description: "Point‑uppräkningen används för att ange hur en punkt ska användas i ett ritningsanrop."
type: docs
weight: 35
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

Point‑uppräkningen används för att ange hur en punkt ska användas i ett ritningsanrop.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | En PT\_LINETO- eller PT\_BEZIERTO-typ kan kombineras med detta värde genom att använda den bitvisa operatorn OR för att indikera att motsvarande punkt är den sista punkten i en figur och att figuren är sluten |
| [PT_LINETO](#PT-LINETO) | Anger att en linje ska ritas från den aktuella positionen till denna punkt, som sedan blir den nya aktuella positionen. |
| [PT_BEZIERTO](#PT-BEZIERTO) | Anger att denna punkt är en kontrollpunkt eller slutpunkt för en Bézier-kurva. |
| [PT_MOVETO](#PT-MOVETO) | Anger att denna punkt startar en fristående figur. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


En PT\_LINETO- eller PT\_BEZIERTO-typ kan kombineras med detta värde genom att använda den bitvisa operatorn OR för att indikera att motsvarande punkt är den sista punkten i en figur och att figuren är sluten

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Anger att en linje ska ritas från den aktuella positionen till denna punkt, som sedan blir den nya aktuella positionen.

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Anger att denna punkt är en kontrollpunkt eller slutpunkt för en Bézier-kurva.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Anger att denna punkt startar en fristående figur. Denna punkt blir den nya aktuella positionen.

