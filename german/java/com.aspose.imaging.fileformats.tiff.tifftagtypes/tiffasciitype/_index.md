---
title: "TiffASCIIType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der tiff ASCII-Typ."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

Der tiff ASCII-Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Initialisiert eine neue Instanz der `TiffASCIIType`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) | Liest oder setzt den Text. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Text. |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente zurück. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getValue()](#getValue--) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Initialisiert eine neue Instanz der `TiffASCIIType`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Die Tag-ID. |

### getText() {#getText--}
```
public String getText()
```


Liest oder setzt den Text.

**Returns:**
java.lang.String - Der Text.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Liest oder setzt den Text.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Text. |

### getCount() {#getCount--}
```
public long getCount()
```


Gibt die Anzahl der Elemente zurück.

**Returns:**
long - Die Anzahl der Elemente.
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
