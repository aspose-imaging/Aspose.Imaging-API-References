---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusMultiplyWorldTransform kaydı, geçerli dünya uzayı dönüşümünü belirtilen bir dönüşüm matrisiyle çarpar."
type: docs
weight: 41
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusMultiplyWorldTransform kaydı, geçerli dünya uzayı dönüşümünü belirtilen bir dönüşüm matrisiyle çarpar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusMultiplyWorldTransform` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | [post multiplied matrix] olup olmadığını gösteren bir değeri alır. |
| [getMatrixData()](#getMatrixData--) | Çarpma matrisini tanımlayan bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47). |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Çarpma matrisini tanımlayan bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47). |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


`EmfPlusMultiplyWorldTransform` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


[post multiplied matrix] olup olmadığını gösteren bir değeri alır. Ayarlanmışsa, dönüşüm matrisi sonradan çarpılmalıdır. Temizlenmişse, önceden çarpılmalıdır.

Değer: [post multiplied matrix] ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Çarpma matrisini tanımlayan bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47).

Değer: Matris verisi.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Çarpma matrisini tanımlayan bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47).

Değer: Matris verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

