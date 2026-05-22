---
title: "EmfPlusRotateWorldTransform"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusRotateWorldTransform kaydı, geçerli dünya uzayı dönüşümüne bir döndürme uygular."
type: docs
weight: 50
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusRotateWorldTransform kaydı, geçerli dünya uzayı dönüşümüne bir döndürme uygular.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusRotateWorldTransform` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | [post multiplied matrix] olup olmadığını gösteren bir değeri alır. |
| [getAngle()](#getAngle--) | Dönüş açısını derece cinsinden belirten 32-bit kayan nokta değerini alır veya ayarlar. |
| [setAngle(float value)](#setAngle-float-) | Dönüş açısını derece cinsinden belirten 32-bit kayan nokta değerini alır veya ayarlar. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


`EmfPlusRotateWorldTransform` sınıfının yeni bir örneğini başlatır.

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Bu, dönüş açısını derece cinsinden belirten 32-bit kayan nokta değerini alır veya ayarlar. İşlem, aşağıdaki diyagramdan yeni bir dönüşüm matrisi oluşturularak gerçekleştirilir:
---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Şekil 2: Dönüşüm Matrisı
Mevcut dünya uzayı dönüşümü bu matrisle çarpılır ve sonuç yeni mevcut dünya uzayı dönüşümü olur. Flags alanı çarpma sırasını belirler.

Değer: Açı.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Bu, dönüş açısını derece cinsinden belirten 32-bit kayan nokta değerini alır veya ayarlar. İşlem, aşağıdaki diyagramdan yeni bir dönüşüm matrisi oluşturularak gerçekleştirilir:
---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Şekil 2: Dönüşüm Matrisı
Mevcut dünya uzayı dönüşümü bu matrisle çarpılır ve sonuç yeni mevcut dünya uzayı dönüşümü olur. Flags alanı çarpma sırasını belirler.

Değer: Açı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

