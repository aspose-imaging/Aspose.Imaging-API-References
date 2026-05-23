---
title: "EmfPlusHeader Sınıfı"
type: docs
weight: 310
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Yeni bir [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| dual_mode | bool | r/w | Bu değer, [dual mode] olup olmadığını alır veya ayarlar.<br/>            Ayarlanmışsa, bu bayrak metafilenin \"dual-mode\" olduğunu gösterir; bu, iki kayıt kümesi içerdiği ve her birinin grafik içeriğini tamamen belirttiği anlamına gelir.<br/>            Temizlenmişse, grafik içeriği EMF+ kayıtlarıyla ve muhtemelen bir EmfPlusGetDC kaydıyla önceden gelen EMF kayıtlarıyla belirtilir.<br/>            Bu bayrak ayarlıysa, yalnızca EMF kayıtları grafik içeriğini tanımlamak için YETERLİ OLMAK ZORUNDADIR.<br/>            \"dual-mode\" bayrağının ayarlı olup olmadığına bakılmaksızın, bazı EMF kayıtları her zaman bulunur; özellikle EMF kontrol kayıtları ve EMF+ kayıtlarını içeren EMF kayıtları. EMF kontrol kayıtları [MS-EMF] bölüm 2.4.4'te belirtilmiştir. |
| emf_plus_flags | int | r/w | EMF plus bayraklarını alır veya ayarlar.<br/>            Bu metafilenin nasıl kaydedildiği hakkında bilgi içeren 32 bit işaretsiz bir tamsayı.<br/>            Alanın 31. biti ayarlıysa, bu bayrak metafilenin bir video ekranı için referans cihaz bağlamı ile kaydedildiğini gösterir. Temizlenmişse, metafile bir yazıcı için referans cihaz bağlamı ile kaydedilmiştir. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| is_valid | bool | r | Bu örneğin geçerli olup olmadığını gösteren bir değer alır. |
| logical_dpi_x | int | r/w | Mantıksal dpi x değerini alır veya ayarlar.<br/>            Metafilenin kaydedildiği yatay çözünürlüğü belirten 32 bit işaretsiz bir tamsayı; birim olarak inç başına piksel. |
| logical_dpi_y | int | r/w | Mantıksal dpi y değerini alır veya ayarlar.<br/>            Metafilenin kaydedildiği dikey çözünürlüğü belirten 32 bit işaretsiz bir tamsayı; birim olarak inç başına satır. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Sürümü alır veya ayarlar.<br/>            Bu metafileyi oluşturmak için kullanılan işletim sistemi grafiklerinin sürümünü belirten bir EmfPlusGraphicsVersion nesnesi (bölüm 2.2.2.19). |
| video_display | bool | r/w | Video ekranı olup olmadığını gösteren bir değer alır veya ayarlar.<br/>            Ayarlıysa, bu bayrak metafilenin bir video ekranı için referans cihaz bağlamı ile kaydedildiğini gösterir. Temizlenmişse, metafile bir yazıcı için referans cihaz bağlamı ile kaydedilmiştir. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Yeni bir [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

