---
title: "EmfPointEnum"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Point‑Aufzählung wird verwendet, um anzugeben, wie ein Punkt in einem Zeichenaufruf verwendet werden soll."
type: docs
weight: 35
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

Die Point‑Aufzählung wird verwendet, um anzugeben, wie ein Punkt in einem Zeichenaufruf verwendet werden soll.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | Ein PT\_LINETO- oder PT\_BEZIERTO-Typ kann mit diesem Wert kombiniert werden, indem der bitweise Operator OR verwendet wird, um anzuzeigen, dass der entsprechende Punkt der letzte Punkt in einer Figur ist und die Figur geschlossen ist. |
| [PT_LINETO](#PT-LINETO) | Gibt an, dass eine Linie von der aktuellen Position zu diesem Punkt gezeichnet werden soll, der dann zur neuen aktuellen Position wird. |
| [PT_BEZIERTO](#PT-BEZIERTO) | Gibt an, dass dieser Punkt ein Kontrollpunkt oder Endpunkt für eine Bézierkurve ist. |
| [PT_MOVETO](#PT-MOVETO) | Gibt an, dass dieser Punkt eine getrennte Figur beginnt. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


Ein PT\_LINETO- oder PT\_BEZIERTO-Typ kann mit diesem Wert kombiniert werden, indem der bitweise Operator OR verwendet wird, um anzuzeigen, dass der entsprechende Punkt der letzte Punkt in einer Figur ist und die Figur geschlossen ist.

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Gibt an, dass eine Linie von der aktuellen Position zu diesem Punkt gezeichnet werden soll, der dann zur neuen aktuellen Position wird.

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Gibt an, dass dieser Punkt ein Kontrollpunkt oder Endpunkt für eine Bézierkurve ist.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Gibt an, dass dieser Punkt eine getrennte Figur beginnt. Dieser Punkt wird zur neuen aktuellen Position.

