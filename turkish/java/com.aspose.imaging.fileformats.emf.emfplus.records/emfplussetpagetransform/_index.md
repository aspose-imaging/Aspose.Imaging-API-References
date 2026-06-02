---
title: "EmfPlusSetPageTransform"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetPageTransform kaydı, sayfa alanı koordinatlarını cihaz alanı koordinatlarına dönüştürmek için ölçek faktörlerini ve birimleri belirtir."
type: docs
weight: 61
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusSetPageTransform kaydı, sayfa alanı koordinatlarını cihaz alanı koordinatlarına dönüştürmek için ölçek faktörlerini ve birimleri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusSetPageTransform` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Sayfa uzayı koordinatları için ölçü birimini, UnitType enumarasyonundan alır (bölüm 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Sayfa uzayı koordinatlarını cihaz uzayı koordinatlarına dönüştürmek için ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setPageScale(float value)](#setPageScale-float-) | Sayfa uzayı koordinatlarını cihaz uzayı koordinatlarına dönüştürmek için ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


`EmfPlusSetPageTransform` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Sayfa uzayı koordinatları için ölçü birimini, UnitType enumarasyonundan alır (bölüm 2.1.1.33). Bu değer UnitTypeDisplay ya da UnitTypeWorld olmamalıdır.

Değer: Sayfa birimi.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Sayfa uzayı koordinatlarını cihaz uzayı koordinatlarına dönüştürmek için ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar.

Değer: Sayfa ölçeği.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Sayfa uzayı koordinatlarını cihaz uzayı koordinatlarına dönüştürmek için ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar.

Değer: Sayfa ölçeği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

