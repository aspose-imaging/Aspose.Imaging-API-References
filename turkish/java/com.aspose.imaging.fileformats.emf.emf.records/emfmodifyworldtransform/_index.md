---
title: "EmfModifyWorldTransform"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_MODIFYWORLDTRANSFORM kaydı, oynatma aygıt bağlamındaki mevcut dünya-uzayından sayfa-uzayına dönüşümü değiştirir."
type: docs
weight: 73
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

EMR\_MODIFYWORLDTRANSFORM kaydı, oynatma cihaz bağlamındaki mevcut dünya-uzayından sayfa-uzayına dönüşümü değiştirir.

Dönüşümler ve koordinat uzaylarıyla ilgili daha fazla bilgi için [MSDN-WRLDPGSPC] adresine bakın. Diğer dönüşüm kayıt türlerinin spesifikasyonu için bölüm 2.3.12'ye bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfModifyWorldTransform` sınıfı örneği başlatır. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Yeni bir `EmfModifyWorldTransform` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Xform içinde belirtilen dönüşümün nasıl kullanılacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Xform içinde belirtilen dönüşümün nasıl kullanılacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Yeni bir `EmfModifyWorldTransform` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Yeni bir `EmfModifyWorldTransform` sınıfı örneği başlatır.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Xform içinde belirtilen dönüşümün nasıl kullanılacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu değer, ModifyWorldTransformMode numaralandırmasında (bölüm 2.1.24) bulunmalıdır.

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Xform içinde belirtilen dönüşümün nasıl kullanılacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu değer, ModifyWorldTransformMode numaralandırmasında (bölüm 2.1.24) bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

