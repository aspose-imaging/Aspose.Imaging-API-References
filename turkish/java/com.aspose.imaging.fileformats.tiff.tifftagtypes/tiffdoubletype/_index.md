---
title: "TiffDoubleType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff double türü."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

tiff double türü.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Yeni bir `TiffDoubleType` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValues()](#getValues--) | Değerleri alır. |
| [setValues(double[] value)](#setValues-double---) | Değerleri ayarlar. |
| [getValuesContainer()](#getValuesContainer--) | Değer konteynerini alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getElementSize()](#getElementSize--) | Elemanın bayt cinsinden boyutunu alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Yeni bir `TiffDoubleType` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Değerleri alır.

**Returns:**
double[] - Değerler.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Değerleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] | Değerler. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Değer konteynerini alır.

**Returns:**
com.aspose.ms.System.Array - Değer konteyneri.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Etiket tipini alır.

**Returns:**
int - Etiket türü.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Elemanın bayt cinsinden boyutunu alır.

**Returns:**
byte - Elemanın bayt cinsinden boyutu.
### getValue() {#getValue--}
```
public Object getValue()
```


Bu veri tipinin içerdiği değeri alır.

**Returns:**
java.lang.Object - Değer.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Bu veri tipinin içerdiği değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Değer. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Ek etiket verisini yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Veri akışı. |

**Returns:**
long - Gerçek yazılan bayt sayısı.
