---
title: EmfPlusSetTsGraphics
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusSetTSGraphics kaydı bir terminal sunucusu için grafik aygıtı bağlamının durumunu belirtir.
type: docs
weight: 6410
url: /tr/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

EmfPlusSetTSGraphics kaydı, bir terminal sunucusu için grafik aygıtı bağlamının durumunu belirtir.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | Satır kenar yumuşatma türü de dahil olmak üzere, satır oluşturmanın kalitesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar, . SmoothingMode numaralandırmasında tanımlanmalıdır (bölüm 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | [temel vga renkleri] olup olmadığını gösteren bir değer alır. Ayarlanırsa, palet yalnızca temel VGA renklerini içerir. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | Kaynak renklerin arka plan renkleriyle nasıl birleştirildiğini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. CompositingMode numaralandırmasında (bölüm 2.1.1.5) bir değer OLMALIDIR. |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | Daha fazla sürekli veya keskin tanımlı görünmelerini sağlamak için çizgilere, eğrilere ve doldurulmuş alanların kenarlarına uygulanacak yumuşatma derecesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. CompositingQuality numaralandırmasında bir değer OLMALIDIR (bölüm 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | Stretching ve küçültme dahil olmak üzere ölçeklemenin nasıl gerçekleştirildiğini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. FilterType numaralandırmasında bir değer OLMALIDIR (bölüm 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | [Palete sahip] olup olmadığını gösteren bir değer alır. Ayarlanırsa, bu kayıt, grafik durum verisini izleyen Palet alanında bir EmfPlusPalette nesnesi (bölüm 2.2.2.28) içerir. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | İsteğe bağlı bir EmfPlusPalette nesnesi alır veya ayarlar. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | image ve metin işleme sürecinin genel kalitesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. PixelOffsetMode numaralandırmasında bir değer OLMALIDIR (bölüm 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | Yarı tonlama ve renk taklidi matrisleri oluşturmak için kaynağının yatay koordinatı olan 16 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | Yarı tonlama ve renk taklidi matrisleri oluşturmak için Origin öğesinin dikey koordinatı olan 16 bitlik işaretli bir tamsayı alır veya ayarlar. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | Kenar yumuşatılmış ve ClearType metni oluşturmak için kullanılan gama düzeltme değerini belirten 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer 0 ila 12 aralığında OLMALIDIR. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | Metin kenar yumuşatma türü de dahil olmak üzere text oluşturmanın kalitesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu, the TextRenderingHint numaralandırmasında (bölüm 2.1.1.32) tanımlanmalıdır. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | 192-bit EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47), bu dünya alanından cihaz alanına dönüşümleri belirtir. |

### Ayrıca bakınız

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
