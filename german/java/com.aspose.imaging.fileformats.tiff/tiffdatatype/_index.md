---
title: "TiffDataType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der TIFF‑Datentyp."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Der TIFF‑Datentyp.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getElementSize()](#getElementSize--) | Gibt die Elementgröße in Bytes zurück. |
| [getDataSize()](#getDataSize--) | Gibt die Größe des Tag-Werts zurück. |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente zurück. |
| [getId()](#getId--) | Gibt die Tag-ID als Zahl zurück. |
| [getTagId()](#getTagId--) | Gibt die Tag-ID zurück. |
| [getTagType()](#getTagType--) | Gibt den Tag-Typ zurück. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | Gibt die Datenmenge ausgerichtet an einer 4-Byte-(int)- oder 8-Byte-(long)-Grenze zurück. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Gibt die zusätzliche Tag-Wertgröße in Bytes zurück (falls das Tag den gesamten Tag-Wert nicht aufnehmen kann). |
| [getValue()](#getValue--) | Liest den Wert, den dieser Datentyp enthält. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Setzt den Wert, den dieser Datentyp enthält. |
| [isValid()](#isValid--) | Liefert einen Wert, der angibt, ob Tag-Daten gültig sind. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Liest die Tag-Daten. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt eine Ganzzahl zurück, die angibt, ob die aktuelle Instanz vor, nach oder an derselben Position in der Sortierreihenfolge wie das andere Objekt liegt. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Schreibt die Tag-Daten. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
| [toString()](#toString--) | Gibt einen `System.String` zurück, der diese Instanz darstellt. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Gibt die Elementgröße in Bytes zurück.

**Returns:**
byte - die Elementgröße in Bytes.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Gibt die Größe des Tag-Werts zurück.

**Returns:**
long - die Größe des Tag-Werts.
### getCount() {#getCount--}
```
public abstract long getCount()
```


Gibt die Anzahl der Elemente zurück.

Wert: Die Anzahl der Elemente.

**Returns:**
long - die Anzahl der Elemente.
### getId() {#getId--}
```
public final int getId()
```


Gibt die Tag-ID als Zahl zurück.

**Returns:**
int - Tag-ID als Zahl.
### getTagId() {#getTagId--}
```
public int getTagId()
```


Gibt die Tag-ID zurück.

**Returns:**
int - Die Tag-ID.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Gibt den Tag-Typ zurück.

**Returns:**
int - Der Tag-Typ.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


Gibt die Datenmenge ausgerichtet an einer 4-Byte-(int)- oder 8-Byte-(long)-Grenze zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sizeOfTagValue | byte | Größe des Tag-Werts. |

**Returns:**
long - Die ausgerichtete Datengröße in Bytes.
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
public abstract Object getValue()
```


Liest den Wert, den dieser Datentyp enthält.

**Returns:**
java.lang.Object - Der Wert.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Setzt den Wert, den dieser Datentyp enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object | Der Wert. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Liefert einen Wert, der angibt, ob Tag-Daten gültig sind. Das gültige Tag enthält Daten, die erhalten bleiben können. Das ungültige Tag kann nicht gespeichert werden.

**Returns:**
boolean - `true`, wenn Tag-Daten gültig sind; andernfalls `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Liest die Tag-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Der Datenstream. |
| Position | long | Die Tag-Position. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt eine Ganzzahl zurück, die angibt, ob die aktuelle Instanz vor, nach oder an derselben Position in der Sortierreihenfolge wie das andere Objekt liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Ein Objekt zum Vergleichen mit dieser Instanz. |

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer, der die relative Reihenfolge der zu vergleichenden Objekte angibt. Der Rückgabewert hat folgende Bedeutungen: Wert Bedeutung Kleiner als Null Diese Instanz ist kleiner als `obj`. Null Diese Instanz ist gleich `obj`. Größer als Null Diese Instanz ist größer als `obj`.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Erstellt eine tiefe Kopie dieser Instanz.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Schreibt die Tag-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Der Datenstream. |
| additionalDataOffset | long | Der Offset, zu dem zusätzliche Daten geschrieben werden. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
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
