---
title: EmfSetPolyFillMode
second_title: Aspose.Imaging for .NET API Referansı
description: EMR_SETPOLYFILLMODE kaydı çokgen doldurma modunu tanımlar.
type: docs
weight: 4460
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
## EmfSetPolyFillMode class

EMR_SETPOLYFILLMODE kaydı çokgen doldurma modunu tanımlar.

```csharp
public sealed class EmfSetPolyFillMode : EmfStateRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfSetPolyFillMode](emfsetpolyfillmode#constructor)() | Yeni bir örneğini başlatır[`EmfSetPolyFillMode`](../emfsetpolyfillmode) sınıf. |
| [EmfSetPolyFillMode](emfsetpolyfillmode#constructor_1)(EmfRecord) | Yeni bir örneğini başlatır[`EmfSetPolyFillMode`](../emfsetpolyfillmode) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [PolygonFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/polygonfillmode) { get; set; } | Çokgen doldurma modunu belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar ve PoligonFillMode (bölüm 2.1.27) numaralandırmasında OLMALIDIR. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Rekorun boyutunu alır veya ayarlar |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Türü alır veya ayarlar. |

### Notlar

Genel olarak, modlar yalnızca karmaşık, örtüşen bir çokgenin DOLDURULMASI ZORUNLU olduğu durumlarda farklılık gösterir; for örneği, merkezinde bir beşgen bulunan beş köşeli bir yıldız oluşturan beş kenarlı bir çokgen. Bu tür durumlarında, ALTERNATİF modu poligondaki diğer tüm çevrelenmiş bölgeleri (yıldızın noktaları) DOLDURMALIDIR, ancak SARMA modu tüm bölgeleri (yıldız ve beşgen noktaları) DOLDURMALIDIR. Doldurma modu ALTERNATİF olduğunda, her tarama satırında tek sayılı ve çift sayılı çokgen kenarları arasındaki alan doldurulmalıdır ÖNEMLİDİR. Yani, birinci ve ikinci kenar arasındaki alan ve üçüncü ve dördüncü kenar arasındaki alan doldurulmalıdır. Doldurma modu SARMA olduğunda, sıfırdan farklı bir sargı değerine sahip herhangi bir bölge DOLDURULMALIDIR. Sargı değer, poligonu çizmek için kullanılan bir kalemin bölgesi etrafında dönme sayısıdır. Çokgenin her bir kenarının yönü önemlidir.

### Ayrıca bakınız

* class [EmfStateRecordType](../emfstaterecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
