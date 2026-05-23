---
title: "EmfPlusSetTextRenderingHint Sınıfı"
type: docs
weight: 560
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/
---

**Summary:** The EmfPlusSetTextRenderingHint record specifies the quality of text rendering, including the type of anti-aliasing.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTextRenderingHint

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSetTextRenderingHint(source)](#EmfPlusSetTextRenderingHint_source_1) | Yeni bir [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| text_rendering_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Metin renderleme ipucu değerini alır veya ayarlar, <br/>            TextRenderingHint enumarasyonundan (bölüm 2.1.1.32), sonraki metin renderlemesinde kullanılacak kaliteyi belirler. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusSetTextRenderingHint(source) {#EmfPlusSetTextRenderingHint_source_1}


```
 EmfPlusSetTextRenderingHint(source) 
```

Yeni bir [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

