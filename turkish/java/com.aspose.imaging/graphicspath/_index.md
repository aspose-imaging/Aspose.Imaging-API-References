---
title: "GraphicsPath"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bağlantılı çizgiler ve eğrilerden oluşan bir seriyi temsil eder."
type: docs
weight: 52
url: /tr/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Bağlantılı çizgiler ve eğrilerden oluşan bir dizi temsil eder. Bu sınıf kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillMode()](#getFillMode--) | `com.aspose.imaging.GraphicsPath` içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir `com.aspose.imaging.FillMode` enum değerini alır. |
| [setFillMode(int value)](#setFillMode-int-) | Bu `com.aspose.imaging.GraphicsPath` içindeki şekillerin içlerinin nasıl doldurulacağını belirleyen bir `com.aspose.imaging.FillMode` sayımını ayarlar. |
| [getFigures()](#getFigures--) | Yol figürlerini alır. |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır veya ayarlar. |
| [reset()](#reset--) | Grafik yolunu boşaltır ve `com.aspose.imaging.FillMode` değerini `F:com.aspose.imaging.fillMode.alternate` olarak ayarlar. |
| [reverse()](#reverse--) | Bu `com.aspose.imaging.graphicsPath` içindeki her şeklin figür, şekil ve nokta sırasını tersine çevirir. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde, belirtilen `com.aspose.imaging.graphics` öğesinin görünür kırpma bölgesinde bulunup bulunmadığını gösterir. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde, belirtilen `com.aspose.imaging.graphics` kullanılarak bulunup bulunmadığını gösterir. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir. |
| [flatten()](#flatten--) | Bu yoldaki her eğriyi birbirine bağlı çizgi segmentleri dizisine dönüştürür. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Belirtilen dönüşümü uygular ve ardından bu `com.aspose.imaging.GraphicsPath` içindeki her eğriyi birbirine bağlı çizgi segmentleri dizisine dönüştürür. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Bu `com.aspose.imaging.GraphicsPath` içindeki her eğriyi birbirine bağlı çizgi segmentleri dizisine dönüştürür. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Yola ek bir ana hat ekler. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | `com.aspose.imaging.graphicsPath` öğesine ek bir ana hat ekler. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Bu `com.aspose.imaging.GraphicsPath` öğesini, bu yol belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrilerle değiştirir. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Yeni bir figür ekler. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Yeni figürler ekler. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Bir figür kaldırır. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Figürleri kaldırır. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Belirtilen `com.aspose.imaging.GraphicsPath` öğesini bu yola ekler. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Belirtilen `com.aspose.imaging.GraphicsPath` öğesini bu yola ekler. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Nesnenin sınırlarını alır. |
| [deepClone()](#deepClone--) | Bu grafik yolunun derin bir kopyasını oluşturur. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |

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

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


`GraphicsPath` sınıfının yeni bir örneğini başlatır.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


`GraphicsPath` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Başlatılacak figürler. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


`GraphicsPath` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Başlatılacak figürler. |
| fillMode | int | Doldurma modu. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


`GraphicsPath` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillMode | int | Doldurma modu. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


`com.aspose.imaging.GraphicsPath` içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir `com.aspose.imaging.FillMode` enum değerini alır.

**Returns:**
int - Doldurma modu. Bu `com.aspose.imaging.GraphicsPath` içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirten bir `com.aspose.imaging.FillMode` enum'ı.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Bu `com.aspose.imaging.GraphicsPath` içindeki şekillerin içlerinin nasıl doldurulacağını belirleyen bir `com.aspose.imaging.FillMode` sayımını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Doldurma modu. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Yol figürlerini alır.

**Returns:**
com.aspose.imaging.Figure[] - Yol şekilleri.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Nesnenin sınırlarını alır veya ayarlar.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Grafik yolunu boşaltır ve `com.aspose.imaging.FillMode` değerini `F:com.aspose.imaging.fillMode.alternate` olarak ayarlar.

### reverse() {#reverse--}
```
public void reverse()
```


Bu `com.aspose.imaging.graphicsPath` içindeki her şeklin figür, şekil ve nokta sırasını tersine çevirir.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde bulunup bulunmadığını true olarak döndürür; aksi takdirde false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Test edilecek noktayı temsil eden bir `com.aspose.imaging.PointF`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde bulunup bulunmadığını true olarak döndürür; aksi takdirde false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde bulunup bulunmadığını true olarak döndürür; aksi takdirde false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Test edilecek noktayı temsil eden bir `com.aspose.imaging.Point`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde bulunup bulunmadığını true olarak döndürür; aksi takdirde false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde, belirtilen `com.aspose.imaging.graphics` öğesinin görünür kırpma bölgesinde bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde bulunup bulunmadığını true olarak döndürür; aksi takdirde false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Test edilecek noktayı temsil eden bir `com.aspose.imaging.PointF`. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın içinde bulunup bulunmadığını true döndürür; aksi takdirde false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde, belirtilen `com.aspose.imaging.graphics` kullanılarak bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde bulunup bulunmadığını true olarak döndürür; aksi takdirde false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.graphicsPath` içinde bulunup bulunmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Test edilecek noktayı temsil eden bir `com.aspose.imaging.Point`. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` içinde bulunup bulunmadığını true olarak döndürür; aksi takdirde false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının içinde bulunup bulunmadığını true döndürür; aksi takdirde false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Test edilecek konumu belirten bir `com.aspose.imaging.PointF`. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının içinde bulunup bulunmadığını true döndürür; aksi takdirde false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının (altında) bulunup bulunmadığını true döndürür; aksi takdirde false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Test edilecek konumu belirten bir `com.aspose.imaging.PointF`. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının (altında) bulunup bulunmadığını true döndürür; aksi takdirde false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının içinde bulunup bulunmadığını true döndürür; aksi takdirde false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.pen` ile çizildiğinde gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Test edilecek konumu belirten bir `com.aspose.imaging.Point`. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının içinde bulunup bulunmadığını true döndürür; aksi takdirde false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının içinde bulunup bulunmadığını true döndürür; aksi takdirde false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Belirtilen noktanın bu `com.aspose.imaging.GraphicsPath` ana hattının (altında) bulunup bulunmadığını, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde ve belirtilen `com.aspose.imaging.graphics` kullanılarak gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Test edilecek konumu belirten bir `com.aspose.imaging.Point`. |
| pen | [Pen](../../com.aspose.imaging/pen) | Test edilecek `com.aspose.imaging.Pen`. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Görünürlüğü test edilecek `com.aspose.imaging.Graphics`. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın, belirtilen `com.aspose.imaging.Pen` ile çizildiğinde bu `com.aspose.imaging.GraphicsPath` dış hattının içinde bulunup bulunmadığını true döndürür; aksi takdirde false.
### flatten() {#flatten--}
```
public void flatten()
```


Bu yoldaki her eğriyi birbirine bağlı çizgi segmentleri dizisine dönüştürür.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Belirtilen dönüşümü uygular ve ardından bu `com.aspose.imaging.GraphicsPath` içindeki her eğriyi birbirine bağlı çizgi segmentleri dizisine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Bu `com.aspose.imaging.GraphicsPath`'i düzleştirmeden önce dönüştürmek için kullanılan bir `com.aspose.imaging.Matrix`. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Bu `com.aspose.imaging.GraphicsPath` içindeki her eğriyi birbirine bağlı çizgi segmentleri dizisine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Bu `com.aspose.imaging.GraphicsPath`'i düzleştirmeden önce dönüştürmek için kullanılan bir `com.aspose.imaging.Matrix`. |
| düzlük | float | Eğri ile düzleştirilmiş yaklaşımı arasındaki izin verilen maksimum hatayı belirtir. Varsayılan değer 0.25'tir. Düzlük değerini azaltmak, yaklaşımda kullanılan çizgi segmenti sayısını artırır. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Yola ek bir ana hat ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Yolun orijinal dış hattı ile bu yöntemin oluşturduğu yeni dış hat arasındaki genişliği belirten bir `com.aspose.imaging.Pen`. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


`com.aspose.imaging.graphicsPath` öğesine ek bir ana hat ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Yolun orijinal dış hattı ile bu yöntemin oluşturduğu yeni dış hat arasındaki genişliği belirten bir `com.aspose.imaging.Pen`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Yolu genişletmeden önce uygulanacak dönüşümü belirten bir `com.aspose.imaging.Matrix`. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Bu `com.aspose.imaging.GraphicsPath` öğesini, bu yol belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrilerle değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Yolun orijinal dış hattı ile bu yöntemin oluşturduğu yeni dış hat arasındaki genişliği belirten bir `com.aspose.imaging.Pen`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Yolu genişletmeden önce uygulanacak dönüşümü belirten bir `com.aspose.imaging.Matrix`. |
| düzlük | float | Eğriler için düzlüğü belirten bir değer. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | `srcRect` tarafından tanımlanan dikdörtgenin dönüştürüldüğü bir paralelkenarı tanımlayan `com.aspose.imaging.PointF` yapılarını içeren bir dizi. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından ima edilir. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `destPoints` tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir `com.aspose.imaging.RectangleF`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | `srcRect` tarafından tanımlanan dikdörtgenin dönüştürüldüğü bir paralelkenarı tanımlayan `com.aspose.imaging.PointF` yapılarını içeren bir dizi. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından ima edilir. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `destPoints` tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir `com.aspose.imaging.RectangleF`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir `com.aspose.imaging.Matrix`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | `srcRect` tarafından tanımlanan dikdörtgenin dönüştürüldüğü bir paralelkenarı tanımlayan `com.aspose.imaging.PointF` yapılarını içeren bir dizi. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından ima edilir. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `destPoints` tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir `com.aspose.imaging.RectangleF`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir `com.aspose.imaging.Matrix`. |
| warpModu | int | Bu warp işleminin perspektif mi yoksa bilineer mod mu kullandığını belirten bir `com.aspose.imaging.WarpMode` enum'ı. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu `com.aspose.imaging.graphicsPath` öğesine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | `srcRect` tarafından tanımlanan dikdörtgenin dönüştürüldüğü bir paralelkenarı tanımlayan `com.aspose.imaging.PointF` yapılarını içeren bir dizi. Dizi üç ya da dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından ima edilir. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `destPoints` tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir `com.aspose.imaging.RectangleF`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir `com.aspose.imaging.Matrix`. |
| warpModu | int | Bu warp işleminin perspektif mi yoksa bilineer mod mu kullandığını belirten bir `com.aspose.imaging.WarpMode` enum'ı. |
| düzlük | float | 0 ile 1 arasında bir değer olup, ortaya çıkan yolun ne kadar düz olduğunu belirtir. Daha fazla bilgi için `com.aspose.imaging.GraphicsPath.flatten` yöntemlerine bakın. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Yeni bir figür ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Eklenecek şekil. |


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

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


Yeni figürler ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Eklenecek şekiller. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
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

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Bir figür kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Kaldırılacak şekil. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Figürleri kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Kaldırılacak şekiller. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Belirtilen `com.aspose.imaging.GraphicsPath` öğesini bu yola ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Eklenecek `com.aspose.imaging.GraphicsPath`. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Belirtilen `com.aspose.imaging.GraphicsPath` öğesini bu yola ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Eklenecek `com.aspose.imaging.GraphicsPath`. |
| bağla | boolean | Eklenen yoldaki ilk şeklin bu yoldaki son şeklin bir parçası olup olmadığını belirten bir Boolean değerdir. true değeri, eklenen yoldaki ilk şeklin bu yoldaki son şeklin bir parçası olduğunu belirtir. false değeri, eklenen yoldaki ilk şeklin bu yoldaki son şekilden ayrı olduğunu belirtir. |

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
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Bu grafik yolunun derin bir kopyasını oluşturur.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Belirtilen dönüşümü şekle uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Uygulanacak dönüşüm. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
