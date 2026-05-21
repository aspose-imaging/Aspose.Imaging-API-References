---
title: "TiffLong8Type"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tiff unsigned 64-bit-typen."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

Tiff unsigned 64-bit-typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | Initierar en ny instans av klassen [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | Initierar en ny instans av klassen [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValues()](#getValues--) | Hämtar värdena. |
| [setValues(long[] value)](#setValues-long---) | Ställer in värdena. |
| [getValuesContainer()](#getValuesContainer--) | Hämtar värdebehållaren. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getValue()](#getValue--) | Hämtar värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ställer in värdet som den här datatypen innehåller. |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


Initierar en ny instans av klassen [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


Initierar en ny instans av klassen [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |
| värden | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Hämtar värdena.

Värde: Taggvärdena.

**Returns:**
long[] - värdena.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


Ställer in värdena.

Värde: Taggvärdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | värdena. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Hämtar värdebehållaren.

**Returns:**
com.aspose.ms.System.Array - behållare för värdena.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Hämtar taggtypen.

Värde: Taggtypen.

**Returns:**
int - taggtypen.
### getValue() {#getValue--}
```
public Object getValue()
```


Hämtar värdet som den här datatypen innehåller.

**Returns:**
java.lang.Object - värdet som den här datatypen innehåller.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Ställer in värdet som den här datatypen innehåller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object | värdet som den här datatypen innehåller. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Hämtar elementets storlek.

**Returns:**
byte - storlek på elementet.
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
