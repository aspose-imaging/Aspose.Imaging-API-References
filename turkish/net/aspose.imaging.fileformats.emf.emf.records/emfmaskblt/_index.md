---
title: EmfMaskBlt
second_title: Aspose.Imaging for .NET API Referansı
description: EMR_MASKBLT kaydı belirtilen ön plan ve arka plan tarama işlemlerine göre isteğe bağlı olarak bir fırça deseni ve bir renk maskesi bitmap uygulamasıyla birlikte bir kaynak bitmapten hedef dikdörtgene piksellerin blok aktarımını belirtir.
type: docs
weight: 3800
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

EMR_MASKBLT kaydı, belirtilen ön plan ve arka plan tarama işlemlerine göre, isteğe bağlı olarak bir fırça deseni ve bir renk maskesi bitmap uygulamasıyla birlikte, bir kaynak bitmap'ten hedef dikdörtgene piksellerin blok aktarımını belirtir.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfMaskBlt](emfmaskblt)(EmfRecord) | Yeni bir örneğini başlatır[`EmfMaskBlt`](../emfmaskblt) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc) { get; set; } | Bir WMF ColorRef nesnesi alır veya ayarlar ([MS-WMF] kaynak bitmap'in arka plan rengini belirten bölüm 2.2.2.8. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds) { get; set; } | Aygıt birimlerinde hedef sınırlayıcı dikdörtgeni tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest) { get; set; } | Hedef dikdörtgenin mantıksal genişliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest) { get; set; } | Hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap) { get; set; } | EMR_MASKBLT kaydının sabit kısmıyla veya her bir diğeriyle bitişik olması gerekmeyen maske bit eşlemlerini içeren bir arabellek alır veya ayarlar. Buna göre, bu arabellekteki "UndefinedSpace" etiketli alanlar isteğe bağlıdır ve yoksayılmalıdır. |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4) { get; set; } | Bir bitmap'in ön plan ve arka plan renkleri olan için üçlü tarama işlemlerini belirten bir dörtlü tarama işlemini alır veya ayarlar. Bu değerler, kaynak dikdörtgenin renk verilerinin hedef dikdörtgenin renk verileriyle nasıl birleştirileceğini tanımlar. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Rekorun boyutunu alır veya ayarlar |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap) { get; set; } | EMR_MASKBLT kaydının sabit kısmıyla veya her bir birbiriyle bitişik olması gerekmeyen kaynak bit eşlemlerini içeren bir arabellek alır veya ayarlar. Buna göre, bu arabellekteki "UndefinedSpace" etiketli alanlar isteğe bağlıdır ve yoksayılmalıdır. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Türü alır veya ayarlar. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask) { get; set; } | Maske bit eşlem başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer DIBColors numaralandırmasında OLMALIDIR. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc) { get; set; } | Kaynak bit eşlem başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer DIBColors numaralandırmasında OLMALIDIR (bölüm 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest) { get; set; } | Hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc) { get; set; } | Kaynak bitmap'e uygulanacak bir dünya-alandan sayfa-uzay dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28) alır veya ayarlar. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask) { get; set; } | Maske bitmap'inin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc) { get; set; } | Kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest) { get; set; } | Hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask) { get; set; } | Maske bit eşleminin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc) { get; set; } | Kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |

### Ayrıca bakınız

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
