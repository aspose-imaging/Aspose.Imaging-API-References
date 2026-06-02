---
title: "TiffASCIIType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff ascii türü."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

tiff ascii türü.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Yeni bir `TiffASCIIType` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getText()](#getText--) | Metni alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Metni alır veya ayarlar. |
| [getCount()](#getCount--) | Eleman sayısını alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Yeni bir `TiffASCIIType` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Etiket kimliği. |

### getText() {#getText--}
```
public String getText()
```


Metni alır veya ayarlar.

**Returns:**
java.lang.String - Metin.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Metni alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Metin. |

### getCount() {#getCount--}
```
public long getCount()
```


Eleman sayısını alır.

**Returns:**
long - öğe sayısı.
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
