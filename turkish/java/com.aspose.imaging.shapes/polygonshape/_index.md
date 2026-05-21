---
title: "PolygonShape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Poligon şekli temsil eder."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Poligon şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Yeni bir `PolygonShape` sınıfı örneğini başlatır. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Yeni bir `PolygonShape` sınıfı örneğini başlatır. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Yeni bir `PolygonShape` sınıfı örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPoints()](#getPoints--) | Eğri noktalarını alır veya ayarlar. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Eğri noktalarını alır veya ayarlar. |
| [isClosed()](#isClosed--) | Şeklin kapalı olup olmadığını belirten değeri alır veya ayarlar. |
| [setClosed(boolean value)](#setClosed-boolean-) | Şeklin kapalı olup olmadığını belirten değeri alır veya ayarlar. |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [getCenter()](#getCenter--) | Şeklin merkezini alır. |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| [getStartPoint()](#getStartPoint--) | Başlangıç şekil noktasını alır. |
| [getEndPoint()](#getEndPoint--) | Bitiş şekil noktasını alır. |
| [reverse()](#reverse--) | Bu şekil için nokta sırasını tersine çevirir. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Nesnenin sınırlarını alır. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin mevcut nesneyle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Varsayılan karma işlevi olarak hizmet verir. |

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

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Yeni bir `PolygonShape` sınıfı örneğini başlatır.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Yeni bir `PolygonShape` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Yeni bir `PolygonShape` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |
| isClosed | boolean | Eğer `true` olarak ayarlanırsa çokgen kapalıdır. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Eğri noktalarını alır veya ayarlar.

Değer: Eğri noktaları.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Eğri noktalarını alır veya ayarlar.

Değer: Eğri noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Şeklin kapalı olup olmadığını belirten değeri alır veya ayarlar.

Değer: Şekil kapalıysa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Şeklin kapalı olup olmadığını belirten değeri alır veya ayarlar.

Değer: Şekil kapalıysa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Nesnenin sınırlarını alır.

Değer: Nesnenin sınırları.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Şeklin merkezini alır.

Değer: Şeklin merkezi.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Şekil segmentlerini alır.

Değer: Şekil segmentleri.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır.

Değer: Şeklin segmentleri varsa `True`; aksi takdirde `false`.

**Returns:**
boolean
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
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](../../com.aspose.imaging/pen) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Belirtilen dönüşümü şekle uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Uygulanacak dönüşüm. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin mevcut nesneyle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılan nesne. |

**Returns:**
boolean - equals sonucunu
### hashCode() {#hashCode--}
```
public int hashCode()
```


Varsayılan karma işlevi olarak hizmet verir.

**Returns:**
int - Geçerli nesne için bir karma kodu.
