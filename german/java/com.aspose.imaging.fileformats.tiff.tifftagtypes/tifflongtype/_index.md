---
title: "TiffLongType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der tiff Long-Typ."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflongtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffLongType extends TiffCommonArrayType
```

Der tiff Long-Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffLongType(int tagId)](#TiffLongType-int-) | Initialisiert eine neue Instanz der `TiffLongType` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValues()](#getValues--) | Liest oder setzt die Werte. |
| [setValues(long[] value)](#setValues-long---) | Liest oder setzt die Werte. |
| [getValuesContainer()](#getValuesContainer--) | Liest den Werte-Container. |
| [getElementSize()](#getElementSize--) | Gibt die Elementgröße in Bytes zurück. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getValue()](#getValue--) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffLongType(int tagId) {#TiffLongType-int-}
```
public TiffLongType(int tagId)
```


Initialisiert eine neue Instanz der `TiffLongType` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### getValues() {#getValues--}
```
public long[] getValues()
```


Liest oder setzt die Werte.

Wert: Die Werte.

**Returns:**
long[]
### setValues(long[] value) {#setValues-long---}
```
public void setValues(long[] value)
```


Liest oder setzt die Werte.

Wert: Die Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Liest den Werte-Container.

Wert: Der Werte-Container.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Gibt die Elementgröße in Bytes zurück.

Wert: Die Elementgröße in Bytes.

**Returns:**
byte
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gibt den Tag-Typ zurück.

Wert: Der Tag-Typ.

**Returns:**
int
### getValue() {#getValue--}
```
public Object getValue()
```


Liest oder setzt den Wert, den dieser Datentyp enthält.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Liest oder setzt den Wert, den dieser Datentyp enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Schreibt die zusätzlichen Tag-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Der Datenstream. |

**Returns:**
long - Die tatsächlich geschriebenen Bytes.
