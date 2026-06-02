---
title: "TiffUnknownType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der unbekannte tiff Typ."
type: docs
weight: 27
url: /de/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

Der unbekannte TIFF-Typ. Falls das TIFF-Tag nicht erkannt werden kann, wird dieser Typ instanziiert.

Hinweis: Der `TiffUnknownType` wird nicht zurück in den Stream serialisiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Initialisiert eine neue Instanz der `TiffUnknownType`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente zurück. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Liefert den Offsetwert für zusätzliche Daten oder den Wert selbst, falls die Anzahl 1 ist. |
| [getStream()](#getStream--) | Liefert den Stream, aus dem zusätzliche Daten gelesen werden. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Gibt die zusätzliche Tag-Wertgröße in Bytes zurück (falls das Tag den gesamten Tag-Wert nicht aufnehmen kann). |
| [getValue()](#getValue--) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest oder setzt den Wert, den dieser Datentyp enthält. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
| [toString()](#toString--) | Gibt einen `System.String` zurück, der diese Instanz darstellt. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Initialisiert eine neue Instanz der `TiffUnknownType`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Der Stream, aus dem gelesen wird. |
| tagType | int | Typ des Tags. |
| tagId | int | Die Tag-ID. |
| count | long | Der Zählwert. |
| offsetOrValue | long | Der Offset oder der Wert. |

### getCount() {#getCount--}
```
public long getCount()
```


Gibt die Anzahl der Elemente zurück.

Wert: Die Anzahl der Elemente.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Liefert den Offsetwert für zusätzliche Daten oder den Wert selbst, falls die Anzahl 1 ist.

Wert: Der Offset oder der Wert.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Liefert den Stream, aus dem zusätzliche Daten gelesen werden.

Wert: Der Stream, aus dem Daten gelesen werden.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gibt den Tag-Typ zurück.

Wert: Der Tag-Typ.

**Returns:**
int
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Gibt die zusätzliche Tag-Wertgröße in Bytes zurück (falls das Tag den gesamten Tag-Wert nicht aufnehmen kann).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sizeOfTagValue | byte | Größe des Tag-Werts: 4 oder 8 für BigTiff. |

**Returns:**
long - Die zusätzliche Datengröße in Bytes.
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
### toString() {#toString--}
```
public String toString()
```


Gibt einen `System.String` zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein `System.String`, der diese Instanz darstellt.
