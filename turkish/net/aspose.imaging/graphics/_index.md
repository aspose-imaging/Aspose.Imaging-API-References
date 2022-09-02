---
title: Graphics
second_title: Aspose.Imaging for .NET API Referansı
description: Geçerli montajda kullanılan grafik motoruna göre grafikleri temsil eder.
type: docs
weight: 9360
url: /tr/net/aspose.imaging/graphics/
---
## Graphics class

Geçerli montajda kullanılan grafik motoruna göre grafikleri temsil eder.

```csharp
public sealed class Graphics
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Graphics](graphics)(Image) | Yeni bir örneğini başlatır[`Graphics`](../graphics) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Klip bölgesini alır veya ayarlar. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Birleştirme kalitesini alır veya ayarlar. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Bu Aspose.Imaging.Graphics. 'nin yatay çözünürlüğünü alır |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Bu Aspose.Imaging.Graphics. 'nin dikey çözünürlüğünü alır |
| [Image](../../aspose.imaging/graphics/image) { get; } | Resmi alır. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Enterpolasyon modunu alır veya ayarlar. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Grafiklerin BeginUpdate çağrı durumunda olup olmadığını gösteren bir değer alır. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Bu Aspose.Imaging.Graphics. için dünya birimleri ve sayfa birimleri arasındaki ölçeklendirmeyi alır veya ayarlar |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Bu Aspose.Imaging.Graphics. içinde sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Düzgünleştirme modunu alır veya ayarlar. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Metin oluşturma ipucunu alır veya ayarlar. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Bunun için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar[`Graphics`](../graphics) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Aşağıdaki grafik işlemlerinin önbelleğe alınmasını başlatır. Daha sonra uygulanan grafik efektleri hemen uygulanmaz, bunun yerine EndUpdate tüm efektlerin bir kerede uygulanmasına neden olur. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Belirtilen rengi kullanarak grafik yüzeyini temizler. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.[`Rectangle`](../rectangle) yapı. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.[`RectangleF`](../rectanglef) yapı. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Bir çift koordinat, genişlik ve yükseklik ile belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Bir çift koordinat, genişlik ve yükseklik ile belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Dört ile tanımlanan bir Bézier spline çizer[`Point`](../point) yapılar. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Dört ile tanımlanan bir Bézier spline çizer[`PointF`](../pointf) yapılar. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Noktaları temsil eden sıralı dört koordinat çifti tarafından tanımlanan bir Bézier spline çizer. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Bir diziden bir dizi Bézier spline çizer.[`PointF`](../pointf) yapılar. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Bir diziden bir dizi Bézier spline çizer.[`Point`](../point) yapılar. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Bir dizi tarafından tanımlanan kapalı bir ana eğri çizer[`PointF`](../pointf) yapılar. Bu yöntem, 0,5 varsayılan gerilimi kullanır veAlternate doldurma modu. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Bir dizi tarafından tanımlanan kapalı bir ana eğri çizer[`Point`](../point) yapılar. Bu yöntem, 0,5 varsayılan gerilimi kullanır veAlternate doldurma modu. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Bir dizi tarafından tanımlanan kapalı bir ana eğri çizer[`PointF`](../pointf) Belirli bir gerilim kullanan yapılar. Bu yöntem bir varsayılan kullanırAlternate doldurma modu. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Bir dizi tarafından tanımlanan kapalı bir ana eğri çizer[`Point`](../point) Belirli bir gerilim kullanan yapılar. Bu yöntem bir varsayılan kullanırAlternate doldurma modu. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../pointf) yapılar. Bu yöntem, 0,5. varsayılan gerilimi kullanır |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`Point`](../point) yapılar. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../pointf) belirli bir gerilimi kullanan yapılar. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`Point`](../point) belirli bir gerilimi kullanan yapılar. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../pointf) yapılar. Çizim, dizinin başlangıcından ofset olarak başlar. Bu yöntem, 0,5. varsayılan gerilimini kullanır. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../pointf)Belirli bir gerilim kullanan yapılar. Çizim, dizinin başından itibaren ofset ile başlar. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`Point`](../point) belirli bir gerilimi kullanan yapılar. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Bir sınırlayıcı tarafından belirtilen bir elips çizer[`Rectangle`](../rectangle) yapı. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Bir sınırlayıcı tarafından tanımlanan bir elips çizer[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Bir koordinat çifti, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Bir koordinat çifti, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Belirtilen çizer[`Image`](./image) , belirtilen konumda orijinal fiziksel boyutunu kullanarak. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Belirtilen çizer[`Image`](./image) , belirtilen konumda orijinal fiziksel boyutunu kullanarak. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Belirtilen çizer[`Image`](./image) , belirtilen konumda orijinal fiziksel boyutunu kullanarak. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Bir koordinat çifti tarafından belirtilen konumda orijinal fiziksel boyutunu kullanarak belirtilen görüntüyü çizer. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Belirtilenin belirtilen kısmını çizer*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Belirtilen çizer[`Image`](./image) belirtilen konumda ve belirtilen boyutta. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Belirtilen bir konumda orijinal fiziksel boyutunu kullanarak belirli bir görüntü çizer. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Belirtilen bir konumda orijinal fiziksel boyutunu kullanarak belirli bir görüntü çizer. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Bir koordinat çifti tarafından belirtilen konumda orijinal fiziksel boyutunu kullanarak belirtilen görüntüyü çizer. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Belirtilen bir konumda orijinal fiziksel boyutunu kullanarak belirli bir görüntü çizer. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Belirtilen görüntüyü ölçeklendirmeden çizer ve gerekirse belirtilen dikdörtgene sığdırmak için keser. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | İkiyi birbirine bağlayan bir çizgi çizer[`Point`](../point) yapılar. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | İkiyi birbirine bağlayan bir çizgi çizer[`PointF`](../pointf) yapılar. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Koordinat çiftleri tarafından belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Koordinat çiftleri tarafından belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Bir diziyi birbirine bağlayan bir dizi çizgi parçası çizer.[`PointF`](../pointf) yapılar. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Bir diziyi birbirine bağlayan bir dizi çizgi parçası çizer.[`Point`](../point) yapılar. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | Bir çizer[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.[`Rectangle`](../rectangle) yapı ve iki radyal çizgi. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.[`RectangleF`](../rectanglef) yapı ve iki radyal çizgi. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Bir koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Bir koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Bir dizi tarafından tanımlanan bir çokgen çizer[`PointF`](../pointf) yapılar. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Bir dizi tarafından tanımlanan bir çokgen çizer[`Point`](../point) yapılar. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | tarafından belirtilen bir dikdörtgen çizer.[`Rectangle`](../rectangle) yapı. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | tarafından belirtilen bir dikdörtgen çizer.[`RectangleF`](../rectanglef) yapı. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | tarafından belirtilen bir dizi dikdörtgen çizer[`RectangleF`](../rectanglef) yapılar. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | tarafından belirtilen bir dizi dikdörtgen çizer[`Rectangle`](../rectangle) yapılar. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Belirtilen metin dizesini belirtilen konumda belirtilen[`Brush`](../brush) ve[`Font`](../font) nesneler. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Belirtilen metin dizesini belirtilen dikdörtgen içinde belirtilen[`Brush`](../brush) ve[`Font`](../font) nesneler. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Belirtilen metin dizesini belirtilen konumda belirtilen[`Brush`](../brush) ve[`Font`](../font) nesneler. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Belirtilen metin dizesini belirtilen konumda belirtilen[`Brush`](../brush) ve[`Font`](../font) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Belirtilen metin dizesini belirtilen dikdörtgen içinde belirtilen[`Brush`](../brush) ve[`Font`](../font) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Belirtilen metin dizesini belirtilen konumda belirtilen[`Brush`](../brush) ve[`Font`](../font) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | BeginUpdate çağrıldıktan sonra başlatılan grafik işlemlerinin önbelleğe alınmasını tamamlar. Bu yöntem çağrılırken önceki grafik işlemleri bir kerede uygulanacaktır. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Bir dizi tarafından tanımlanan kapalı bir ana eğri eğrisinin içini doldurur[`PointF`](../pointf) yapılar. Bu yöntem, 0,5 varsayılan gerilimi kullanır veAlternate doldurma modu. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Bir dizi tarafından tanımlanan kapalı bir ana eğri eğrisinin içini doldurur[`Point`](../point) yapılar. Bu yöntem, 0,5 varsayılan gerilimi kullanır veAlternate doldurma modu. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Bir dizi tarafından tanımlanan kapalı bir ana eğri eğrisinin içini doldurur[`PointF`](../pointf) Belirtilen doldurma modunu kullanan yapılar. Bu yöntem, 0,5. varsayılan gerilimi kullanır |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Bir dizi tarafından tanımlanan kapalı bir ana eğri eğrisinin içini doldurur[`Point`](../point) Belirtilen doldurma modunu kullanan yapılar. Bu yöntem, 0,5. varsayılan gerilimi kullanır |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Bir dizi tarafından tanımlanan kapalı bir ana eğri eğrisinin içini doldurur[`PointF`](../pointf) belirtilen doldurma modunu ve gerilimi kullanan yapılar. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Bir dizi tarafından tanımlanan kapalı bir ana eğri eğrisinin içini doldurur[`Point`](../point) belirtilen doldurma modunu ve gerilimi kullanan yapılar. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Bir sınırlayıcı dikdörtgen tarafından tanımlanan bir elipsin içini doldurur.[`Rectangle`](../rectangle) yapı. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Bir sınırlayıcı dikdörtgen tarafından tanımlanan bir elipsin içini doldurur.[`RectangleF`](../rectanglef) yapı. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Bir koordinat çifti, bir genişlik ve bir yükseklik tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Bir koordinat çifti, bir genişlik ve bir yükseklik tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Bir[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | tarafından belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur.[`RectangleF`](../rectanglef) yapı ve iki radyal çizgi. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | tarafından belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur.[`RectangleF`](../rectanglef) yapı ve iki radyal çizgi. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Bir çift koordinat, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Bir çift koordinat, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`PointF`](../pointf) yapılar veAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`Point`](../point) yapılar veAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`PointF`](../pointf) belirtilen doldurma modunu kullanan yapılar. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`Point`](../point) belirtilen doldurma modunu kullanan yapılar. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | ile belirtilen bir dikdörtgenin içini doldurur.[`Rectangle`](../rectangle) yapı. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | ile belirtilen bir dikdörtgenin içini doldurur.[`RectangleF`](../rectanglef) yapı. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | ile belirtilen bir dizi dikdörtgenin içini doldurur.[`RectangleF`](../rectanglef) yapılar. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | ile belirtilen bir dizi dikdörtgenin içini doldurur.[`Rectangle`](../rectangle) yapılar. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Bir[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Belirtilen metin dizesini belirtilen parametrelerle ölçer |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | [`Matrix`](../matrix) bunun yerel geometrik dönüşümünü temsil eden[`Graphics`](../graphics) belirtilen tarafından[`Matrix`](../matrix) belirtilenleri başa ekleyerek[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | [`Matrix`](../matrix) bunun yerel geometrik dönüşümünü temsil eden[`Graphics`](../graphics) belirtilen tarafından[`Matrix`](../matrix) belirtilen sırada. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | [`Transform`](./transform) kimlik özelliği. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem, dönüşümü dönüşüme hazırlar. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen miktarda döndürür. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen miktarlara göre ölçekler. Bu yöntem, ölçeklendirme matrisini dönüşümün başına ekler. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen miktarlara göre ölçeklendirir. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Belirtilen boyutlara göre yerel geometrik dönüşümü öteler. Bu yöntem, dönüşümün başına çeviriyi ekler. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen boyutlara göre çevirir. |

### Örnekler

Bu örnek, Görüntü yüzeyinde ilkel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PNG formatında yeni bir Görüntü oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Görüntü yüzeyine ilkel şekiller çizer.

```csharp
[C#]

//FileStream örneğini oluşturur
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //PngOptions örneğini oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //PngOptions için Kaynağı Ayarla
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Görüntü örneğini oluştur 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        // Graphics sınıfının bir örneğini oluştur ve başlat
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafik yüzeyini temizle
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Siyah renkli Pen nesnesini belirterek bir Yay çizin, 
        //Yay, Başlangıç Açısı ve Süpürme Açısını çevreleyen bir Dikdörtgen
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Pen nesnesini Mavi renk ve koordinat Noktalarına sahip olarak belirterek bir Bezier çizin.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Yeşil renge ve bir dizi Noktaya sahip Pen nesnesini belirterek bir Eğri çizin
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Pen nesnesini ve çevresindeki Dikdörtgeni kullanarak bir Elips çizin
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Bir çizgi çiz 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Bir Pasta segmenti çizin
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Kırmızı renk ve bir dizi Noktaya sahip Pen nesnesini belirterek bir Çokgen çizin
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Bir Dikdörtgen Çiz
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Bir SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //SolidBrush nesnesini ve Yazı Tipi'ni kullanarak belirli bir Noktada bir Dize çizin
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // tüm değişiklikleri kaydet.
        image.Save();
    }
}
```

### Ayrıca bakınız

* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
