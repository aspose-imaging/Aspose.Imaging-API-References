---
title: "TiffLong8Type"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Tiff unsigned 64‑Bit-Typ."
type: docs
weight: 17
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

Der Tiff unsigned 64‑Bit-Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | Initialisiert eine neue Instanz der [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type)-Klasse. |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | Initialisiert eine neue Instanz der [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValues()](#getValues--) | Liest die Werte. |
| [setValues(long[] value)](#setValues-long---) | Setzt die Werte. |
| [getValuesContainer()](#getValuesContainer--) | Liest den Werte-Container. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getValue()](#getValue--) | Liest den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Setzt den Wert, den dieser Datentyp enthält. |
| [getElementSize()](#getElementSize--) | Liest die Größe des Elements. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


Initialisiert eine neue Instanz der [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


Initialisiert eine neue Instanz der [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |
| Werte | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Liest die Werte.

Wert: Die Tag-Werte.

**Returns:**
long[] - die Werte.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


Setzt die Werte.

Wert: Die Tag-Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | die Werte. |

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


Setzt den Wert, den dieser Datentyp enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object | der Wert, den dieser Datentyp enthält. |

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
