---
title: "TiffSLong8Type"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Tiff unsigned 64‑Bit-Typ."
type: docs
weight: 21
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffSLong8Type extends TiffCommonArrayType
```

Der Tiff unsigned 64‑Bit-Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffSLong8Type(int tagId)](#TiffSLong8Type-int-) | Initialisiert eine neue Instanz der [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValues()](#getValues--) | Liest die Werte. |
| [setValues(long[] values)](#setValues-long---) | Setzt die Werte. |
| [getValuesContainer()](#getValuesContainer--) | Liest den Werte-Container. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getValue()](#getValue--) | Liest den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest den Wert, den dieser Datentyp enthält. |
| [getElementSize()](#getElementSize--) | Liest die Größe des Elements. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffSLong8Type(int tagId) {#TiffSLong8Type-int-}
```
public TiffSLong8Type(int tagId)
```


Initialisiert eine neue Instanz der [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Liest die Werte.

Wert: Die Tag-Werte.

**Returns:**
long[] - die Werte.
### setValues(long[] values) {#setValues-long---}
```
public void setValues(long[] values)
```


Setzt die Werte.

Wert: Die Tag-Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Werte | long[] | Die Werte. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Liest den Werte-Container.

**Returns:**
com.aspose.ms.System.Array - der Werte-Container.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gibt den Tag-Typ zurück.

Wert: Der Tag-Typ.

**Returns:**
int - der Tag-Typ.
### getValue() {#getValue--}
```
public Object getValue()
```


Liest den Wert, den dieser Datentyp enthält.

**Returns:**
java.lang.Object - der Wert, den dieser Datentyp enthält.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Liest den Wert, den dieser Datentyp enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object | Der Wert, den dieser Datentyp enthält. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Liest die Größe des Elements.

**Returns:**
byte - Größe des Elements.
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
