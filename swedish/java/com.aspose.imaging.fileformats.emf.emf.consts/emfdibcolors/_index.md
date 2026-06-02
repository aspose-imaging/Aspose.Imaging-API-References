---
title: "EmfDibColors"
second_title: "Aspose.Imaging för Java API-referens"
description: "DIBColors-enumerationen definierar hur värdena i färgtabellen för en DIB ska tolkas."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfDibColors extends System.Enum
```

DIBColors-enumerationen definierar hur värdena i färgtabellen för en DIB ska tolkas.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | Färgtabellen innehåller bokstavliga RGB-värden |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | Färgtabellen består av en array av 16-bitars index till LogPalette-objektet (avsnitt 2.2.17) som för närvarande är definierat i uppspelningsenhetens kontext. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Ingen färgtabell finns. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


Färgtabellen innehåller bokstavliga RGB-värden

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


Färgtabellen består av en array av 16-bitars index till LogPalette-objektet (avsnitt 2.2.17) som för närvarande är definierat i uppspelningsenhetens kontext.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Ingen färgtabell finns. Pixlarna i DIB är index till den aktuella logiska paletten i uppspelningsenhetens kontext.

