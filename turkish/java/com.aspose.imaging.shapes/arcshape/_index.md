---
title: "ArcShape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir yay şekli temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.shapes/arcshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape), [com.aspose.imaging.shapes.PieShape](../../com.aspose.imaging.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Bir yay şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ArcShape()](#ArcShape--) | Yeni bir `ArcShape` sınıfı örneği başlatır. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.imaging.RectangleF-float-float-) | Yeni bir `ArcShape` sınıfı örneği başlatır. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-) | Yeni bir `ArcShape` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [getStartPoint()](#getStartPoint--) | Başlangıç şekil noktasını alır. |
| [getEndPoint()](#getEndPoint--) | Bitiş şekil noktasını alır. |
| [isClosed()](#isClosed--) | Sipariş edilen şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setClosed(boolean value)](#setClosed-boolean-) | Sipariş edilen şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [reverse()](#reverse--) | Bu şekil için nokta sırasını tersine çevirir. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |

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

### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Yeni bir `ArcShape` sınıfı örneği başlatır.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.imaging.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Yeni bir `ArcShape` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Dikdörtgen. |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Tarama açısı. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Yeni bir `ArcShape` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Dikdörtgen. |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Tarama açısı. |
| isClosed | boolean | `true` olarak ayarlanırsa yay kapalı olur. Kapalı yay aslında bir elipseye dönüşür. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Şekil segmentlerini alır.

Değer: Şekil segmentleri.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Başlangıç şekil noktasını alır.

Değer: Başlangıç şekil noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Bitiş şekil noktasını alır.

Değer: Bitiş şekil noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Sipariş edilen şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı sipariş edilen şekli işlerken başlangıç ve bitiş noktaları bir anlam taşımaz.

Değer: Bu sipariş edilen şekil kapalıysa `True`; aksi takdirde `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Sipariş edilen şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı sipariş edilen şekli işlerken başlangıç ve bitiş noktaları bir anlam taşımaz.

Değer: Bu sipariş edilen şekil kapalıysa `True`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### reverse() {#reverse--}
```
public void reverse()
```


Bu şekil için nokta sırasını tersine çevirir.

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
