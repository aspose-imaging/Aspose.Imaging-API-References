---
title: "TiffSRationalType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den tiff signerade rationella typen."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffSRationalType extends TiffCommonArrayType
```

Den tiff signerade rationella typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffSRationalType(int tagId)](#TiffSRationalType-int-) | Initierar en ny instans av klassen `TiffSRationalType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValues()](#getValues--) | Hämtar eller anger värdena. |
| [setValues(TiffSRational[] value)](#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Hämtar eller anger värdena. |
| [getValuesContainer()](#getValuesContainer--) | Hämtar värdebehållaren. |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek i byte. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getValue()](#getValue--) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffSRationalType(int tagId) {#TiffSRationalType-int-}
```
public TiffSRationalType(int tagId)
```


Initierar en ny instans av klassen `TiffSRationalType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### getValues() {#getValues--}
```
public TiffSRational[] getValues()
```


Hämtar eller anger värdena.

Värde: Värdena.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[]
### setValues(TiffSRational[] value) {#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void setValues(TiffSRational[] value)
```


Hämtar eller anger värdena.

Värde: Värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

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
