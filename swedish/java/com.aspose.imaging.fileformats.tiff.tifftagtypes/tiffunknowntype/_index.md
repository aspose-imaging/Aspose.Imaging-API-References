---
title: "TiffUnknownType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den okända tiff-typen."
type: docs
weight: 27
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

Den okända tiff-typen. Om tiff-taggen inte kan identifieras skapas denna typ.

Observera att `TiffUnknownType` inte serialiseras tillbaka till strömmen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Initierar en ny instans av klassen `TiffUnknownType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar antalet element. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Hämtar förskjutningsvärdet för ytterligare data eller själva värdet om antalet är 1. |
| [getStream()](#getStream--) | Hämtar strömmen för att läsa ytterligare data från. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Hämtar den extra taggvärdesstorleken i byte (om taggen inte får plats med hela taggvärdet). |
| [getValue()](#getValue--) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
| [toString()](#toString--) | Returnerar en `System.String` som representerar denna instans. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Initierar en ny instans av klassen `TiffUnknownType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Strömmen att läsa från. |
| tagType | int | Typ av taggen. |
| tagId | int | Tagg‑id‑et. |
| antal | long | Räknevärdet. |
| offsetOrValue | long | Förskjutningen eller värdet. |

### getCount() {#getCount--}
```
public long getCount()
```


Hämtar antalet element.

Värde: Antalet element.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Hämtar förskjutningsvärdet för ytterligare data eller själva värdet om antalet är 1.

Värde: Förskjutningen eller värdet.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Hämtar strömmen för att läsa ytterligare data från.

Värde: Strömmen att läsa data från.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Hämtar taggtypen.

Värde: Taggtypen.

**Returns:**
int
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
public Object getValue()
```


Hämtar eller anger värdet som den här datatypen innehåller.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Hämtar eller anger värdet som den här datatypen innehåller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
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
