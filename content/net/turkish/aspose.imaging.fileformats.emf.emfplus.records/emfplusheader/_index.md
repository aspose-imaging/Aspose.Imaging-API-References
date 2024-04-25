---
title: EmfPlusHeader
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusHeader kaydı meta dosyasındaki EMF verilerinin başlangıcını belirtir. EmfPlusHeader kaydı meta dosyasındaki EMF başlığının hemen ardından gelen kayıt OLMALIDIR bir EMF EMR_COMMENT_EMFPLUS kaydına yerleştirilmelidir ZORUNLU. EMR_COMMENT_EMFPLUS kaydı MS-EMF bölüm 2.3.3.2. de belirtilmiştir.
type: docs
weight: 6140
url: /tr/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

EmfPlusHeader kaydı, meta dosyasındaki EMF+ verilerinin başlangıcını belirtir. EmfPlusHeader kaydı, meta dosyasındaki EMF başlığının hemen ardından gelen kayıt OLMALIDIR, bir EMF EMR_COMMENT_EMFPLUS kaydına yerleştirilmelidir ZORUNLU. EMR_COMMENT_EMFPLUS kaydı, [MS-EMF] bölüm 2.3.3.2. 'de belirtilmiştir.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusHeader](emfplusheader)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusHeader`](../emfplusheader) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode) { get; set; } | [ikili mod] olup olmadığını gösteren bir değer alır veya ayarlar. Ayarlanırsa, bu bayrak bu meta dosyasının "ikili mod" olduğunu belirtir; bu, her biri grafik içeriğini tamamen belirten iki kayıt kümesi içerdiği anlamına gelir. Açıksa, grafik içeriği EMF+ kayıtları ve muhtemelen öncesinde bir EmfPlusGetDC kaydı olan EMF kayıtları tarafından belirtilir. Bu bayrak ayarlanırsa, EMF kayıtları tek başına grafik içeriğini tanımlamak için yeterli OLMALIDIR. "İkili mod" bayrağı ayarlanmış olsun veya olmasın, bazı EMF kayıtlarının her zaman mevcut olduğuna dikkat edin, yani EMF kontrol kayıtları ve EMF+ kayıtlarını içeren EMF kayıtları . EMF kontrol kayıtları [MS-EMF] bölüm 2.3.4. 'de belirtilmiştir. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags) { get; set; } | EMF artı işaretlerini alır veya ayarlar. Bu meta dosyasının nasıl kaydedildiği hakkında bilgi içeren 32 bitlik işaretsiz bir tam sayı. Alanın 31. biti ayarlanmışsa, bu bayrak meta dosyasının bir referansla kaydedildiğini gösterir. video gösterimi için cihaz bağlamı. Temizse, meta dosyası, bir yazıcı için bir referans cihaz bağlamı ile kaydedilmiştir. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid) { get; } | Bu örneğin geçerli olup olmadığını gösteren bir değer alır. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix) { get; set; } | Mantıksal dpi x. değerini alır veya ayarlar. meta dosyasının kaydedildiği yatay çözünürlüğü inç başına piksel birimi cinsinden belirten 32 bitlik işaretsiz bir tam sayı. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy) { get; set; } | Mantıksal dpi'yi alır veya ayarlar y. İnç başına satır birimi olarak meta dosyasının kaydedildiği dikey çözünürlüğü belirten 32 bitlik işaretsiz bir tam sayı |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version) { get; set; } | Sürümü alır veya ayarlar. Bu meta dosyasını oluşturmak için kullanılan Operating sistem grafiklerinin sürümünü belirten bir EmfPlusGraphicsVersion nesnesi (bölüm 2.2.2.19). |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay) { get; set; } | Video gösterimi olup olmadığını belirten bir değer alır veya ayarlar. ayarlanırsa, bu bayrak meta dosyasının bir video gösterimi için bir referans device bağlamıyla kaydedildiğini gösterir. Temizse, meta dosyası bir yazıcı için bir referans device bağlamıyla kaydedilmiştir. |

### Ayrıca bakınız

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
