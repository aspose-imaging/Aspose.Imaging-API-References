---
title: "TiffASCIIType"
second_title: "Aspose.Imaging för Java API-referens"
description: "tiff ascii-typen."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

tiff ascii-typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Initierar en ny instans av klassen `TiffASCIIType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Hämtar eller anger texten. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger texten. |
| [getCount()](#getCount--) | Hämtar antalet element. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getValue()](#getValue--) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Initierar en ny instans av klassen `TiffASCIIType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### getText() {#getText--}
```
public String getText()
```


Hämtar eller anger texten.

**Returns:**
java.lang.String - Texten.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Hämtar eller anger texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Texten. |

### getCount() {#getCount--}
```
public long getCount()
```


Hämtar antalet element.

**Returns:**
long - antalet element.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Hämtar taggtypen.

**Returns:**
int - Tagg‑typ.
### getValue() {#getValue--}
```
public Object getValue()
```


Hämtar eller anger värdet som den här datatypen innehåller.

**Returns:**
java.lang.Object - Värdet.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Hämtar eller anger värdet som den här datatypen innehåller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object | Värdet. |

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
