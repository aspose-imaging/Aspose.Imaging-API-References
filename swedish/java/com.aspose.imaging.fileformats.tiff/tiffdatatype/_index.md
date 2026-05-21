---
title: "TiffDataType"
second_title: "Aspose.Imaging för Java API-referens"
description: "TIFF-datatypen."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

TIFF-datatypen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek i byte. |
| [getDataSize()](#getDataSize--) | Hämtar taggvärdets storlek. |
| [getCount()](#getCount--) | Hämtar antalet element. |
| [getId()](#getId--) | Hämtar tagg‑id som nummer. |
| [getTagId()](#getTagId--) | Hämtar tagg‑id. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | Hämtar datastorleken justerad till 4‑byte (int) eller 8‑byte (long) gräns. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Hämtar den extra taggvärdesstorleken i byte (om taggen inte får plats med hela taggvärdet). |
| [getValue()](#getValue--) | Hämtar värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ställer in värdet som den här datatypen innehåller. |
| [isValid()](#isValid--) | Hämtar ett värde som indikerar om taggdata är giltig. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Läser taggdata. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Utför en djup kloning av denna instans. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Skriver taggdata. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
| [toString()](#toString--) | Returnerar en `System.String` som representerar denna instans. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Hämtar elementets storlek i byte.

**Returns:**
byte - elementets storlek i byte.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Hämtar taggvärdets storlek.

**Returns:**
long - taggvärdets storlek.
### getCount() {#getCount--}
```
public abstract long getCount()
```


Hämtar antalet element.

Värde: Antalet element.

**Returns:**
long - antalet element.
### getId() {#getId--}
```
public final int getId()
```


Hämtar tagg‑id som nummer.

**Returns:**
int - tagg‑id som nummer.
### getTagId() {#getTagId--}
```
public int getTagId()
```


Hämtar tagg‑id.

**Returns:**
int - Tagg‑id.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Hämtar taggtypen.

**Returns:**
int - Tagg‑typ.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


Hämtar datastorleken justerad till 4‑byte (int) eller 8‑byte (long) gräns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sizeOfTagValue | byte | Storlek på taggvärde. |

**Returns:**
long - den justerade datastorleken i byte.
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Hämtar den extra taggvärdesstorleken i byte (om taggen inte får plats med hela taggvärdet).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sizeOfTagValue | byte | Storlek på taggvärde: 4 eller 8 för BigTiff. |

**Returns:**
long - den extra datastorleken i byte.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Hämtar värdet som den här datatypen innehåller.

**Returns:**
java.lang.Object - Värdet.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Ställer in värdet som den här datatypen innehåller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object | Värdet. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Hämtar ett värde som indikerar om taggdata är giltig. Den giltiga taggen innehåller data som kan bevaras. Den ogiltiga taggen kan inte lagras.

**Returns:**
boolean - `true` om taggdata är giltig; annars `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Läser taggdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Datastreamen. |
| position | long | Taggpositionen. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Ett objekt att jämföra med denna instans. |

**Returns:**
int - En 32-bitars heltal med tecken som indikerar den relativa ordningen för de objekt som jämförs. Returvärdet har följande betydelser: Värde Betydelse Mindre än noll Detta objekt är mindre än `obj`. Noll Detta objekt är lika med `obj`. Större än noll Detta objekt är större än `obj`.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Utför en djup kloning av denna instans.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Skriver taggdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Datastreamen. |
| additionalDataOffset | long | Offseten att skriva ytterligare data till. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Skriver den extra taggdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Datastreamen. |

**Returns:**
long - De faktiska skrivna byten.
### toString() {#toString--}
```
public String toString()
```


Returnerar en `System.String` som representerar denna instans.

**Returns:**
java.lang.String - En `System.String` som representerar denna instans.
