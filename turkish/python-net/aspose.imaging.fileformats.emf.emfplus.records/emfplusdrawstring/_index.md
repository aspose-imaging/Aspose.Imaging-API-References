---
title: "EmfPlusDrawString Sınıfı"
type: docs
weight: 190
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Yeni bir [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Fırça tanımlayıcısını alır veya ayarlar<br/>            Fırçayı belirten 32 bit işaretsiz tamsayı, içeriği <br/>            Flags alanındaki S biti tarafından belirlenir. Bu tanım <br/>            ön plan metin rengini boyamak için kullanılır; yani sadece glifler kendileri. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| format_id | int | r/w | Biçim tanımlayıcısını alır veya ayarlar<br/>            İsteğe bağlı bir <br/>            EmfPlusStringFormat nesnesinin (bölüm 2.2.1.9) EMF+ Nesne Tablosundaki dizinini belirten 32 bit işaretsiz tamsayı. <br/>            Bu nesne bir dizeye uygulanacak metin yerleşim bilgilerini ve görüntü manipülasyonlarını belirtir |
| is_color | bool | r/w | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesini (bölüm 2.2.2.1) belirtir.<br/>            Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Düzen dikdörtgenini alır veya ayarlar<br/>            Dizeyi alacak hedefin sınırlayıcı alanını tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39). |
| length | int | r/w | Uzunluğu alır veya ayarlar<br/>            Dizedeki karakter sayısını belirten 32 bit işaretsiz tamsayı. |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Metni işlemek için EMF+ Nesne Tablosundaki bir EmfPlusFont nesnesinin (bölüm 2.2.1.3) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| string_data | string | r/w | Dize verisini alır veya ayarlar<br/>            Çizilecek dizeyi belirten 16 bit Unicode karakterlerden oluşan bir dizi. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Yeni bir [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

