---
title: "EmfPlusSetWorldTransform"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetWorldTransform kaydı, belirtilen dönüşüm matrisindeki değerlere göre dünya dönüşümünü ayarlar."
type: docs
weight: 68
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusSetWorldTransform kaydı, belirtilen dönüşüm matrisindeki değerlere göre dünya dönüşümünü ayarlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusSetWorldTransform` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | Yeni geçerli dünya dönüşümünü tanımlayan bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Yeni geçerli dünya dönüşümünü tanımlayan bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


`EmfPlusSetWorldTransform` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Yeni geçerli dünya dönüşümünü tanımlayan bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar.

Değer: Matris verisi.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Yeni geçerli dünya dönüşümünü tanımlayan bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar.

Değer: Matris verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

