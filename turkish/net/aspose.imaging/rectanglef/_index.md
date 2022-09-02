---
title: RectangleF
second_title: Aspose.Imaging for .NET API Referansı
description: Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan noktalı sayı kümesini depolar.
type: docs
weight: 10840
url: /tr/net/aspose.imaging/rectanglef/
---
## RectangleF structure

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan noktalı sayı kümesini depolar.

```csharp
public struct RectangleF
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Yeni bir örneğini başlatır[`RectangleF`](../rectanglef) belirtilen konum ve boyuta sahip yapı. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Yeni bir örneğini başlatır[`RectangleF`](../rectanglef) belirtilen konum ve boyuta sahip yapı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | Yeni bir örneğini alır[`RectangleF`](../rectanglef) sahip yapı[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) ve[`Height`](./height) değerler sıfıra ayarlandı. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | Toplamı olan y koordinatını alır veya ayarlar.[`Y`](./y) ve[`Height`](./height) bunun[`RectangleF`](../rectanglef) yapı. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | Bunun yüksekliğini alır veya ayarlar[`RectangleF`](../rectanglef) yapı. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | olup olmadığını gösteren bir değer alır.[`Width`](./width) veya[`Height`](./height) bunun mülkü[`RectangleF`](../rectanglef) sıfır değerine sahiptir. |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | Bunun sol kenarının x koordinatını alır veya ayarlar[`RectangleF`](../rectanglef) yapı. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | Bunun sol üst köşesinin koordinatlarını alır veya ayarlar[`RectangleF`](../rectanglef) yapı. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | Toplamı olan x koordinatını alır veya ayarlar.[`X`](./x) ve[`Width`](./width) bunun[`RectangleF`](../rectanglef) yapı. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | Bunun boyutunu alır veya ayarlar[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | Bunun üst kenarının y koordinatını alır veya ayarlar[`RectangleF`](../rectanglef) yapı. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | Bunun genişliğini alır veya ayarlar[`RectangleF`](../rectanglef) yapı. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | Bunun sol üst köşesinin x koordinatını alır veya ayarlar[`RectangleF`](../rectanglef) yapı. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | Bunun sol üst köşesinin y koordinatını alır veya ayarlar[`RectangleF`](../rectanglef) yapı. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Bir[`RectangleF`](../rectanglef) belirtilen konumlarda sol üst köşesi ve sağ alt köşesi olan yapı. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | Yeni bir[`Rectangle`](../rectangle) belirtilen iki noktadan Yaratılanın iki köşesi[`Rectangle`](../rectangle) geçene eşit olacak*point1* ve*point2* . Bunlar tipik olarak zıt köşelerdir. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | Belirtilen öğenin şişirilmiş bir kopyasını oluşturur ve döndürür[`RectangleF`](../rectanglef)yapı. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değiştirilmeden kalır. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | Bir döndürür[`RectangleF`](../rectanglef) iki dikdörtgenin kesişimini temsil eden yapı. Kavşak yoksa ve boşsa[`RectangleF`](../rectanglef) döndürülür. |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | Bir birleşim oluşturan iki dikdörtgenin her ikisini de içerebilen olası en küçük üçüncü dikdörtgeni oluşturur. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | Belirtilen noktanın bunun içinde bulunup bulunmadığını belirler.[`RectangleF`](../rectanglef) yapı. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | ile temsil edilen dikdörtgen bölgenin*rect* tamamen bunun içindedir[`RectangleF`](../rectanglef) yapı. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | Belirtilen noktanın bunun içinde bulunup bulunmadığını belirler.[`RectangleF`](../rectanglef) yapı. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | olup olmadığını test eder*obj* bir[`RectangleF`](../rectanglef) bununla aynı yer ve büyüklükte[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | Bunun için hash kodunu alır[`RectangleF`](../rectanglef) yapı. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | Bunu şişirir[`RectangleF`](../rectanglef) belirtilen miktarda. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | Bunu şişirir[`RectangleF`](../rectanglef) belirtilen miktara göre yapı. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | Bunu değiştirir[`RectangleF`](../rectanglef)kendisinin ve belirtilenin kesişimi ile yapı[`RectangleF`](../rectanglef) yapı. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | Bu dikdörtgenin aşağıdakilerle kesişip kesişmediğini belirler.*rect* . |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | Dikdörtgeni, genişliğini ve yüksekliğini pozitif, solu sağdan küçük ve üst kısmı alttan küçük yaparak normalleştirir. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | Belirtilen miktara göre bu dikdörtgenin konumunu ayarlar. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | Belirtilen miktara göre bu dikdörtgenin konumunu ayarlar. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | Bunun özniteliklerini dönüştürür[`RectangleF`](../rectanglef) insan tarafından okunabilir bir dizeye. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | /. operatörünü uygular |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | İki tane olup olmadığını test eder.[`RectangleF`](../rectanglef)yapılar eşit konum ve boyuta sahiptir. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | Belirtileni dönüştürür[`Rectangle`](../rectangle) bir yapıya[`RectangleF`](../rectanglef) yapı. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | İki tane olup olmadığını test eder.[`RectangleF`](../rectanglef) yapılar konum veya boyut bakımından farklılık gösterir. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | *. operatörünü uygular |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
