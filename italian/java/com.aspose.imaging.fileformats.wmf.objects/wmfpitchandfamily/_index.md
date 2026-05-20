---
title: "WmfPitchAndFamily"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto PitchAndFamily specifica le proprietà di pitch e family di un oggetto Font sezione 2.2.1.2."
type: docs
weight: 54
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

L'oggetto PitchAndFamily specifica le proprietà di pitch e family di un oggetto Font (sezione 2.2.1.2). Il pitch si riferisce alla larghezza dei caratteri, e la family si riferisce all'aspetto generale di un font.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | Inizializza una nuova istanza della struct `WmfPitchAndFamily`. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | Inizializza una nuova istanza della struct `WmfPitchAndFamily`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamily()](#getFamily--) | Ottiene una proprietà di un font che ne descrive l'aspetto generale. |
| [getPitch()](#getPitch--) | Ottiene una proprietà di un font che descrive il pitch dei caratteri. |
| [getByteData()](#getByteData--) | Imposta i dati ``. |
| [setByteData(byte value)](#setByteData-byte-) | Imposta i dati ``. |
| [toByte()](#toByte--) | Al byte. |
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


Inizializza una nuova istanza della struct `WmfPitchAndFamily`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| byteData | byte | I dati ``. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


Inizializza una nuova istanza della struct `WmfPitchAndFamily`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pitch | byte | Il pitch. |
| famiglia | byte | La famiglia. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Ottiene una proprietà di un carattere che descrive il suo aspetto generale. Questo DEVE essere un valore nell'enumerazione FamilyFont.

Valore: La famiglia.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Ottiene una proprietà di un carattere che descrive il pitch dei caratteri. Questo DEVE essere un valore nell'enumerazione PitchFont.

Valore: Il pitch.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


Imposta i dati ``.

Valore: I `` dati.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


Imposta i dati ``.

Valore: I `` dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


Al byte.

**Returns:**
byte - Il valore byte.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
