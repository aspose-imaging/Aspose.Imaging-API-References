---
title: "EmfPlusTranslateWorldTransform"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusTranslateWorldTransform kaydı, mevcut dünya uzayı dönüşümüne bir çeviri uygular."
type: docs
weight: 72
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusTranslateWorldTransform kaydı, mevcut dünya uzayı dönüşümüne bir çeviri uygular.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusTranslateWorldTransform` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | [post multiplied matrix] olup olmadığını gösteren bir değeri alır. |
| [getDx()](#getDx--) | Yatay mesafeyi tanımlayan 32-bit kayan nokta değerini alır veya ayarlar. |
| [setDx(float value)](#setDx-float-) | Yatay mesafeyi tanımlayan 32-bit kayan nokta değerini alır veya ayarlar. |
| [getDy()](#getDy--) | Dikey mesafe değerini tanımlayan 32-bit kayan nokta değerini alır veya ayarlar. |
| [setDy(float value)](#setDy-float-) | Dikey mesafe değerini tanımlayan 32-bit kayan nokta değerini alır veya ayarlar. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


`EmfPlusTranslateWorldTransform` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


[post multiplied matrix] olup olmadığını gösteren bir değeri alır. Ayarlanmışsa, dönüşüm matrisi post-çarpılmalıdır. Temizlenmişse, ön-çarpılmalıdır.

Değer: [post multiplied matrix] ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### getDx() {#getDx--}
```
public float getDx()
```


Yatay mesafeyi tanımlayan 32-bit kayan nokta değerini alır veya ayarlar. Çeviri, dx ve dy alanlarından yeni bir dünya dönüşüm matrisi oluşturarak gerçekleştirilir.

Değer: dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Yatay mesafeyi tanımlayan 32-bit kayan nokta değerini alır veya ayarlar. Çeviri, dx ve dy alanlarından yeni bir dünya dönüşüm matrisi oluşturarak gerçekleştirilir.

Değer: dx.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Dikey mesafe değerini tanımlayan 32-bit kayan nokta değerini alır veya ayarlar.

Değer: dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Dikey mesafe değerini tanımlayan 32-bit kayan nokta değerini alır veya ayarlar.

Değer: dy.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

