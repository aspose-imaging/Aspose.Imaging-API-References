---
title: EmfSetColorAdjustment
second_title: Aspose.Imaging for .NET API Referansı
description: EMR_SETCOLORADJUSTMENT kaydı oynatma cihaz bağlamında renk ayarlama özelliklerini belirtir.
type: docs
weight: 4310
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
## EmfSetColorAdjustment class

EMR_SETCOLORADJUSTMENT kaydı, oynatma cihaz bağlamında renk ayarlama özelliklerini belirtir.

```csharp
public sealed class EmfSetColorAdjustment : EmfStateRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfSetColorAdjustment](emfsetcoloradjustment)(EmfRecord) | Yeni bir örneğini başlatır[`EmfSetColorAdjustment`](../emfsetcoloradjustment) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ColorAdjustment](../../aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/coloradjustment) { get; set; } | color ayarlama değerlerini belirten bir ColorAdjustment nesnesi (bölüm 2.2.2) alır veya ayarlar. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Rekorun boyutunu alır veya ayarlar |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Türü alır veya ayarlar. |

### Notlar

Renk ayarlama değerleri, StretchMode numaralandırmasından STRETCH_HALFTONE modu ayarlandığında (bölüm 2.1.32) EMR_STRETCHBLT ve EMR_STRETCHDIBITS kayıtları tarafından gerçekleştirilen graph işlemleri için kaynak bitmap'in giriş rengini ayarlamak için kullanılır. Bu kayıt tarafından belirtilen ColorAdjustment nesnesi ZORUNLUDUR başka bir EMR_SETCOLORADJUSTMENT kaydı tarafından farklı bir ColorAdjustment nesnesi belirtilene kadar veya nesne bir EMR_DELETEOBJECT kaydı tarafından kaldırılana kadar, bir ColorAdjustment nesnesi gerektiren grafik işlemlerinde kullanılır.

### Ayrıca bakınız

* class [EmfStateRecordType](../emfstaterecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->