---
title: "EmfPlusDrawDriverString Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Yeni bir [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Fırça tanımlayıcısını alır veya ayarlar<br/>            Flags içindeki S bayrağının değerine bağlı olarak metnin ön plan rengini veya bir grafik fırçasını belirten 32 bitlik işaretsiz tamsayı. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Sürücü dizesi seçenek bayraklarını alır veya ayarlar<br/>            Dize için boşluk, yönelim ve render kalitesini belirten 32 bitlik işaretsiz tamsayı. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| glyph_count | int | r/w | Glif sayısını alır veya ayarlar<br/>            Dizedeki glif sayısını belirten 32 bitlik işaretsiz tamsayı. |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Glif konumları dizisini alır veya ayarlar<br/>            Her karakter glifinin çıktı konumunu belirten EmfPlusPointF nesnelerinin (bölüm 2.2.2.36) bir dizisi.<br/>            GlyphCount elemanları bulunmalı ve bu elemanlar Glyphs dizisindeki elemanlarla bire bir eşleşmelidir.<br/>            DriverStringOptions bayraklarındaki DriverStringOptionsRealizedAdvance bayrağı ayarlıysa, glif konumları ilk glifin konumundan hesaplanır. Bu durumda, GlyphPos yalnızca ilk glifin konumunu belirtir. |
| glyphs | int[] | r/w | Glifler dizisini alır veya ayarlar<br/>            Çizilecek metin dizesini tanımlayan 16 bitlik değerlerin bir dizisi.<br/>            DriverStringOptionsFlags alanındaki DriverStringOptionsCmapLookup bayrağı ayarlıysa, bu dizideki her değer bir Unicode karakterini belirtir. Aksi takdirde, her değer Flags alanındaki ObjectId değeriyle belirtilen EmfPlusFont nesnesindeki bir karakter glifine bir indeks belirtir. |
| is_color | bool | r/w | Bu örneğin renk olup olmadığını belirten bir değeri alır veya ayarlar.<br/>            Bu bit, BrushId alanındaki veri tipini gösterir.<br/>            Ayarlıysa, BrushId bir EmfPlusARGB nesnesindeki (bölüm 2.2.2.1) renk değerini belirtir.<br/>            Temizse, BrushId bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) EMF+ Nesne Tablosu indeksini içerir. |
| matrix_present | int | r/w | Matris mevcut bayrağını alır veya ayarlar<br/>            TransformMatrix alanında bir dönüşüm matrisinin bulunup bulunmadığını belirten 32 bitlik işaretsiz tamsayı<br/>            0 - matris yok. 1 - dönüşüm matrisi TransformMatrix alanında. |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Metni renderlemek için bir ***EmfPlusFont*** nesnesinin (bölüm 2.2.1.3) EMF+ Nesne Tablosu indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Dönüşüm matrisini alır veya ayarlar<br/>            Metin dizisindeki her değere uygulanacak dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47). Bu verinin varlığı MatrixPresent alanından belirlenir. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Yeni bir [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

