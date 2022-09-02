---
title: Matrix
second_title: Aspose.Imaging for .NET API Referansı
description: GDI Matrisinin yerini alır.
type: docs
weight: 10550
url: /tr/net/aspose.imaging/matrix/
---
## Matrix class

GDI+ Matrisinin yerini alır.

```csharp
public class Matrix
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Matrix](matrix#constructor)() | Kimlik matrisi olarak Matrix sınıfının yeni bir örneğini başlatır. |
| [Matrix](matrix#constructor_1)(Matrix) | [`Matrix`](../matrix) sınıf. |
| [Matrix](matrix#constructor_2)(Rectangle, Point[]) | Yeni bir örneğini başlatır[`Matrix`](../matrix) belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme sınıf. |
| [Matrix](matrix#constructor_3)(RectangleF, PointF[]) | Yeni bir örneğini başlatır[`Matrix`](../matrix) belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme sınıf. |
| [Matrix](matrix#constructor_4)(float, float, float, float, float, float) | Yeni bir örneğini başlatır[`Matrix`](../matrix) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements) { get; } | Bunun öğelerini temsil eden bir dizi kayan nokta değeri alır.[`Matrix`](../matrix) . |
| [M11](../../aspose.imaging/matrix/m11) { get; } | İlk satırın ilk sütunundaki matris öğesini alır. X ekseni boyunca ölçeği temsil eder. |
| [M12](../../aspose.imaging/matrix/m12) { get; } | Birinci satır ikinci sütundaki matris öğesini alır. Y ekseni boyunca kaymayı temsil eder. |
| [M21](../../aspose.imaging/matrix/m21) { get; } | İkinci satır birinci sütundaki matris öğesini alır. X ekseni boyunca kaymayı temsil eder. |
| [M22](../../aspose.imaging/matrix/m22) { get; } | İkinci satır ikinci sütundaki matris öğesini alır. Y ekseni boyunca ölçeği temsil eder. |
| [M31](../../aspose.imaging/matrix/m31) { get; } | Üçüncü satır birinci sütundaki matris öğesini alır. X ekseni boyunca çeviriyi temsil eder. |
| [M32](../../aspose.imaging/matrix/m32) { get; } | Üçüncü satır birinci sütundaki matris öğesini alır. Y ekseni boyunca çeviriyi temsil eder. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals)(object) | BelirtilenObject bu örneğe eşittir. |
| [GetElements](../../aspose.imaging/matrix/getelements)() | Matris öğelerinin kopyasını alır. |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode)() | Bu örnek için bir karma kod döndürür. |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply)(Matrix) | Bu Matrisi, (varsayılan) Başa Ekle sırasını kullanarak matris parametresinde belirtilen matrisle çarpar. |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply_1)(Matrix, MatrixOrder) | Bu Matrisi, matris parametresinde belirtilen matrisle ve sıra parametresinde belirtilen sırayla çarpar. |
| [Reset](../../aspose.imaging/matrix/reset)() | Bu Matrisi, kimlik matrisinin öğelerine sahip olacak şekilde sıfırlar. |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate)(float) | Varsayılan (Prepend) sırayla bu Matris için başlangıç noktası (sıfır x ve y koordinatları) etrafında açı parametresinde belirtilen bir miktarın saat yönünde dönüşünü uygular. |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate_1)(float, MatrixOrder) | Bu Matris için, açı parametresinde belirtilen bir miktarın başlangıç noktası (sıfır x ve y koordinatları) etrafında belirtilen sırada saat yönünde dönüşünü uygular. |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat)(float, PointF) | Varsayılan (Prepend) sırayla bu Matrise belirtilen nokta etrafında saat yönünde bir dönüş uygular. |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat_1)(float, PointF, MatrixOrder) | Bu Matrix'e belirtilen sırada belirtilen nokta etrafında saat yönünde bir dönüş uygular. |
| [Scale](../../aspose.imaging/matrix/scale#scale)(float, float) | (varsayılan) Başa Ekle sırasını kullanarak belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrise uygular. |
| [Scale](../../aspose.imaging/matrix/scale#scale_1)(float, float, MatrixOrder) | Belirtilen ölçek vektörünü (scaleX ve scaleY) buna uygular[`Matrix`](../matrix) belirtilen sırayı kullanarak. |
| override [ToString](../../aspose.imaging/matrix/tostring)() | Bir döndürürString bu, bu örneği temsil eder. |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints)(PointF[]) | Bununla temsil edilen geometrik dönüşümü uygular.[`Matrix`](../matrix)belirli bir nokta dizisine. |
| [Translate](../../aspose.imaging/matrix/translate#translate)(float, float) | Belirtilen çeviri vektörünü buna uygular[`Matrix`](../matrix) kullanarak (varsayılan) Siparişi başa ekle. |
| [Translate](../../aspose.imaging/matrix/translate#translate_1)(float, float, MatrixOrder) | Belirtilen çeviri vektörünü belirtilen sırayla bu Matrix'e uygular. |
| static [Equals](../../aspose.imaging/matrix/equals)(Matrix, Matrix) | İki matrisin eşit olup olmadığını belirler. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip) | Bu bayrak biti, bu object tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, normalde sağ elini kullanan koordinat sistemini bir sol el sistemine değiştiren bazı eksenler etrafında bir ayna görüntüsü çevirmesi gerçekleştirdiğini gösterir. Sağ elini kullanan bir koordinat sistemi pozitif X ekseninin, pozitif Y eksenini kaplamak için saat yönünün tersine döndüğü bir yerdir , sağ elinizdeki parmakların başparmağınıza baktığınız zaman kıvrıldığı yöne benzer . Solak koordinat sistemi, pozitif X ekseninin döndüğü bir koordinat sistemidir pozitif Y eksenini sol elinizdeki parmakların kıvrıldığı yöne benzer bindirmek için saat yönünde çevirin. Uygun bir ayarlama dönüşü verildiğinde tüm çevirme açıları aynı olduğundan, orijinal çevirme veya yansıtma dönüşümünün açısını belirlemenin matematiksel bir yolu yoktur. NOT: TypeFlip, GENERAL_TRANSFORM'dan sonra eklendi public dolaşımdaydı ve bayrak bitleri, external kodunda ikili uyumsuzluk oluşturmadan artık uygun şekilde yeniden numaralandırılamıyordu. |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation) | Bu bayrak biti, bu object tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlerine ek olarak isteğe bağlı bir açıyla döndürme gerçekleştirdiğini gösterir. Bir döndürme, vektörün orijinal yönünden bağımsız olarak vektörlerin açılarını aynı miktarda değiştirir ve vektörün uzunluğunu değiştirmeden. Bu bayrak biti, the ile birbirini dışlar. |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale) | Genel bir ölçek, dikey vektörler arasındaki açı 'yi değiştirmeden x ve y yönlerinde vektörlerin uzunluğunu farklı miktarlarıyla çarpar. Bu bayrak biti, TypeUniformScale bayrağıyla birbirini dışlar. |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform) | Bu sabit, bu object tarafından tanımlanan dönüşümün giriş koordinatlarının keyfi bir dönüşümünü gerçekleştirdiğini gösterir. Bu dönüşüm yukarıdaki sabitlerden herhangi biri tarafından sınıflandırılabilirse, tür, ya sabit TypeIdentity ya da uygun bayrağın a birleşimi olacaktır. bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için bitler. |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity) | Bir kimlik dönüşümü, çıkış koordinatlarının her zaman giriş koordinatlarıyla aynı olduğu bir dönüşümdür. Bu dönüşüm, kimlik dönüşümünden başka bir şeyse, tür ya sabit GENERAL_TRANSFORM ya da uygun bayrak bitlerinin a birleşimi olacaktır. bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri. |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation) | Bu sabit, döndürme bayrağı bitlerinden herhangi biri için bir bit maskesidir. |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale) | Bu sabit, herhangi bir ölçek bayrağı biti için bir bit maskesidir. |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation) | Bu bayrak biti, bu object tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, in 90 derecenin katları kadar bir kadran dönüşü gerçekleştirdiğini gösterir. Bir döndürme, orijinal yönden bağımsız olarak vektörlerin açılarını aynı miktarda değiştirir vektörün ve vektörün uzunluğunu değiştirmeden. Bu bayrak biti, TypeGeneralRotation bayrağıyla birbirini dışlar. |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation) | Bir öteleme, vektörlerin uzunluğunu veya açısını değiştirmeden koordinatları x ve y'de sabit bir miktarda hareket ettirir. |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale) | Tek biçimli bir ölçek, vektörlerin uzunluğunu, vektörler arasındaki açıyı değiştirmeden hem x hem de y yönlerinde aynı miktarda ile çarpar. Bu bayrak biti, TypeGeneralScale bayrağıyla birbirini dışlar. |

### Notlar

Algoritmaların çoğu Sun'ın AffineTransform.java'sından alınmıştır. Dahili olarak kullanılan matris öğeleri için Java'nın adları. Java adlarının .net adlarına eşleştirilmesi: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear Y m01 M21 Shear X m M Çevir X m12 M32 Çevir Y

### Ayrıca bakınız

* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
