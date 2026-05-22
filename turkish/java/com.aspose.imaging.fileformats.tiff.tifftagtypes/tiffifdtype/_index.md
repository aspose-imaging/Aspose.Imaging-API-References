---
title: "TiffIfdType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TIFF Exif görüntü dosyası dizini türü sınıfını temsil eder."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffifdtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffIfdType extends TiffCommonArrayType
```

TIFF Exif görüntü dosyası dizini türü sınıfını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffIfdType(int tagId)](#TiffIfdType-int-) | Yeni bir `TiffIfdType` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValues()](#getValues--) | Değerleri alır veya ayarlar. |
| [setValues(long[] value)](#setValues-long---) | Değerleri alır veya ayarlar. |
| [getValuesContainer()](#getValuesContainer--) | Değer konteynerini alır. |
| [getElementSize()](#getElementSize--) | Elemanın bayt cinsinden boyutunu alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffIfdType(int tagId) {#TiffIfdType-int-}
```
public TiffIfdType(int tagId)
```


Yeni bir `TiffIfdType` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### getValues() {#getValues--}
```
public long[] getValues()
```


Değerleri alır veya ayarlar.

Değer: Değerler.

**Returns:**
long[]
### setValues(long[] value) {#setValues-long---}
```
public void setValues(long[] value)
```


Değerleri alır veya ayarlar.

Değer: Değerler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] |  |

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
