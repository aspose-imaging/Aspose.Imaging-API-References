---
title: "EllipseShape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Elips şekli temsil eder."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.shapes/ellipseshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

Elips şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | Yeni bir `EllipseShape` sınıfı örneğini başlatır. |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.imaging.RectangleF-) | Yeni bir `EllipseShape` sınıfı örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
Bu örnek yeni bir Image oluşturur ve Image yüzeyinde Figures ve GraphicsPath kullanarak çeşitli şekiller çizer.
``` java
//BmpOptions bir örnek oluşturur ve çeşitli özelliklerini ayarlar.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//FileCreateSource bir örneği oluşturun ve bunu BmpOptions örneği için Source olarak atayın
//İkinci Boolean parametresi, oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Image örneği oluşturun
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Graphics sınıfının bir örneğini oluşturun ve başlatın
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Graphics yüzeyini temizleyin
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //GraphicsPath sınıfının bir örneğini oluşturun
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Figure sınıfının bir örneğini oluşturun
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Shape'i Figure nesnesine ekle.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Figure sınıfının bir örneğini oluşturun
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Shape'i Figure nesnesine ekle.
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //Figure nesnesini GraphicsPath'e ekleyin
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Pen nesnesiyle siyah renkli yolu çizin
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // tüm değişiklikleri kaydet.
    image.save();
} finally {
    image.dispose();
}
```

### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


Yeni bir `EllipseShape` sınıfı örneğini başlatır.

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.imaging.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


Yeni bir `EllipseShape` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Dikdörtgen. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Şekil segmentlerini alır.

Değer: Şekil segmentleri.

**Returns:**
com.aspose.imaging.ShapeSegment[]
