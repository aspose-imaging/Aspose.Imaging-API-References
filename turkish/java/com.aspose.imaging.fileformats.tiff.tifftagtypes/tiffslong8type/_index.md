---
title: "TiffSLong8Type"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Tiff işaretsiz 64-bit türü."
type: docs
weight: 21
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffSLong8Type extends TiffCommonArrayType
```

Tiff işaretsiz 64-bit türü.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffSLong8Type(int tagId)](#TiffSLong8Type-int-) | Yeni bir [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValues()](#getValues--) | Değerleri alır. |
| [setValues(long[] values)](#setValues-long---) | Değerleri ayarlar. |
| [getValuesContainer()](#getValuesContainer--) | Değer konteynerini alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır. |
| [getElementSize()](#getElementSize--) | Elemanın boyutunu alır. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffSLong8Type(int tagId) {#TiffSLong8Type-int-}
```
public TiffSLong8Type(int tagId)
```


Yeni bir [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Değerleri alır.

Değer: Etiket değerleri.

**Returns:**
long[] - değerler.
### setValues(long[] values) {#setValues-long---}
```
public void setValues(long[] values)
```


Değerleri ayarlar.

Değer: Etiket değerleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değerler | long[] | Değerler. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Değer konteynerini alır.

**Returns:**
com.aspose.ms.System.Array - değerler konteyneri.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Etiket tipini alır.

Değer: Etiket türü.

**Returns:**
int - etiket türü.
### getValue() {#getValue--}
```
public Object getValue()
```


Bu veri tipinin içerdiği değeri alır.

**Returns:**
java.lang.Object - bu veri tipinin içerdiği değer.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Bu veri tipinin içerdiği değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Bu veri tipinin içerdiği değer. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Elemanın boyutunu alır.

**Returns:**
byte - öğenin boyutu.
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
