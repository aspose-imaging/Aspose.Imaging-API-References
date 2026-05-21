---
title: "EmfModifyWorldTransformMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "ModifyWorldTransformMode‑uppräkningen definierar lägen för att använda specificerad transformdata för att ändra världsrums‑ till sidrymdstransformen som för närvarande är definierad i uppspelningsenhetens kontext."
type: docs
weight: 33
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

ModifyWorldTransformMode‑uppräkningen definierar lägen för att använda specificerad transformdata för att ändra världsrums‑ till sidrymdstransformen som för närvarande är definierad i uppspelningsenhetens kontext.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Återställ den aktuella transformen med identitetsmatrisen. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Multiplicera den aktuella transformen. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Multiplicera den aktuella transformen. |
| [MWT_SET](#MWT-SET) | Utför funktionen för en EMR\_SETWORLDTRANSFORM-post (avsnitt 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Återställ den aktuella transformen med identitetsmatrisen. I detta läge ignoreras den angivna transformdata.

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Multiplicera den aktuella transformen. I detta läge är den angivna transformdata den vänstra multiplikanden, och den transform som för närvarande är definierad i uppspelningsenhetens kontext är den högra multiplikanden.

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Multiplicera den aktuella transformen. I detta läge är den angivna transformdata den högra multiplikanden, och den transform som för närvarande är definierad i uppspelningsenhetens kontext är den vänstra multiplikanden.

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


Utför funktionen för en EMR\_SETWORLDTRANSFORM-post (avsnitt 2.3.12.2).

