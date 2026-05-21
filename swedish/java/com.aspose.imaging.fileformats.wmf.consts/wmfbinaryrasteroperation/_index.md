---
title: "WmfBinaryRasterOperation"
second_title: "Aspose.Imaging för Java API-referens"
description: "BinaryRasterOperation‑enumerationsavsnittet listar de binära raster‑operationskoderna."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

Avsnittet BinaryRasterOperation‑enumeration listar de binära raster‑operationskoderna. Raster‑operationskoder definierar hur metafilbehandling kombinerar bitarna från den valda pennan med bitarna i destinations‑bitmapen.

--------------------

Varje raster‑operationskod representerar en boolesk operation där värdena för pixlarna i den valda pennan och destinations‑bitmapen kombineras. Nedan följer de två operander som används i dessa operationer. Operand Betydelse P Vald pen D Destinations‑bitmap a Bitvis OCH n Bitvis INTE (invers) o Bitvis OR x Bitvis exklusiv OR (XOR)
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Black](#Black) | 0, Pixel är alltid 0. |
| [Notmergepen](#Notmergepen) | DPon, Pixel är inversen av MERGEPEN‑färgen |
| [Masknotpen](#Masknotpen) | DPna, Pixel är en kombination av skärmfärgen och inversen av pennfärgen. |
| [Notcopypen](#Notcopypen) | Pn, Pixel är inversen av pennfärgen. |
| [Maskpennot](#Maskpennot) | PDna, Pixel är en kombination av färgerna gemensamma för både pennan och inversen av skärmen. |
| [Not](#Not) | Dn, Pixel är inversen av skärm‑färgen. |
| [Xorpen](#Xorpen) | DPx, Pixel är en kombination av färgerna i pennan eller i skärmen, men inte i båda. |
| [Notmaskpen](#Notmaskpen) | DPan, Pixel är inversen av MASKPEN‑färgen. |
| [Maskpen](#Maskpen) | DPa, Pixel är en kombination av färgerna gemensamma för både pennan och skärmen. |
| [Notxorpen](#Notxorpen) | DPxn, Pixel är inversen av XORPEN‑färgen. |
| [Nop](#Nop) | D, Pixel förblir oförändrad. |
| [Mergenotpen](#Mergenotpen) | DPno, Pixel är en kombination av färgerna gemensamma för både skärmen och inversen av pennan. |
| [Copypen](#Copypen) | P, Pixel är pennfärgen. |
| [Mergepennot](#Mergepennot) | PDno, Pixel är en kombination av pennfärgen och den omvända av skärmens färg. |
| [Mergepen](#Mergepen) | DPo, Pixel är en kombination av pennfärgen och skärmens färg. |
| [White](#White) | 1, Pixel är alltid 1 |
### Black {#Black}
```
public static final int Black
```


0, Pixel är alltid 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, Pixel är inversen av MERGEPEN‑färgen

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, Pixel är en kombination av skärmfärgen och inversen av pennfärgen.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, Pixel är inversen av pennfärgen.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, Pixel är en kombination av färgerna gemensamma för både pennan och inversen av skärmen.

### Not {#Not}
```
public static final int Not
```


Dn, Pixel är inversen av skärm‑färgen.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, Pixel är en kombination av färgerna i pennan eller i skärmen, men inte i båda.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, Pixel är inversen av MASKPEN‑färgen.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, Pixel är en kombination av färgerna gemensamma för både pennan och skärmen.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, Pixel är inversen av XORPEN‑färgen.

### Nop {#Nop}
```
public static final int Nop
```


D, Pixel förblir oförändrad.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, Pixel är en kombination av färgerna gemensamma för både skärmen och inversen av pennan.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Pixel är pennfärgen.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Pixel är en kombination av pennfärgen och den omvända av skärmens färg.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Pixel är en kombination av pennfärgen och skärmens färg.

### White {#White}
```
public static final int White
```


1, Pixel är alltid 1

