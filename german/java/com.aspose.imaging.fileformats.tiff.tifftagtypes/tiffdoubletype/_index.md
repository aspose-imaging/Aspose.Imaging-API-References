---
title: "TiffDoubleType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der tiff Double-Typ."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

Der tiff Double-Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Initialisiert eine neue Instanz der `TiffDoubleType`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValues()](#getValues--) | Liest die Werte. |
| [setValues(double[] value)](#setValues-double---) | Setzt die Werte. |
| [getValuesContainer()](#getValuesContainer--) | Liest den Werte-Container. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getElementSize()](#getElementSize--) | Gibt die Elementgröße in Bytes zurück. |
| [getValue()](#getValue--) | Liest den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Setzt den Wert, den dieser Datentyp enthält. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Initialisiert eine neue Instanz der `TiffDoubleType`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Liest die Werte.

**Returns:**
double[] - Die Werte.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Setzt die Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] | Die Werte. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Liest den Werte-Container.

**Returns:**
com.aspose.ms.System.Array - Der Werte-Container.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gibt den Tag-Typ zurück.

**Returns:**
int - Der Tag-Typ.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Gibt die Elementgröße in Bytes zurück.

**Returns:**
byte - Die Elementgröße in Bytes.
### getValue() {#getValue--}
```
public Object getValue()
```


Liest den Wert, den dieser Datentyp enthält.

**Returns:**
java.lang.Object - Der Wert.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Setzt den Wert, den dieser Datentyp enthält.

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
