---
title: "WmfRecorderGraphics2D"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Wmf kaydedicisi."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class WmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Wmf kaydedicisi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfRecorderGraphics2D(Rectangle frame, int inch)](#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-) | Yeni bir `WmfRecorderGraphics2D` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Arka plan modunu alır veya ayarlar. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Arka plan modunu alır veya ayarlar. |
| [endRecording()](#endRecording--) | Kaydı sonlandırır. |
| [fromWmfImage(WmfImage wmfImage)](#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-) | Mevcut Wmf görüntüsü için Wmf kaydedicisinin bir örneğini alır. |

## Example: This example shows how to create a WMF image and draw some geometric shapes using WmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Bu, varsayılan ekran çözünürlüğüdür.
int dpi = 96;

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Bir WMF görüntüsü oluştur.
com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D(frame, dpi);

// Görüntü kenarları boyunca 1 piksel genişliğinde siyah bir kalem kullanarak siyah bir dikdörtgen çizin.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Bir dikdörtgeni beyaz duman rengiyle doldurun.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// 1 piksel genişliğinde koyu yeşil bir kalem kullanarak iki çapraz çizgi çizin.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// {0, 0, 200, 200} dikdörtgeni içinde 2 piksel genişliğinde mavi bir kalem kullanarak bir yay çizin.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Bir yay doldurun
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 2 piksel genişliğinde kırmızı bir kalem kullanarak kübik bir bezier çizin.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Belirtilen konumda belirtilen boyutta bir raster görüntüsü çizin.
// Görüntü, istenen dikdörtgene sığacak şekilde ölçeklendirilir.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
{
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
}

// Bir metin dizesi çizin
graphics.drawString("Hello World!", new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular), com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekir.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Tüm çizim komutlarını içeren son WMF görüntüsünü alın
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = graphics.endRecording();
try {
    wmfImage.save(dir + "test.output.wmf");
} finally {
    wmfImage.dispose();
}
```

### WmfRecorderGraphics2D(Rectangle frame, int inch) {#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-}
```
public WmfRecorderGraphics2D(Rectangle frame, int inch)
```


Yeni bir `WmfRecorderGraphics2D` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | Metadoyayı görüntülemek için twip cinsinden ölçülen hedef dikdörtgen. |
| inç | int | İnç başına piksel sayısı. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Arka plan modunu alır veya ayarlar.

Değer: Arka plan modu.

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Arka plan modunu alır veya ayarlar.

Değer: Arka plan modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### endRecording() {#endRecording--}
```
public WmfImage endRecording()
```


Kaydı sonlandırır.

**Returns:**
[WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) - The result image.
### fromWmfImage(WmfImage wmfImage) {#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-}
```
public static WmfRecorderGraphics2D fromWmfImage(WmfImage wmfImage)
```


Mevcut Wmf görüntüsü için Wmf kaydedicisinin bir örneğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| wmfImage | [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) | Kaydedici alınacak Wmf görüntüsü. |

**Returns:**
[WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) - An instance of the [WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) class.
