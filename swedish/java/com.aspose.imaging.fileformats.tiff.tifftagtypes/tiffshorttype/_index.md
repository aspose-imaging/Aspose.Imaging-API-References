---
title: "TiffShortType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den tiff korta typen."
type: docs
weight: 25
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffShortType extends TiffCommonArrayType
```

Den tiff korta typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffShortType(int tagId)](#TiffShortType-int-) | Initierar en ny instans av klassen `TiffShortType`. |
| [TiffShortType(int tagId, int[] values)](#TiffShortType-int-int---) | Initierar en ny instans av klassen `TiffShortType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValues()](#getValues--) | Hämtar eller anger data. |
| [setValues(int[] value)](#setValues-int---) | Hämtar eller anger data. |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek i byte. |
| [getValuesContainer()](#getValuesContainer--) | Hämtar värdebehållaren. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getValue()](#getValue--) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffShortType(int tagId) {#TiffShortType-int-}
```
public TiffShortType(int tagId)
```


Initierar en ny instans av klassen `TiffShortType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### TiffShortType(int tagId, int[] values) {#TiffShortType-int-int---}
```
public TiffShortType(int tagId, int[] values)
```


Initierar en ny instans av klassen `TiffShortType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |
| värden | int[] |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Hämtar eller anger data.

Värde: Data.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Hämtar eller anger data.

Värde: Data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Hämtar elementets storlek i byte.

Värde: Elementets storlek i byte.

**Returns:**
byte
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Hämtar värdebehållaren.

Värde: Behållaren för värdena.

**Returns:**
com.aspose.ms.System.Array
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
