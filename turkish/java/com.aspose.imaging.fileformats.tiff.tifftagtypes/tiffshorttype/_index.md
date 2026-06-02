---
title: "TiffShortType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Tiff kısa tür."
type: docs
weight: 25
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffShortType extends TiffCommonArrayType
```

Tiff kısa tür.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffShortType(int tagId)](#TiffShortType-int-) | Yeni bir `TiffShortType` sınıfının örneğini başlatır. |
| [TiffShortType(int tagId, int[] values)](#TiffShortType-int-int---) | Yeni bir `TiffShortType` sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValues()](#getValues--) | Veriyi alır veya ayarlar. |
| [setValues(int[] value)](#setValues-int---) | Veriyi alır veya ayarlar. |
| [getElementSize()](#getElementSize--) | Elemanın bayt cinsinden boyutunu alır. |
| [getValuesContainer()](#getValuesContainer--) | Değer konteynerini alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffShortType(int tagId) {#TiffShortType-int-}
```
public TiffShortType(int tagId)
```


Yeni bir `TiffShortType` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### TiffShortType(int tagId, int[] values) {#TiffShortType-int-int---}
```
public TiffShortType(int tagId, int[] values)
```


Yeni bir `TiffShortType` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |
| değerler | int[] |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Veriyi alır veya ayarlar.

Value: Veri.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Veriyi alır veya ayarlar.

Value: Veri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Elemanın bayt cinsinden boyutunu alır.

Value: Elemanın bayt cinsinden boyutu.

**Returns:**
byte
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Değer konteynerini alır.

Value: Değerler konteyneri.

**Returns:**
com.aspose.ms.System.Array
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
