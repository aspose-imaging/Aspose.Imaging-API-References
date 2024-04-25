---
title: EmfLogFontExDv
second_title: Aspose.Imaging for .NET API Referansı
description: LogFontExDv nesnesi genişletilmiş bir mantıksal yazı tipi için tasarım vektörünü belirtir.
type: docs
weight: 3050
url: /tr/aspose.imaging.fileformats.emf.emf.objects/emflogfontexdv/
---
## EmfLogFontExDv class

LogFontExDv nesnesi, genişletilmiş bir mantıksal yazı tipi için tasarım vektörünü belirtir.

```csharp
public sealed class EmfLogFontExDv : EmfLogFontEx
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfLogFontExDv](emflogfontexdv)(EmfLogFontEx) | Yeni bir örneğini başlatır[`EmfLogFontExDv`](../emflogfontexdv) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Karakter glifleri kümesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. , WMF Karakter Kümesi numaralandırmasında ([MS-WMF] bölüm 2.1.1.5) bir değer OLMALIDIR. karakter kümesi bilinmiyorsa, meta dosyası işleme, o yazı tipiyle oluşturulan dizelerini çevirmeye veya yorumlamaya ÇALIŞMAMALIDIR. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Kırpma kesinliğini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. kırpma hassasiyeti, kısmen kırpma bölgesinin dışında kalan karakterlerin nasıl kırpılacağını tanımlar. WMF ClipPrecision Bayraklarından biri veya daha fazlası olabilir |
| [DesignVector](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontexdv/designvector) { get; set; } | Bir DesignVector nesnesi alır veya ayarlar (bölüm 2.2.3). Bu alan 72 bayttan uzun OLMAMALIDIR. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Eşapman vektörü ile aygıtın x ekseni arasındaki derecenin onda biri cinsinden açıyı belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Eşapman vektörü, bir metin satırının taban çizgisine paraleldir. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Bir Yüz Adı (64 bayt) alır veya ayarlar: Yazı tipinin yazı tipi adını belirten en fazla 32 Unicode karakterden oluşan bir dize. Bu dizenin uzunluğu 32 karakterden azsa, sonlandırıcı bir NULL OLMALIDIR, bundan sonra bu alanın geri kalanı yoksayılmalıdır. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/fullname) { get; set; } | Yazı tipinin tam adını içeren 64 Unicode karakterden oluşan bir dize alır veya ayarlar. bu dizenin uzunluğu 64 karakterden azsa, 'den sonra bu alanın geri kalanı yoksayılmalıdır ZORUNLU bir sonlandırıcı NULL OLMALIDIR. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Yazı tipinin karakter hücresinin veya karakterinin yüksekliğini mantıksal birimlerde belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. em boyutu olarak da bilinen karakter yüksekliği değeri, karakter hücre yüksekliği değerinden dahili satır aralığı değerinin çıkarılmasıyla elde edilen değerdir. Yazı tipi eşleyicisi, Yükseklik alanında belirtilen değeri aşağıdaki şekilde yorumlamalıdır . |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | 0x01 olarak ayarlanırsa italik bir yazı tipi belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar; aksi takdirde, 0x00. olarak AYARLANMALIDIR |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Her karakterin taban çizgisi ile aygıtın x ekseni arasındaki açıyı derecenin onda biri cinsinden belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Çıktı kesinliğini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. çıktı hassasiyeti, yazı tipinin istenen yükseklik, genişlik, karakter yönü, eşapman, aralık ve yazı tipi tipiyle ne kadar yakından eşleşmesi gerektiğini tanımlar. WMF OutPrecision numaralandırma değerinden bir değer OLMALIDIR |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | yazı tipinin aralığını ve ailesini belirten bir WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar. Yazı tipi aileleri, bir yazı tipinin görünümünü genel şekilde tanımlar. Belirtilen yazı tipi mevcut olmadığında bir yazı tipi belirtmek için tasarlanmıştır. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Çıktı kalitesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. çıktı kalitesi, mantıksal yazı tipi niteliklerini gerçek bir fiziksel yazı tipininkilerle ne kadar yakından eşleştirmeye çalışılacağını tanımlar. WMF FontQuality numaralandırmasındaki değerlerden biri OLMALIDIR ([MS-WMF] bölüm 2.1.1.10). |
| [Script](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/script) { get; set; } | Yazı tipinin karakter kümesini tanımlayan 32 Unicode karakterden oluşan bir dize alır veya ayarlar. Bu dizenin uzunluğu 32 karakterden azsa, sonlandırıcı bir NULL OLMALIDIR, bundan sonra bu alanın geri kalanı yoksayılmalıdır. |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | 0x01 olarak ayarlanırsa üstü çizili bir yazı tipi belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar; aksi takdirde 0x00 olarak AYARLANMALIDIR. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/style) { get; set; } | Yazı tipinin stilini tanımlayan 32 Unicode karakterden oluşan bir dize alır veya ayarlar. bu dizenin uzunluğu 32 karakterden azsa, sonlandırıcı bir NULL OLMALIDIR, bundan sonra bu alanın geri kalanı yoksayılmalıdır. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | 0x01 olarak ayarlanırsa altı çizili bir yazı tipi belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar; aksi takdirde 0x00. olarak AYARLANMALIDIR |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Sıfırdan 1000'e kadar aralığında yazı tipinin ağırlığını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Örneğin, 400 normaldir ve 700 kalındır. Bu değer sıfır ise, varsayılan bir ağırlık kullanılabilir. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Yazı tipindeki karakterlerinin mantıksal birimlerde ortalama genişliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Genişlik alanı değeri sıfırsa, tipografın amaçladığı en boy oranına sahip bir yazı tipi bulmak için diğer LogFont değerlerinden uygun bir değer hesaplanmalıdır GEREKİR |

### Ayrıca bakınız

* class [EmfLogFontEx](../emflogfontex)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
