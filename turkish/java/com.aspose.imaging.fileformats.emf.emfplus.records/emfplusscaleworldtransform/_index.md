---
title: "EmfPlusScaleWorldTransform"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusScaleWorldTransform kaydı, geçerli dünya uzayı dönüşümüne bir ölçekleme uygular."
type: docs
weight: 52
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusScaleWorldTransform kaydı, geçerli dünya uzayı dönüşümüne bir ölçekleme uygular.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusScaleWorldTransform` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | [post multiplied matrix] olup olmadığını gösteren bir değeri alır. |
| [getSx()](#getSx--) | Yatay ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar. |
| [setSx(float value)](#setSx-float-) | Yatay ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar. |
| [getSy()](#getSy--) | Dikey ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar. |
| [setSy(float value)](#setSy-float-) | Dikey ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


`EmfPlusScaleWorldTransform` sınıfının yeni bir örneğini başlatır.

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
### getSx() {#getSx--}
```
public float getSx()
```


Yatay ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar. Ölçekleme, aşağıdaki tabloda gösterildiği gibi Sx ve Sy alan değerlerinden yeni bir dönüşüm matrisi oluşturularak gerçekleştirilir. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Şekil 3: Ölçek Dönüşüm Matrisi

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Yatay ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar. Ölçekleme, aşağıdaki tabloda gösterildiği gibi Sx ve Sy alan değerlerinden yeni bir dönüşüm matrisi oluşturularak gerçekleştirilir. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Şekil 3: Ölçek Dönüşüm Matrisi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Dikey ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Dikey ölçek faktörünü tanımlayan 32 bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

