---
title: EmfStretchBlt
second_title: Aspose.Imaging for .NET API Referansı
description: EMR_STRETCHBLT kaydı isteğe bağlı olarak belirtilen bir raster işlemine göre bir fırça deseniyle birlikte gerekirse hedefin boyutlarına uyacak şekilde çıktıyı gererek veya sıkıştırarak bir kaynak bitmapten bir hedef dikdörtgene piksellerin blok aktarımını belirtir. .
type: docs
weight: 4590
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

EMR_STRETCHBLT kaydı, isteğe bağlı olarak, belirtilen bir raster işlemine göre bir fırça deseniyle birlikte, gerekirse hedefin boyutlarına uyacak şekilde çıktıyı gererek veya sıkıştırarak, bir kaynak bitmap'ten bir hedef dikdörtgene piksellerin blok aktarımını belirtir. .

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfStretchBlt](emfstretchblt#constructor)() | Yeni bir örneğini başlatır[`EmfStretchBlt`](../emfstretchblt) sınıf. |
| [EmfStretchBlt](emfstretchblt#constructor_1)(EmfRecord) | Yeni bir örneğini başlatır[`EmfStretchBlt`](../emfstretchblt) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc) { get; set; } | Bir WMF ColorRef nesnesi alır veya ayarlar ([MS-WMF] kaynak bitmap'in arka plan rengini belirten bölüm 2.2.2.8. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation) { get; set; } | Tarama işlemi kodunu belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. Bu kod, son color elde etmek için kaynak dikdörtgenin renk verilerinin hedef dikdörtgenin renk verileri ve isteğe bağlı olarak bir fırça deseni ile nasıl birleştirileceğini tanımlar. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds) { get; set; } | Aygıt birimlerinde hedef sınırlayıcı dikdörtgeni tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest) { get; set; } | Hedef dikdörtgenin mantıksal genişliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc) { get; set; } | Kaynak dikdörtgenin mantıksal genişliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest) { get; set; } | Hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc) { get; set; } | Kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect) { get; set; } | Varış yönünü alır veya ayarlar. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Rekorun boyutunu alır veya ayarlar |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap) { get; set; } | EMR_STRETCHBLT kaydının sabit kısmıyla bitişik olması gerekmeyen kaynak bit eşlemi içeren bir arabellek alır veya ayarlar. Buna göre, bu arabelleğindeki "UndefinedSpace" etiketli alanlar isteğe bağlıdır ve MUTLAKA yoksayılmalıdır. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect) { get; set; } | Kaynak doğrusunu alır veya ayarlar. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Türü alır veya ayarlar. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc) { get; set; } | Kaynak bit eşlem başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer DIBColors numaralandırmasında OLMALIDIR (bölüm 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest) { get; set; } | Hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc) { get; set; } | Kaynak bitmap'e uygulanacak bir dünya-alandan sayfa-uzay dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28) alır veya ayarlar. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc) { get; set; } | Kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest) { get; set; } | Hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc) { get; set; } | Kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |

### Ayrıca bakınız

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
