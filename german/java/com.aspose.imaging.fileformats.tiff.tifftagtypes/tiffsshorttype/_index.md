---
title: "TiffSShortType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der tiff signierte short-Typ."
type: docs
weight: 24
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffSShortType extends TiffCommonArrayType
```

Der tiff signierte short-Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffSShortType(int tagId)](#TiffSShortType-int-) | Initialisiert eine neue Instanz der `TiffSShortType`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValues()](#getValues--) | Liest oder setzt die Werte. |
| [setValues(short[] value)](#setValues-short---) | Liest oder setzt die Werte. |
| [getValuesContainer()](#getValuesContainer--) | Liest den Werte-Container. |
| [getElementSize()](#getElementSize--) | Gibt die Elementgröße in Bytes zurück. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getValue()](#getValue--) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffSShortType(int tagId) {#TiffSShortType-int-}
```
public TiffSShortType(int tagId)
```


Initialisiert eine neue Instanz der `TiffSShortType`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### getValues() {#getValues--}
```
public short[] getValues()
```


Liest oder setzt die Werte.

Wert: Die Werte.

**Returns:**
short[]
### setValues(short[] value) {#setValues-short---}
```
public void setValues(short[] value)
```


Liest oder setzt die Werte.

Wert: Die Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short[] |  |

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
