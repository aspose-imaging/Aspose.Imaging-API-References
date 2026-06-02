---
title: "TiffRationalType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff rasyonel tipi."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffRationalType extends TiffCommonArrayType
```

tiff rasyonel tipi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffRationalType(int tagId)](#TiffRationalType-int-) | Yeni bir `TiffRationalType` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValues()](#getValues--) | Değerleri alır veya ayarlar. |
| [setValues(TiffRational[] value)](#setValues-com.aspose.imaging.fileformats.tiff.TiffRational---) | Değerleri alır veya ayarlar. |
| [getValuesContainer()](#getValuesContainer--) | Değer konteynerini alır. |
| [getElementSize()](#getElementSize--) | Elemanın bayt cinsinden boyutunu alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffRationalType(int tagId) {#TiffRationalType-int-}
```
public TiffRationalType(int tagId)
```


Yeni bir `TiffRationalType` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### getValues() {#getValues--}
```
public TiffRational[] getValues()
```


Değerleri alır veya ayarlar.

Değer: Değerler.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setValues(TiffRational[] value) {#setValues-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setValues(TiffRational[] value)
```


Değerleri alır veya ayarlar.

Değer: Değerler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Değer konteynerini alır.

Value: Değerler konteyneri.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Elemanın bayt cinsinden boyutunu alır.

Value: Elemanın bayt cinsinden boyutu.

**Returns:**
byte
### getTagType() {#getTagType--}
```
public int getTagType()
```


Etiket tipini alır.

Değer: Etiket türü.

**Returns:**
int
### getValue() {#getValue--}
```
public Object getValue()
```


Bu veri tipinin içerdiği değeri alır veya ayarlar.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Bu veri tipinin içerdiği değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

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
