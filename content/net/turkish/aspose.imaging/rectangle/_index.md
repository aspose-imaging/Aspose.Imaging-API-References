---
title: Rectangle
second_title: Aspose.Imaging for .NET API Referansı
description: Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tamsayı kümesini depolar.
type: docs
weight: 10830
url: /tr/aspose.imaging/rectangle/
---
## Rectangle structure

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tamsayı kümesini depolar.

```csharp
public struct Rectangle
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Yeni bir örneğini başlatır[`Rectangle`](../rectangle) belirtilen konum ve boyuta sahip yapı. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Yeni bir örneğini başlatır[`Rectangle`](../rectangle) belirtilen konum ve boyuta sahip yapı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Yeni bir örneğini alır[`Rectangle`](../rectangle) sahip yapı[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) ve[`Height`](./height) değerler sıfıra ayarlandı. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Toplamı olan y koordinatını alır veya ayarlar.[`Y`](./y) ve[`Height`](./height) bunun özellik değerleri[`Rectangle`](../rectangle) yapı. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Bunun yüksekliğini alır veya ayarlar[`Rectangle`](../rectangle) yapı. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Bunun tüm sayısal özelliklerinin olup olmadığını gösteren bir değer alır.[`Rectangle`](../rectangle) sıfır değerlerine sahip. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Bunun sol kenarının x koordinatını alır veya ayarlar[`Rectangle`](../rectangle) yapı. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Bunun sol üst köşesinin koordinatlarını alır veya ayarlar[`Rectangle`](../rectangle) yapı. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Toplamı olan x koordinatını alır veya ayarlar.[`X`](./x) ve[`Width`](./width) bunun özellik değerleri[`Rectangle`](../rectangle) yapı. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Bunun boyutunu alır veya ayarlar[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Bunun üst kenarının y koordinatını alır veya ayarlar[`Rectangle`](../rectangle) yapı. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Bunun genişliğini alır veya ayarlar[`Rectangle`](../rectangle) yapı. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Bunun sol üst köşesinin x koordinatını alır veya ayarlar[`Rectangle`](../rectangle) yapı. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Bunun sol üst köşesinin y koordinatını alır veya ayarlar[`Rectangle`](../rectangle) yapı. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Belirtileni dönüştürür[`RectangleF`](../rectanglef) bir yapıya[`Rectangle`](../rectangle) yuvarlatılarak yapı[`RectangleF`](../rectanglef) değerleri bir sonraki daha yüksek tamsayı değerlerine bağlar. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Bir[`Rectangle`](../rectangle) belirtilen kenar konumlarına sahip yapı. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Yeni bir[`Rectangle`](../rectangle) belirtilen iki noktadan Oluşturulan iki dikey[`Rectangle`](../rectangle) geçene eşit olacak*point1* ve*point2* . Bunlar tipik olarak zıt köşelerdir. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Belirtilen öğenin şişirilmiş bir kopyasını oluşturur ve döndürür[`Rectangle`](../rectangle) yapı. Kopya belirtilen miktarda şişirilir. Orijinal[`Rectangle`](../rectangle) yapı değiştirilmeden kalır. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Üçte birini döndürür[`Rectangle`](../rectangle) diğer ikisinin kesişimini temsil eden yapı[`Rectangle`](../rectangle) yapılar. Kavşak yoksa boş[`Rectangle`](../rectangle) döndürülür. |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Belirtileni dönüştürür[`RectangleF`](../rectanglef) bir[`Rectangle`](../rectangle) yuvarlayarak[`RectangleF`](../rectanglef)en yakın tamsayı değerlerine değerler. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Belirtileni dönüştürür[`RectangleF`](../rectanglef) bir[`Rectangle`](../rectangle) kısaltarak[`RectangleF`](../rectanglef) değerler. |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | [`Rectangle`](../rectangle) ikisinin birleşimini içeren yapı[`Rectangle`](../rectangle) yapılar. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Belirtilen noktanın bunun içinde bulunup bulunmadığını belirler.[`Rectangle`](../rectangle) yapı. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | ile temsil edilen dikdörtgen bölgenin*rect* tamamen bunun içindedir[`Rectangle`](../rectangle) yapı. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Belirtilen noktanın bunun içinde bulunup bulunmadığını belirler.[`Rectangle`](../rectangle) yapı. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | olup olmadığını test eder*obj* bir[`Rectangle`](../rectangle)aynı yer ve büyüklükteki yapı[`Rectangle`](../rectangle) yapı. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Bunun için karma kodu döndürür[`Rectangle`](../rectangle) yapı. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | Bunu şişirir[`Rectangle`](../rectangle) belirtilen miktarda. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | Bunu şişirir[`Rectangle`](../rectangle) belirtilen miktarda. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Bunu değiştirir[`Rectangle`](../rectangle) kendisinin ve belirtilenin kesişimi ile[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Bu dikdörtgenin aşağıdakilerle kesişip kesişmediğini belirler.*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Dikdörtgeni, genişliğini ve yüksekliğini pozitif, solu sağdan küçük ve üst kısmı alttan küçük yaparak normalleştirir. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Belirtilen miktara göre bu dikdörtgenin konumunu ayarlar. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Belirtilen miktara göre bu dikdörtgenin konumunu ayarlar. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Bunun özniteliklerini dönüştürür[`Rectangle`](../rectangle) insan tarafından okunabilir bir dizeye. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | İki tane olup olmadığını test eder.[`Rectangle`](../rectangle)yapılar eşit konum ve boyuta sahiptir. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | İki tane olup olmadığını test eder.[`Rectangle`](../rectangle) yapılar konum veya boyut bakımından farklılık gösterir. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
