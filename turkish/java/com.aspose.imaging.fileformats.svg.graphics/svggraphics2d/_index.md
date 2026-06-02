---
title: "SvgGraphics2D"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Svg görüntüsü oluşturmak için çizim komutları sağlar."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Svg görüntüsü oluşturmak için çizim komutları sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Yeni bir [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) sınıfının bir örneğini başlatır. |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Yeni bir [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Belirtilen konumda belirtilen resmi çizer. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Belirtilen konumda belirtilen boyutta belirtilen resmi çizer. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Belirtilen konumda ve belirtilen boyutta, belirtilen görüntünün belirtilen bölümünü çizer. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Bir Rectangle yapısı tarafından belirlenen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Bir Dikdörtgen yapısı tarafından belirtilen elipsin bir bölümünü temsil eden bir yay doldurur. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Kübik bezier çizer. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Metin dizesini çizer. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Çizgiyi çizer. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Yolu çizer. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Yolu doldurur. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Dikdörtgeni çizer. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Dikdörtgeni doldurur. |
| [endRecording()](#endRecording--) | Tüm çizim komutlarını [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) nesnesi aracılığıyla gerçekleştiren son Svg görüntüsünü alır. |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Görüntü kenarları boyunca 1 piksel genişliğinde siyah bir kalem kullanarak siyah bir dikdörtgen çizin.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Bir dikdörtgeni beyaz duman rengiyle doldurun.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// 1 piksel genişliğinde koyu yeşil bir kalem kullanarak iki çapraz çizgi çizin.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// {0, 0, 200, 200} dikdörtgeni içinde 2 piksel genişliğinde mavi bir kalem kullanarak bir yay çizin.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Bir yay doldurun
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 2 piksel genişliğinde kırmızı bir kalem kullanarak kübik bir bezier çizin.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Belirtilen konumda belirtilen boyutta bir raster görüntüsü çizin.
// Görüntü, istenen dikdörtgene sığacak şekilde ölçeklendirilir.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Bir metin dizesi çizin
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

// Doldurulacak bir yol oluştur
com.aspose.imaging.Figure figureToFill = new com.aspose.imaging.Figure();
figureToFill.setClosed(true);

com.aspose.imaging.GraphicsPath pathToFill = new com.aspose.imaging.GraphicsPath();
pathToFill.addFigure(figureToFill);

figureToFill.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(400, 0, 200, 100), 45, 300),
                new com.aspose.imaging.shapes.BezierShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 200),
                                        new com.aspose.imaging.PointF(400, 200),
                                        new com.aspose.imaging.PointF(500, 100),
                                        new com.aspose.imaging.PointF(600, 200),
                                }),
                new com.aspose.imaging.shapes.PolygonShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 100),
                                }),
                new com.aspose.imaging.shapes.RectangleShape(
                        new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
        });

// Yolu, sarı bir fırça ve kontur çizmek için yeşil bir kalem kullanarak doldurun
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Çizmek için bir yol oluştur
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// 5 piksel genişliğinde turuncu bir kalem kullanarak yolu çizin.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Tüm çizim komutlarını içeren son SVG görüntüsünü al.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = graphics.endRecording();
try {
    svgImage.save(dir + "test.output.svg");
} finally {
    svgImage.dispose();
}
```

### SvgGraphics2D(int width, int height, int dpi) {#SvgGraphics2D-int-int-int-}
```
public SvgGraphics2D(int width, int height, int dpi)
```


Yeni bir [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Çıktı Svg görüntüsünün genişliği. |
| yükseklik | int | Çıktı Svg görüntüsünün genişliği. |
| dpi | int | Cihaz çözünürlüğü, ör. inç başına 96 nokta. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Yeni bir [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | Çizim işlemlerinin yapılacağı görüntü. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Belirtilen konumda belirtilen resmi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çizilen görüntü. |
| origin | [Point](../../com.aspose.imaging/point) | Çizilen görüntünün konumu. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Belirtilen konumda belirtilen boyutta belirtilen resmi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çizilen görüntü. |
| origin | [Point](../../com.aspose.imaging/point) | Çizilen görüntünün konumu. |
| size | [Size](../../com.aspose.imaging/size) | Çizilen görüntünün istenen boyutu. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Belirtilen konumda ve belirtilen boyutta, belirtilen görüntünün belirtilen bölümünü çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Çizilecek görüntü nesnesinin bölümü. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Çizilen görüntünün konumu ve boyutu. Görüntü, dikdörtgene sığacak şekilde ölçeklendirilir. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çizilecek görüntü. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Bir Rectangle yapısı tarafından belirlenen bir elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin dış hatlarını çizmek için kalem. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Elipsin sınırları. |
| startAngle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| arcAngle | float | startAngle parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Bir Dikdörtgen yapısı tarafından belirtilen elipsin bir bölümünü temsil eden bir yay doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin dış hatlarını çizmek için kalem. |
| brush | [Brush](../../com.aspose.imaging/brush) | Şeklin içini doldurmak için fırça. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Elipsin sınırları. |
| startAngle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| arcAngle | float | startAngle parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Kübik bezier çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | Eğrinin başlangıç noktası. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | Eğri için ilk kontrol noktası. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | Eğri için ikinci kontrol noktası. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | Eğrinin bitiş noktası. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | Metni renderlamak için kullanılan yazı tipi. |
| metin | java.lang.String | Unicode metin dizesi. |
| origin | [Point](../../com.aspose.imaging/point) | Metin çalıştırmasının sol üst köşesi. |
| textColor | [Color](../../com.aspose.imaging/color) | Metin rengi. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Çizgiyi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| x1 | int | İlk noktanın x koordinatı. |
| y1 | int | İlk noktanın y koordinatı. |
| x2 | int | İkinci noktanın x koordinatı. |
| y2 | int | İkinci noktanın y koordinatı. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Yolu çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin dış hatlarını çizmek için kalem. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Çizilecek yol. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Yolu doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin dış hatlarını çizmek için kalem. |
| brush | [Brush](../../com.aspose.imaging/brush) | Şeklin içini doldurmak için fırça. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Çizilecek yol. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dikdörtgeni çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin dış hatlarını çizmek için kalem. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | int | Çizilecek dikdörtgenin genişliği. |
| yükseklik | int | Çizilecek dikdörtgenin yüksekliği. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Dikdörtgeni doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin dış hatlarını çizmek için kalem. |
| brush | [Brush](../../com.aspose.imaging/brush) | Şeklin içini doldurmak için fırça. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | int | Çizilecek dikdörtgenin genişliği. |
| yükseklik | int | Çizilecek dikdörtgenin yüksekliği. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Tüm çizim komutlarını [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) nesnesi aracılığıyla gerçekleştiren son Svg görüntüsünü alır.

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
