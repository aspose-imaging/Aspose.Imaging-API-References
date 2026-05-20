---
title: "TiffUndefinedType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der tiff undefinierte Typ."
type: docs
weight: 26
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

Der tiff undefinierte Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | Initialisiert eine neue Instanz der `TiffUndefinedType`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getData()](#getData--) | Liest oder setzt die Daten. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt die Daten. |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente zurück. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getValue()](#getValue--) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


Initialisiert eine neue Instanz der `TiffUndefinedType`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### getData() {#getData--}
```
public byte[] getData()
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


Gibt die Anzahl der Elemente zurück.

Wert: Die Anzahl der Elemente.

**Returns:**
long
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
