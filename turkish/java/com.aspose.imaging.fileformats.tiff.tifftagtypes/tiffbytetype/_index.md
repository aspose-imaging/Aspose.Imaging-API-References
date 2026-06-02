---
title: "TiffByteType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff byte türü."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffByteType extends TiffCommonArrayType
```

tiff byte türü.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffByteType(int tagId)](#TiffByteType-int-) | Yeni bir `TiffByteType` sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValues()](#getValues--) | Değerleri alır veya ayarlar. |
| [setValues(byte[] value)](#setValues-byte---) | Değerleri alır veya ayarlar. |
| [getValuesContainer()](#getValuesContainer--) | Değer konteynerini alır. |
| [getElementSize()](#getElementSize--) | Elemanın bayt cinsinden boyutunu alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffByteType(int tagId) {#TiffByteType-int-}
```
public TiffByteType(int tagId)
```


Yeni bir `TiffByteType` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


Değerleri alır veya ayarlar.

**Returns:**
byte[] - Veri.
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


Değerleri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] | Veri. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Değer konteynerini alır.

**Returns:**
com.aspose.ms.System.Array - Değer konteyneri.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Elemanın bayt cinsinden boyutunu alır.

**Returns:**
byte - Elemanın bayt cinsinden boyutu.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Etiket tipini alır.

**Returns:**
int - Etiket türü.
### getValue() {#getValue--}
```
public Object getValue()
```


Bu veri tipinin içerdiği değeri alır veya ayarlar.

**Returns:**
java.lang.Object - Değer.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Bu veri tipinin içerdiği değeri alır veya ayarlar.

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
