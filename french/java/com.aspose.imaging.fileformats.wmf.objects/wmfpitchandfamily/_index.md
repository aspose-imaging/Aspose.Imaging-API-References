---
title: "WmfPitchAndFamily"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet PitchAndFamily spécifie les propriétés de pas et de famille d'un objet Font section 2.2.1.2."
type: docs
weight: 54
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

L'objet PitchAndFamily spécifie les propriétés de pas et de famille d'un objet Font (section 2.2.1.2). Le pas fait référence à la largeur des caractères, et la famille fait référence à l'apparence générale d'une police.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | Initialise une nouvelle instance de la structure `WmfPitchAndFamily`. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | Initialise une nouvelle instance de la structure `WmfPitchAndFamily`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFamily()](#getFamily--) | Obtient une propriété d'une police qui décrit son apparence générale. |
| [getPitch()](#getPitch--) | Obtient une propriété d'une police qui décrit le pas des caractères. |
| [getByteData()](#getByteData--) | Définit les données ``. |
| [setByteData(byte value)](#setByteData-byte-) | Définit les données ``. |
| [toByte()](#toByte--) | Vers l'octet. |
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


Initialise une nouvelle instance de la structure `WmfPitchAndFamily`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| byteData | byte | Les données ``. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


Initialise une nouvelle instance de la structure `WmfPitchAndFamily`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pitch | byte | Le pas. |
| famille | byte | La famille. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Obtient une propriété d'une police qui décrit son apparence générale. Ceci DOIT être une valeur dans l'énumération FamilyFont.

Valeur : la famille.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Obtient une propriété d'une police qui décrit le pas des caractères. Ceci DOIT être une valeur dans l'énumération PitchFont.

Valeur : le pas.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


Définit les données ``.

Valeur : les `` data.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


Définit les données ``.

Valeur : les `` data.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


Vers l'octet.

**Returns:**
octet - La valeur d'octet.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
