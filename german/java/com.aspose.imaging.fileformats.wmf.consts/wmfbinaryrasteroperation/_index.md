---
title: "WmfBinaryRasterOperation"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Abschnitt der BinaryRasterOperation‑Aufzählung listet die binären Rasteroperationscodes auf."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

Der Abschnitt der Aufzählung BinaryRasterOperation listet die binären Raster‑Operations‑Codes auf. Raster‑Operations‑Codes definieren, wie die Metadateiverarbeitung die Bits des ausgewählten Stifts mit den Bits im Ziel‑Bitmap kombiniert.

--------------------

Jeder Raster‑Operations‑Code stellt eine boolesche Operation dar, bei der die Werte der Pixel im ausgewählten Stift und im Ziel‑Bitmap kombiniert werden. Nachfolgend die beiden in diesen Operationen verwendeten Operanden. Operand Bedeutung P Ausgewählter Stift D Ziel‑Bitmap a Bitweises UND n Bitweises NICHT (Inverse) o Bitweises ODER x Bitweises exklusives ODER (XOR)
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Black](#Black) | 0, Pixel ist immer 0. |
| [Notmergepen](#Notmergepen) | DPon, Pixel ist die Inverse der MERGEPEN‑Farbe |
| [Masknotpen](#Masknotpen) | DPna, Pixel ist eine Kombination aus der Bildschirmfarbe und der Inversen der Stiftfarbe. |
| [Notcopypen](#Notcopypen) | Pn, Pixel ist die Inverse der Stiftfarbe. |
| [Maskpennot](#Maskpennot) | PDna, Pixel ist eine Kombination der Farben, die sowohl im Stift als auch in der Inversen des Bildschirms vorkommen. |
| [Not](#Not) | Dn, Pixel ist die Inverse der Bildschirmfarbe. |
| [Xorpen](#Xorpen) | DPx, Pixel ist eine Kombination der Farben im Stift oder im Bildschirm, jedoch nicht in beiden. |
| [Notmaskpen](#Notmaskpen) | DPan, Pixel ist die Inverse der MASKPEN‑Farbe. |
| [Maskpen](#Maskpen) | DPa, Pixel ist eine Kombination der Farben, die sowohl im Stift als auch im Bildschirm vorkommen. |
| [Notxorpen](#Notxorpen) | DPxn, Pixel ist die Inverse der XORPEN‑Farbe. |
| [Nop](#Nop) | D, Pixel bleibt unverändert. |
| [Mergenotpen](#Mergenotpen) | DPno, Pixel ist eine Kombination der Farben, die sowohl im Bildschirm als auch in der Inversen des Stifts vorkommen. |
| [Copypen](#Copypen) | P, Pixel ist die Stiftfarbe. |
| [Mergepennot](#Mergepennot) | PDno, Pixel ist eine Kombination aus der Stiftfarbe und dem Inversen der Bildschirmfarbe. |
| [Mergepen](#Mergepen) | DPo, Pixel ist eine Kombination aus der Stiftfarbe und der Bildschirmfarbe. |
| [White](#White) | 1, Pixel ist immer 1 |
### Black {#Black}
```
public static final int Black
```


0, Pixel ist immer 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, Pixel ist die Inverse der MERGEPEN‑Farbe

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, Pixel ist eine Kombination aus der Bildschirmfarbe und der Inversen der Stiftfarbe.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, Pixel ist die Inverse der Stiftfarbe.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, Pixel ist eine Kombination der Farben, die sowohl im Stift als auch in der Inversen des Bildschirms vorkommen.

### Not {#Not}
```
public static final int Not
```


Dn, Pixel ist die Inverse der Bildschirmfarbe.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, Pixel ist eine Kombination der Farben im Stift oder im Bildschirm, jedoch nicht in beiden.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, Pixel ist die Inverse der MASKPEN‑Farbe.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, Pixel ist eine Kombination der Farben, die sowohl im Stift als auch im Bildschirm vorkommen.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, Pixel ist die Inverse der XORPEN‑Farbe.

### Nop {#Nop}
```
public static final int Nop
```


D, Pixel bleibt unverändert.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, Pixel ist eine Kombination der Farben, die sowohl im Bildschirm als auch in der Inversen des Stifts vorkommen.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Pixel ist die Stiftfarbe.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Pixel ist eine Kombination aus der Stiftfarbe und dem Inversen der Bildschirmfarbe.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Pixel ist eine Kombination aus der Stiftfarbe und der Bildschirmfarbe.

### White {#White}
```
public static final int White
```


1, Pixel ist immer 1

