---
title: "TiffByteType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der tiff Byte-Typ."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffByteType extends TiffCommonArrayType
```

Der tiff Byte-Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffByteType(int tagId)](#TiffByteType-int-) | Initialisiert eine neue Instanz der `TiffByteType` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValues()](#getValues--) | Liest oder setzt die Werte. |
| [setValues(byte[] value)](#setValues-byte---) | Liest oder setzt die Werte. |
| [getValuesContainer()](#getValuesContainer--) | Liest den Werte-Container. |
| [getElementSize()](#getElementSize--) | Gibt die Elementgröße in Bytes zurück. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getValue()](#getValue--) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffByteType(int tagId) {#TiffByteType-int-}
```
public TiffByteType(int tagId)
```


Initialisiert eine neue Instanz der `TiffByteType` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


Liest oder setzt die Werte.

**Returns:**
byte[] - Die Daten.
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


Liest oder setzt die Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] | Die Daten. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Liest den Werte-Container.

**Returns:**
com.aspose.ms.System.Array - Der Werte-Container.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Gibt die Elementgröße in Bytes zurück.

**Returns:**
byte - Die Elementgröße in Bytes.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gibt den Tag-Typ zurück.

**Returns:**
int - Der Tag-Typ.
### getValue() {#getValue--}
```
public Object getValue()
```


Liest oder setzt den Wert, den dieser Datentyp enthält.

**Returns:**
java.lang.Object - Der Wert.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Liest oder setzt den Wert, den dieser Datentyp enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object | Der Wert. |

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
