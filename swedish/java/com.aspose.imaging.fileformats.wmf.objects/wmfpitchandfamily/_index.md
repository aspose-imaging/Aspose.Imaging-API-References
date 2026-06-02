---
title: "WmfPitchAndFamily"
second_title: "Aspose.Imaging för Java API-referens"
description: "PitchAndFamily‑objektet specificerar pitch‑ och familjeegenskaperna för ett Font‑objekt sektion 2.2.1.2."
type: docs
weight: 54
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

PitchAndFamily‑objektet specificerar pitch‑ och familjeegenskaperna för ett Font‑objekt (avsnitt 2.2.1.2). Pitch avser teckenbredden och family avser det allmänna utseendet på ett teckensnitt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | Initierar en ny instans av strukturen `WmfPitchAndFamily`. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | Initierar en ny instans av strukturen `WmfPitchAndFamily`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamily()](#getFamily--) | Hämtar en egenskap för ett teckensnitt som beskriver dess allmänna utseende. |
| [getPitch()](#getPitch--) | Hämtar en egenskap för ett teckensnitt som beskriver pitch för tecknen. |
| [getByteData()](#getByteData--) | Ställer in ``‑data. |
| [setByteData(byte value)](#setByteData-byte-) | Ställer in ``‑data. |
| [toByte()](#toByte--) | Till byte. |
| [CloneTo(WmfPitchAndFamily that)](#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)](#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
### WmfPitchAndFamily() {#WmfPitchAndFamily--}
```
public WmfPitchAndFamily()
```


### WmfPitchAndFamily(byte byteData) {#WmfPitchAndFamily-byte-}
```
public WmfPitchAndFamily(byte byteData)
```


Initierar en ny instans av strukturen `WmfPitchAndFamily`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byteData | byte | Den ``‑data. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


Initierar en ny instans av strukturen `WmfPitchAndFamily`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pitch | byte | Pitchen. |
| familj | byte | Familjen. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Hämtar en egenskap för ett teckensnitt som beskriver dess allmänna utseende. Detta MÅSTE vara ett värde i FamilyFont‑uppräkningen

Värde: Familjen.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Hämtar en egenskap för ett teckensnitt som beskriver pitchen för tecknen. Detta MÅSTE vara ett värde i PitchFont‑uppräkningen

Värde: Tonhöjden.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


Ställer in ``‑data.

Värde: `` data.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


Ställer in ``‑data.

Värde: `` data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


Till byte.

**Returns:**
byte - Bytevärdet.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### Clone() {#Clone--}
```
public WmfPitchAndFamily Clone()
```




**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
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
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
