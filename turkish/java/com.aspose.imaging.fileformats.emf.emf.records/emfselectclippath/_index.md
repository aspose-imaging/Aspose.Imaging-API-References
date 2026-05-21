---
title: "EmfSelectClipPath"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SELECTCLIPPATH kaydı, belirtilen modu kullanarak yeni bölgeyi mevcut kırpma bölgesiyle birleştirerek, oynatma aygıtı bağlamı için geçerli yolu bir kırpma bölgesi olarak belirtir."
type: docs
weight: 115
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

EMR\_SELECTCLIPPATH kaydı, mevcut yolu bir oynatma cihaz bağlamı için kırpma bölgesi olarak tanımlar ve belirtilen modla yeni bölgeyi mevcut kırpma bölgesiyle birleştirir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSelectClipPath` sınıfının yeni bir örneğini başlatır. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | `EmfSelectClipPath` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Yolu kullanma şeklini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setRegionMode(int value)](#setRegionMode-int-) | Yolu kullanma şeklini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


`EmfSelectClipPath` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


`EmfSelectClipPath` sınıfının yeni bir örneğini başlatır.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Yolu kullanma şeklini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Değer, RegionMode numaralandırmasında (bölüm 2.1.29) bulunmalıdır.

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Yolu kullanma şeklini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Değer, RegionMode numaralandırmasında (bölüm 2.1.29) bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

