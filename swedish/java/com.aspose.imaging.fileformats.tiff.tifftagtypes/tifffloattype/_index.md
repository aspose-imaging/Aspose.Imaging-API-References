---
title: "TiffFloatType"
second_title: "Aspose.Imaging för Java API-referens"
description: "tiff float-typen."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffFloatType extends TiffCommonArrayType
```

tiff float-typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffFloatType(int tagId)](#TiffFloatType-int-) | Initierar en ny instans av klassen `TiffFloatType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValues()](#getValues--) | Hämtar värdena. |
| [setValues(float[] value)](#setValues-float---) | Ställer in värdena. |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek i byte. |
| [getValuesContainer()](#getValuesContainer--) | Hämtar värdebehållaren. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getValue()](#getValue--) | Hämtar värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ställer in värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffFloatType(int tagId) {#TiffFloatType-int-}
```
public TiffFloatType(int tagId)
```


Initierar en ny instans av klassen `TiffFloatType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### getValues() {#getValues--}
```
public float[] getValues()
```


Hämtar värdena.

**Returns:**
float[] - Värdena.
### setValues(float[] value) {#setValues-float---}
```
public void setValues(float[] value)
```


Ställer in värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | Värdena. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Hämtar elementets storlek i byte.

**Returns:**
byte - Elementets storlek i byte.
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Hämtar värdebehållaren.

**Returns:**
com.aspose.ms.System.Array - Värdebehållaren.
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


Hämtar värdet som den här datatypen innehåller.

**Returns:**
java.lang.Object - Värdet.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Ställer in värdet som den här datatypen innehåller.

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
