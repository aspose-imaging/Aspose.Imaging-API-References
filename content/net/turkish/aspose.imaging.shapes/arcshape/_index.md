---
title: ArcShape
second_title: Aspose.Imaging for .NET API Referansı
description: Bir yay şeklini temsil eder.
type: docs
weight: 10950
url: /tr/aspose.imaging.shapes/arcshape/
---
## ArcShape class

Bir yay şeklini temsil eder.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ArcShape](arcshape#constructor)() | Yeni bir örneğini başlatır[`ArcShape`](../arcshape) sınıf. |
| [ArcShape](arcshape#constructor_1)(RectangleF, float, float) | Yeni bir örneğini başlatır[`ArcShape`](../arcshape) sınıf. |
| [ArcShape](arcshape#constructor_2)(RectangleF, float, float, bool) | Yeni bir örneğini başlatır[`ArcShape`](../arcshape) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | Nesnenin sınırlarını alır. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | Şeklin merkezini alır. |
| [EndPoint](../../aspose.imaging.shapes/arcshape/endpoint) { get; } | Bitiş şekil noktasını alır. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | Şeklin segmentleri olup olmadığını gösteren bir değer alır. |
| [IsClosed](../../aspose.imaging.shapes/arcshape/isclosed) { get; set; } | Sıralı şeklin kapalı olup olmadığını gösteren bir değer alır veya ayarlar. Kapalı sıralı şekil işlenirken başlangıç ve bitiş noktalarının bir anlamı yoktur. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | Sol alt dikdörtgen noktasını alır. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | Sol üst dikdörtgen noktasını alır. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | Dikdörtgenin yüksekliğini alır. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Dikdörtgen genişliğini alır. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | Sağ alttaki dikdörtgen noktasını alır. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | Sağ üst dikdörtgen noktasını alır. |
| override [Segments](../../aspose.imaging.shapes/arcshape/segments) { get; } | Şekil parçalarını alır. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle) { get; set; } | Başlangıç açısını alır veya ayarlar. |
| [StartPoint](../../aspose.imaging.shapes/arcshape/startpoint) { get; } | Başlangıç şekil noktasını alır. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle) { get; set; } | Süpürme açısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [Reverse](../../aspose.imaging.shapes/arcshape/reverse)() | Bu şekil için noktaların sırasını tersine çevirir. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform)(Matrix) | Belirtilen dönüşümü şekle uygular. |

### Örnekler

Bu örnek, yeni bir Görüntü oluşturur ve Görüntü yüzeyinde Figures ve GraphicsPath kullanarak çeşitli şekiller çizer.

```csharp
[C#]

//BmpOptions örneğini oluşturur ve çeşitli özelliklerini ayarlar            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//FileCreateSource örneğini oluşturun ve bunu BmpOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Görüntü örneğini oluştur 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // Graphics sınıfının bir örneğini oluştur ve başlat
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Grafik yüzeyini temizle
    graphics.Clear(Color.Wheat);

    // GraphicsPath sınıfının bir örneğini oluştur
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    // Figure sınıfının bir örneğini oluşturun
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    // Figure nesnesine Şekil Ekle
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // Figure sınıfının bir örneğini oluşturun
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    // Figure nesnesine Şekil Ekle
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    // Figure nesnesini GraphicsPath'e ekle
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Siyah renkli Pen nesnesiyle yol çiz
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // tüm değişiklikleri kaydet.
    image.Save();
}
```

### Ayrıca bakınız

* class [PieShape](../pieshape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* ad alanı [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
