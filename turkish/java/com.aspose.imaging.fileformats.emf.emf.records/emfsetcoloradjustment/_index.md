---
title: "EmfSetColorAdjustment"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETCOLORADJUSTMENT kaydı, oynatma cihazı bağlamında renk ayarlama özelliklerini belirtir."
type: docs
weight: 122
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

EMR\_SETCOLORADJUSTMENT kaydı, oynatma cihaz bağlamındaki renk ayarı özelliklerini tanımlar.

Renk ayarlama değerleri, STRETCH\_HALFTONE modu StretchMode numaralandırmasından (bölüm 2.1.32) ayarlandığında, EMR\_STRETCHBLT ve EMR\_STRETCHDIBITS kayıtları tarafından gerçekleştirilen grafik işlemleri için kaynak bitmap'in giriş rengini ayarlamak amacıyla kullanılır. Bu kayıt tarafından belirtilen ColorAdjustment nesnesi, başka bir EMR\_SETCOLORADJUSTMENT kaydıyla farklı bir ColorAdjustment nesnesi belirtilene kadar veya nesne bir EMR\_DELETEOBJECT kaydıyla kaldırılana kadar, ColorAdjustment nesnesi gerektiren grafik işlemlerinde KULLANILMALIDIR.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSetColorAdjustment` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Renk ayarlama değerlerini belirten bir ColorAdjustment nesnesini (bölüm 2.2.2) alır veya ayarlar. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Renk ayarlama değerlerini belirten bir ColorAdjustment nesnesini (bölüm 2.2.2) alır veya ayarlar. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


`EmfSetColorAdjustment` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Renk ayarlama değerlerini belirten bir ColorAdjustment nesnesini (bölüm 2.2.2) alır veya ayarlar.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Renk ayarlama değerlerini belirten bir ColorAdjustment nesnesini (bölüm 2.2.2) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

