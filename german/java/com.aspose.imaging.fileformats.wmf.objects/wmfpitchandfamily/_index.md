---
title: "WmfPitchAndFamily"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das PitchAndFamily‑Objekt gibt die Pitch‑ und Family‑Eigenschaften eines Font‑Objekts an Abschnitt 2.2.1.2."
type: docs
weight: 54
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

Das PitchAndFamily‑Objekt gibt die Pitch‑ und Family‑Eigenschaften eines Font‑Objekts an (Abschnitt 2.2.1.2). Pitch bezieht sich auf die Breite der Zeichen, und Family bezieht sich auf das allgemeine Erscheinungsbild einer Schrift.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | Initialisiert eine neue Instanz der `WmfPitchAndFamily`‑Struktur. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | Initialisiert eine neue Instanz der `WmfPitchAndFamily`‑Struktur. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFamily()](#getFamily--) | Liest eine Eigenschaft einer Schrift, die ihr allgemeines Erscheinungsbild beschreibt. |
| [getPitch()](#getPitch--) | Liest eine Eigenschaft einer Schrift, die den Pitch der Zeichen beschreibt. |
| [getByteData()](#getByteData--) | Setzt die `` Daten. |
| [setByteData(byte value)](#setByteData-byte-) | Setzt die `` Daten. |
| [toByte()](#toByte--) | Zum Byte. |
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


Initialisiert eine neue Instanz der `WmfPitchAndFamily`‑Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| byteData | byte | Die `` Daten. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


Initialisiert eine neue Instanz der `WmfPitchAndFamily`‑Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pitch | byte | Der Pitch. |
| Familie | byte | Die Familie. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Ruft eine Eigenschaft einer Schriftart ab, die ihr allgemeines Erscheinungsbild beschreibt. Dies MUSS ein Wert in der FamilyFont‑Aufzählung sein.

Wert: Die Familie.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Ruft eine Eigenschaft einer Schriftart ab, die die Tonhöhe der Zeichen beschreibt. Dies MUSS ein Wert in der PitchFont‑Aufzählung sein.

Wert: Die Tonhöhe.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


Setzt die `` Daten.

Wert: Die `` data.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


Setzt die `` Daten.

Wert: Die `` data.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


Zum Byte.

**Returns:**
byte – Der Byte‑Wert.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
