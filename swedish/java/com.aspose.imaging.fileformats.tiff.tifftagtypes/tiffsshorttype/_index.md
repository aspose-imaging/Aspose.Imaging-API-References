---
title: "TiffSShortType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den tiff signerade korta typen."
type: docs
weight: 24
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffSShortType extends TiffCommonArrayType
```

Den tiff signerade korta typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffSShortType(int tagId)](#TiffSShortType-int-) | Initierar en ny instans av klassen `TiffSShortType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValues()](#getValues--) | Hämtar eller anger värdena. |
| [setValues(short[] value)](#setValues-short---) | Hämtar eller anger värdena. |
| [getValuesContainer()](#getValuesContainer--) | Hämtar värdebehållaren. |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek i byte. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getValue()](#getValue--) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffSShortType(int tagId) {#TiffSShortType-int-}
```
public TiffSShortType(int tagId)
```


Initierar en ny instans av klassen `TiffSShortType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### getValues() {#getValues--}
```
public short[] getValues()
```


Hämtar eller anger värdena.

Värde: Värdena.

**Returns:**
short[]
### setValues(short[] value) {#setValues-short---}
```
public void setValues(short[] value)
```


Hämtar eller anger värdena.

Värde: Värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Hämtar värdebehållaren.

Värde: Behållaren för värdena.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Hämtar elementets storlek i byte.

Värde: Elementets storlek i byte.

**Returns:**
byte
### getTagType() {#getTagType--}
```
public int getTagType()
```


Hämtar taggtypen.

Värde: Taggtypen.

**Returns:**
int
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
