---
title: "EmfBlendFunction"
second_title: "Aspose.Imaging för Java API-referens"
description: "En struktur som specificerar blandningsoperationerna för käll- och destinationsbitmapar."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

En struktur som specificerar blandningsoperationerna för käll- och destinationsbitmapar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | Initierar en ny instans av klassen `EmfBlendFunction`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Hämtar blandningsoperationskoden. |
| [getBlendFlags()](#getBlendFlags--) | Hämtar blandningsflaggorna. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Hämtar ett 8‑bitars osignerat heltal som specificerar alfa‑transparens, vilket bestämmer blandningen av käll‑ och destinations‑bitmapar. |
| [getAlphaFormat()](#getAlphaFormat--) | Hämtar en struktur som specificerar hur käll‑ och destinations‑pixlar tolkas med avseende på alfa‑transparens. |
| [toInt()](#toInt--) | Konverterar strängrepresentationen av ett tal till ett heltal. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


Initierar en ny instans av klassen `EmfBlendFunction`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dwordData | int | dword‑data. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Hämtar blandningsoperationskoden. Den enda källa‑ och destinations‑blandningsoperation som har definierats är 0x00, vilket specificerar att käll‑bitmapen MÅSTE kombineras med destinations‑bitmapen baserat på alfa‑transparensvärdena för käll‑pixlarna. Se följande ekvationer för detaljer.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Hämtar blandningsflaggorna. Detta värde MÅSTE vara 0x00 och MÅSTE ignoreras.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Hämtar ett 8‑bitars osignerat heltal som specificerar alfa‑transparens, vilket bestämmer blandningen av käll‑ och destinations‑bitmapar. Detta värde MÅSTE användas på hela käll‑bitmapen. Det minsta alfa‑transparensvärdet, noll, motsvarar helt genomskinligt och det maximala värdet, 0xFF, motsvarar helt ogenomskinligt. I praktiken specificerar ett värde på 0xFF att per‑pixel‑alfa‑värdena bestämmer blandningen av käll‑ och destinations‑bitmapar. Se ekvationerna senare i detta avsnitt för detaljer.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Hämtar en struktur som specificerar hur käll‑ och destinations‑pixlar tolkas med avseende på alfa‑transparens.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Konverterar strängrepresentationen av ett tal till ett heltal.

**Returns:**
int - DWORD‑värdet för strukturen.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
