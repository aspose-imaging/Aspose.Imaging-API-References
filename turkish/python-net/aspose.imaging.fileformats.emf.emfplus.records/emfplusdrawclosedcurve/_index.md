---
title: "EmfPlusDrawClosedCurve Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | Yeni bir [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) sınıfı örneği başlatır.<br/>            RecordType - Bu kayıt türünü RecordType sayımından (bölüm 2.1.1.1) EmfPlusDrawClosedCurve olarak tanımlayan 16 bit işaretsiz tam sayı. Değer 0x4017 olmalıdır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Bu [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir.<br/>            Ayarlıysa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir. <br/>            Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir<br/>            Not: Aşağıdaki Relative bayrağı ayarlıysa, bu bayrak tanımsızdır ve YOK SAYILMALIDIR |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Kapalı eğriyi çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Nokta verilerini alır veya ayarlar<br/>            Spline'ı tanımlayan çizgilerin uç noktalarını belirten Count sayıda nokta dizisi. Kapalı bir kardinal spline'da, <br/>            eğri PointData dizisindeki son nokta üzerinden devam eder ve dizinin ilk noktasıyla bağlanır.<br/>            Bu dizideki veri türü Flags alanı tarafından aşağıdaki gibi belirtilir: Veri Türü Anlamı<br/>            EmfPlusPointR nesnesi (bölüm 2.2.2.37)<br/>            Flags içinde P bayrağı ayarlıysa, noktalar göreli konumları belirtir.<br/>            EmfPlusPointF nesnesi (bölüm 2.2.2.36)<br/>            Flags alanında P ve C bitleri ayarlıysa, noktalar mutlak konumları belirtir.<br/>            EmfPlusPoint nesnesi (bölüm 2.2.2.35)<br/>            Flags alanında P biti temiz ve C biti ayarlıysa, noktalar göreli konumları belirtir. |
| relative | bool | r/w | Bu [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) göreceli olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, PointData alanının göreceli mi yoksa mutlak mı konumları belirttiğini gösterir.<br/>            Ayarlıysa, PointData'daki her öğe, koordinat uzayında bir konumu, dizideki önceki öğe tarafından belirtilen konuma göreli olarak belirtir.<br/>            PointData'daki ilk öğe için, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir.<br/>            Not: Bu bayrak ayarlıysa, yukarıdaki Sıkıştırılmış bayrak tanımsızdır ve YOK SAYILMALIDIR |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| gerilim | float | r/w | Gerginliği alır veya ayarlar<br/>            Noktalardan geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta sayısı. 0 değeri spline'ın düz hatlar dizisi olduğunu belirtir. Değer arttıkça, eğri daha yuvarlak hâle gelir. Daha fazla bilgi için [SPLINE77] ve [PETZOLD] bakınız. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

Yeni bir [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) sınıfı örneği başlatır.<br/>            RecordType - Bu kayıt türünü RecordType sayımından (bölüm 2.1.1.1) EmfPlusDrawClosedCurve olarak tanımlayan 16 bit işaretsiz tam sayı. Değer 0x4017 olmalıdır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

