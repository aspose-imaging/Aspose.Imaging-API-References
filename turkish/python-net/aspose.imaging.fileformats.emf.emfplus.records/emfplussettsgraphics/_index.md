---
title: "EmfPlusSetTsGraphics Sınıfı"
type: docs
weight: 580
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | Yeni bir [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Satır render kalitesini, satır anti-aliasing türünü de içerecek şekilde belirten 8‑bit işaretsiz tam sayıyı alır veya ayarlar,<br/>            bu değer SmoothingMode<br/>            enumarasyonunda tanımlanmalıdır (bölüm 2.1.1.28). |
| basic_vga_colors | bool | r | [basic vga colors] olup olmadığını gösteren bir değeri alır.<br/>            Ayarlanırsa, palet yalnızca temel VGA renklerini içerir. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Kaynak renklerinin arka plan renkleriyle nasıl birleştirileceğini belirten 8‑bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu değer CompositingMode<br/>            enumarasyonunda bir değer olmalıdır (bölüm 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Satırlara, eğrilere ve doldurulmuş alanların kenarlarına uygulanacak pürüzsüzleştirme derecesini belirten 8‑bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu değer CompositingQuality enumarasyonunda bir değer olmalıdır (bölüm 2.1.1.6). |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Uzatma ve küçültme dahil ölçeklemenin nasıl gerçekleştirileceğini belirten 8‑bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu değer FilterType enumarasyonunda bir değer olmalıdır (bölüm 2.1.1.11). |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| have_palette | bool | r | [have palette] olup olmadığını gösteren bir değeri alır.<br/>            Ayarlanırsa, bu kayıt grafik durum verisinin ardından gelen Palette alanında bir EmfPlusPalette nesnesi (bölüm 2.2.2.28) içerir. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | İsteğe bağlı bir EmfPlusPalette nesnesini alır veya ayarlar. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Görüntünün ve metin render sürecinin genel kalitesini belirten 8‑bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu değer PixelOffsetMode enumarasyonunda bir değer olmalıdır (bölüm 2.1.1.26). |
| render_origin_x | int | r/w | Yarı tonlama ve titreme matrislerinin render başlangıç noktasının yatay koordinatını belirten 16‑bit işaretli tam sayıyı alır veya ayarlar.<br/>             |
| render_origin_y | int | r/w | Yarı tonlama ve titreme matrislerinin render başlangıç noktasının dikey koordinatını belirten 16‑bit işaretli tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| text_contrast | int | r/w | Anti-aliasing ve ClearType metin render'ı için kullanılan gama düzeltme değerini belirten 16‑bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu değer 0 ile 12 arasında, dahil olmak üzere bir değer olmalıdır. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Metin render kalitesini, metin anti-aliasing türünü de içerecek şekilde belirten 8‑bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu değer TextRenderingHint enumarasyonunda tanımlanmalıdır (bölüm 2.1.1.32). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 192 bitlik bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47) bu<br/>            dünya uzayından cihaz uzayına dönüşümleri belirten. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

Yeni bir [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

