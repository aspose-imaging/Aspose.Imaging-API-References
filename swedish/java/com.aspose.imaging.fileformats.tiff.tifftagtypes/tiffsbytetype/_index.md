---
title: "TiffSByteType"
second_title: "Aspose.Imaging för Java API-referens"
description: "tiff signed byte-typen."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffSByteType extends TiffCommonArrayType
```

tiff signed byte-typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffSByteType(int tagId)](#TiffSByteType-int-) | Initierar en ny instans av klassen `TiffSByteType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValues()](#getValues--) | Hämtar eller anger värdena. |
| [setValues(byte[] value)](#setValues-byte---) | Hämtar eller anger värdena. |
| [getValuesContainer()](#getValuesContainer--) | Hämtar värdebehållaren. |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek i byte. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getValue()](#getValue--) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Hämtar eller anger värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffSByteType(int tagId) {#TiffSByteType-int-}
```
public TiffSByteType(int tagId)
```


Initierar en ny instans av klassen `TiffSByteType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


Hämtar eller anger värdena.

Värde: Data.

**Returns:**
byte[]
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


Hämtar eller anger värdena.

Värde: Data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

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
