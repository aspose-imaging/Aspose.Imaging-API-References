---
title: "TiffSShortType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Tiff işaretli kısa tür."
type: docs
weight: 24
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffSShortType extends TiffCommonArrayType
```

Tiff işaretli kısa tür.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffSShortType(int tagId)](#TiffSShortType-int-) | Yeni bir `TiffSShortType` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValues()](#getValues--) | Değerleri alır veya ayarlar. |
| [setValues(short[] value)](#setValues-short---) | Değerleri alır veya ayarlar. |
| [getValuesContainer()](#getValuesContainer--) | Değer konteynerini alır. |
| [getElementSize()](#getElementSize--) | Elemanın bayt cinsinden boyutunu alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffSShortType(int tagId) {#TiffSShortType-int-}
```
public TiffSShortType(int tagId)
```


Yeni bir `TiffSShortType` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### getValues() {#getValues--}
```
public short[] getValues()
```


Değerleri alır veya ayarlar.

Değer: Değerler.

**Returns:**
short[]
### setValues(short[] value) {#setValues-short---}
```
public void setValues(short[] value)
```


Değerleri alır veya ayarlar.

Değer: Değerler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short[] |  |

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
