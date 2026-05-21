---
title: "WmfPitchAndFamily"
second_title: "Aspose.Imaging for Java API Referansı"
description: "PitchAndFamily nesnesi, bir Font nesnesinin pitch ve family özelliklerini bölüm 2.2.1.2'de belirtir."
type: docs
weight: 54
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

PitchAndFamily nesnesi, bir Font nesnesinin pitch ve family özelliklerini (bölüm 2.2.1.2) belirtir. Pitch, karakterlerin genişliğini, family ise bir fontun genel görünümünü ifade eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | `WmfPitchAndFamily` yapısının yeni bir örneğini başlatır. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | `WmfPitchAndFamily` yapısının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamily()](#getFamily--) | Bir fontun genel görünümünü tanımlayan bir özelliği alır. |
| [getPitch()](#getPitch--) | Karakterlerin pitch'ini tanımlayan bir font özelliğini alır. |
| [getByteData()](#getByteData--) | `` verisini ayarlar. |
| [setByteData(byte value)](#setByteData-byte-) | `` verisini ayarlar. |
| [toByte()](#toByte--) | Byte'a. |
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


`WmfPitchAndFamily` yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| byteData | byte | `` verisi. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


`WmfPitchAndFamily` yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pitch | byte | Pitch. |
| aile | byte | Aile. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Bir yazı tipinin genel görünümünü tanımlayan bir özelliği alır. Bu MUST FamilyFont sayımında bir değer olmalıdır.

Değer: Aile.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Karakterlerin perdesini tanımlayan bir yazı tipi özelliğini alır. Bu MUST PitchFont sayımında bir değer olmalıdır.

Değer: Perde.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


`` verisini ayarlar.

Değer: `` verisi.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


`` verisini ayarlar.

Değer: `` verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


Byte'a.

**Returns:**
byte - Bayt değeri.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
