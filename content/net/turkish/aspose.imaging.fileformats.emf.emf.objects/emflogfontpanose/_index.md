---
title: EmfLogFontPanose
second_title: Aspose.Imaging for .NET API Referansı
description: LogFontPanose nesnesi mantıksal bir yazı tipinin PANOSE özelliklerini belirtir.
type: docs
weight: 3060
url: /tr/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
## EmfLogFontPanose class

LogFontPanose nesnesi, mantıksal bir yazı tipinin PANOSE özelliklerini belirtir.

```csharp
public sealed class EmfLogFontPanose : EmfLogFont
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfLogFontPanose](emflogfontpanose)(EmfLogFont) | Yeni bir örneğini başlatır[`EmfLogFontPanose`](../emflogfontpanose) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Karakter glifleri kümesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. , WMF Karakter Kümesi numaralandırmasında ([MS-WMF] bölüm 2.1.1.5) bir değer OLMALIDIR. karakter kümesi bilinmiyorsa, meta dosyası işleme, o yazı tipiyle oluşturulan dizelerini çevirmeye veya yorumlamaya ÇALIŞMAMALIDIR. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Kırpma kesinliğini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. kırpma hassasiyeti, kısmen kırpma bölgesinin dışında kalan karakterlerin nasıl kırpılacağını tanımlar. WMF ClipPrecision Bayraklarından biri veya daha fazlası olabilir |
| [Culture](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/culture) { get; set; } | Sıfır olarak ayarlanması ve yoksayılması ZORUNLU olan 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Eşapman vektörü ile aygıtın x ekseni arasındaki derecenin onda biri cinsinden açıyı belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Eşapman vektörü, bir metin satırının taban çizgisine paraleldir. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Bir Yüz Adı (64 bayt) alır veya ayarlar: Yazı tipinin yazı tipi adını belirten en fazla 32 Unicode karakterden oluşan bir dize. Bu dizenin uzunluğu 32 karakterden azsa, sonlandırıcı bir NULL OLMALIDIR, bundan sonra bu alanın geri kalanı yoksayılmalıdır. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/fullname) { get; set; } | Yazı tipinin tam adını tanımlayan 64 Unicode karakterden oluşan bir dize alır veya ayarlar. bu dizenin uzunluğu 64 karakterden azsa, 'den sonra bu alanın geri kalanı yoksayılmalıdır ZORUNLU bir sonlandırıcı NULL OLMALIDIR. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Yazı tipinin karakter hücresinin veya karakterinin yüksekliğini mantıksal birimlerde belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. em boyutu olarak da bilinen karakter yüksekliği değeri, karakter hücre yüksekliği değerinden dahili satır aralığı değerinin çıkarılmasıyla elde edilen değerdir. Yazı tipi eşleyicisi, Yükseklik alanında belirtilen değeri aşağıdaki şekilde yorumlamalıdır . |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | 0x01 olarak ayarlanırsa italik bir yazı tipi belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar; aksi takdirde, 0x00. olarak AYARLANMALIDIR |
| [Match](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/match) { get; set; } | Alır veya ayarlar Bu alan MUTLAKA dikkate alınmamalıdır. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Her karakterin taban çizgisi ile aygıtın x ekseni arasındaki açıyı derecenin onda biri cinsinden belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Çıktı kesinliğini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. çıktı hassasiyeti, yazı tipinin istenen yükseklik, genişlik, karakter yönü, eşapman, aralık ve yazı tipi tipiyle ne kadar yakından eşleşmesi gerektiğini tanımlar. WMF OutPrecision numaralandırma değerinden bir değer OLMALIDIR |
| [Padding](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/padding) { get; set; } | Yalnızca bu yapının 32 bit hizalamasını sağlamak için var olan bir alanı alır veya ayarlar. Yok sayılmalıdır |
| [Panose](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/panose) { get; set; } | Mantıksal yazı tipinin PANOSE özelliklerini belirten bir Panose nesnesi (bölüm 2.2.21) alır veya ayarlar. Bu nesnenin tüm alanları sıfırsa, yok sayılmalıdır. |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | yazı tipinin aralığını ve ailesini belirten bir WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar. Yazı tipi aileleri, bir yazı tipinin görünümünü genel şekilde tanımlar. Belirtilen yazı tipi mevcut olmadığında bir yazı tipi belirtmek için tasarlanmıştır. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Çıktı kalitesini belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar. çıktı kalitesi, mantıksal yazı tipi niteliklerini gerçek bir fiziksel yazı tipininkilerle ne kadar yakından eşleştirmeye çalışılacağını tanımlar. WMF FontQuality numaralandırmasındaki değerlerden biri OLMALIDIR ([MS-WMF] bölüm 2.1.1.10). |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | 0x01 olarak ayarlanırsa üstü çizili bir yazı tipi belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar; aksi takdirde 0x00 olarak AYARLANMALIDIR. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/style) { get; set; } | Yazı tipinin stilini tanımlayan 32 Unicode karakterden oluşan bir dize alır veya ayarlar. bu dizenin uzunluğu 32 karakterden azsa, sonlandırıcı bir NULL OLMALIDIR, bundan sonra bu alanın geri kalanı yoksayılmalıdır. |
| [StyleSize](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/stylesize) { get; set; } | Yazı tipi ipucunun gerçekleştirildiği nokta boyutunu belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Sıfıra ayarlanırsa, LogFont field içindeki LogFont nesnesindeki Yükseklik alanına karşılık gelen nokta boyutunda yazı tipi ipucu gerçekleştirilir. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | 0x01 olarak ayarlanırsa altı çizili bir yazı tipi belirten 8 bitlik işaretsiz bir tamsayı alır veya ayarlar; aksi takdirde 0x00. olarak AYARLANMALIDIR |
| [VendorId](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/vendorid) { get; set; } | Alır veya ayarlar Bu alan MUTLAKA dikkate alınmamalıdır. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/version) { get; set; } | Alır veya ayarlar Bu alan yok sayılmalıdır ZORUNLU. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Sıfırdan 1000'e kadar aralığında yazı tipinin ağırlığını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Örneğin, 400 normaldir ve 700 kalındır. Bu değer sıfır ise, varsayılan bir ağırlık kullanılabilir. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Yazı tipindeki karakterlerinin mantıksal birimlerde ortalama genişliğini belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Genişlik alanı değeri sıfırsa, tipografın amaçladığı en boy oranına sahip bir yazı tipi bulmak için diğer LogFont değerlerinden uygun bir değer hesaplanmalıdır GEREKİR |

### Ayrıca bakınız

* class [EmfLogFont](../emflogfont)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
