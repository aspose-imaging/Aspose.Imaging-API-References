---
title: "Figure"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Şekil."
type: docs
weight: 44
url: /tr/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Şekil. Şekiller için bir kapsayıcı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Figure()](#Figure--) | Yeni bir [Figure](../../com.aspose.imaging/figure) örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShapes()](#getShapes--) | Şeklin şekillerini alır. |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır veya ayarlar. |
| [isClosed()](#isClosed--) | Bu şeklin kapalı olup olmadığını gösteren değeri alır. |
| [setClosed(boolean value)](#setClosed-boolean-) | Bu şeklin kapalı olup olmadığını gösteren değeri ayarlar. |
| [getSegments()](#getSegments--) | Tüm şekil segmentlerini alır. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Şekle bir şekil ekler. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Şekle bir dizi şekil ekler. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Şekilden bir şekil kaldırır. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Şekilden bir dizi şekil kaldırır. |
| [reverse()](#reverse--) | Bu şeklin şekil sırasını ve şekil nokta sırasını tersine çevirir. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Nesnenin sınırlarını alır. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin mevcut nesneyle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Varsayılan karma işlevi olarak hizmet verir. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
Bu örnekler, GraphicsPath ve Graphics sınıflarını kullanarak bir Image yüzeyinde Figürler oluşturur ve manipüle eder. Örnek, yeni bir Image (Tiff türünde) oluşturur ve GraphicsPath sınıfının yardımıyla yollar çizer. Sonunda, Graphics sınıfı tarafından sunulan DrawPath yöntemi, yolları yüzeye render etmek için çağrılır.
``` java
// FileStream örneği oluşturun
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // TiffOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // ImageOptions örneği için kaynağı ayarlayın
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Image örneği oluşturun
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Graphics sınıfının bir örneğini oluşturun ve başlatın
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Graphics yüzeyini temizleyin
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // GraphicsPath sınıfının bir örneğini oluşturun
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Figure sınıfının bir örneğini oluşturun
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Figure nesnesine Şekiller ekleyin
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Figure nesnesini GraphicsPath'e ekleyin
        graphicspath.addFigure(figure);

        // Pen nesnesiyle siyah renkli yolu çizin
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Tüm değişiklikleri kaydedin.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### Figure() {#Figure--}
```
public Figure()
```


Yeni bir [Figure](../../com.aspose.imaging/figure) örneği başlatır. JSON serileştirmesi için gerekli bir yapıcı.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Şeklin şekillerini alır.

**Returns:**
com.aspose.imaging.Shape[] - Figür şekilleri.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Nesnenin sınırlarını alır veya ayarlar.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Bu figürün kapalı olup olmadığını gösteren bir değer alır. Kapalı bir figür, yalnızca ilk ve son figür şekilleri sürekli şekiller olduğunda bir fark yaratır. Böyle bir durumda, ilk şeklin ilk noktası, son şeklin son noktasından düz bir çizgiyle bağlanır.

**Returns:**
boolean - `True` bu figür kapalıysa; aksi takdirde, `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Bu figürün kapalı olup olmadığını gösteren bir değer ayarlar. Kapalı bir figür, yalnızca ilk ve son figür şekilleri sürekli şekiller olduğunda bir fark yaratır. Böyle bir durumda, ilk şeklin ilk noktası, son şeklin son noktasından düz bir çizgiyle bağlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `True` bu figür kapalıysa; aksi takdirinde, `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Tüm şekil segmentlerini alır.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Figür segmentleri.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Şekle bir şekil ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Eklenecek şekil. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
Bu örnekler, GraphicsPath ve Graphics sınıflarını kullanarak bir Image yüzeyinde Figürler oluşturur ve manipüle eder. Örnek, yeni bir Image (Tiff türünde) oluşturur ve GraphicsPath sınıfının yardımıyla yollar çizer. Sonunda, Graphics sınıfı tarafından sunulan DrawPath yöntemi, yolları yüzeye render etmek için çağrılır.
``` java
// FileStream örneği oluşturun
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // TiffOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // ImageOptions örneği için kaynağı ayarlayın
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Image örneği oluşturun
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Graphics sınıfının bir örneğini oluşturun ve başlatın
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Graphics yüzeyini temizleyin
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // GraphicsPath sınıfının bir örneğini oluşturun
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Figure sınıfının bir örneğini oluşturun
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Figure nesnesine Şekiller ekleyin
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Figure nesnesini GraphicsPath'e ekleyin
        graphicspath.addFigure(figure);

        // Pen nesnesiyle siyah renkli yolu çizin
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Tüm değişiklikleri kaydedin.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


Şekle bir dizi şekil ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Eklenecek şekiller. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Şekilden bir şekil kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Kaldırılacak şekil. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Şekilden bir dizi şekil kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Kaldırılacak şekil aralığı. |

### reverse() {#reverse--}
```
public void reverse()
```


Bu şeklin şekil sırasını ve şekil nokta sırasını tersine çevirir.

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
