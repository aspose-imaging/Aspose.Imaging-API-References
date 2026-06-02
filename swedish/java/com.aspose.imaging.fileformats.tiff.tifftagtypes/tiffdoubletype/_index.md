---
title: "TiffDoubleType"
second_title: "Aspose.Imaging för Java API-referens"
description: "tiff double-typen."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

tiff double-typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Initierar en ny instans av klassen `TiffDoubleType`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValues()](#getValues--) | Hämtar värdena. |
| [setValues(double[] value)](#setValues-double---) | Ställer in värdena. |
| [getValuesContainer()](#getValuesContainer--) | Hämtar värdebehållaren. |
| [getTagType()](#getTagType--) | Hämtar taggtypen. |
| [getElementSize()](#getElementSize--) | Hämtar elementets storlek i byte. |
| [getValue()](#getValue--) | Hämtar värdet som den här datatypen innehåller. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ställer in värdet som den här datatypen innehåller. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Initierar en ny instans av klassen `TiffDoubleType`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Tagg‑id‑et. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Hämtar värdena.

**Returns:**
double[] - Värdena.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Ställer in värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] | Värdena. |

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
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Hämtar elementets storlek i byte.

**Returns:**
byte - Elementets storlek i byte.
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
