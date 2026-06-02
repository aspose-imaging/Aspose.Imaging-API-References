---
title: "MetafileRecorderGraphics2D"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Metadosyalar kaydedici grafikleri"
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

Metadosyalar kaydedici grafikleri
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getClip()](#getClip--) | Bu Graphics nesnesinin çizim bölgesini sınırlayan bir Region'ı alır veya ayarlar |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Bu Graphics nesnesinin çizim bölgesini sınırlayan bir Region'ı alır veya ayarlar |
| [getClipBounds()](#getClipBounds--) | Kırpma sınırlarını alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka planın rengini alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka planın rengini ayarlar. |
| [clear()](#clear--) | Graphics nesnesinin durumunu temizler |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Bir Rectangle yapısı tarafından belirlenen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Kübik bezier çizer. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Poli kübik bezier çizer. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Elipsi çizer. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Elipsi doldurur. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Belirtilen konumda, orijinal fiziksel boyutunu kullanarak belirtilen Görüntüyü çizer. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Görüntüyü çizer. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Görüntüyü çizer. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Belirtilen konumda ve belirtilen boyutta, belirtilen Görüntünün belirtilen bölümünü çizer. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Çizgiyi çizer. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Çizgiyi çizer. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Poligon çizgisini çizer. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Yolu çizer. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Yolu doldurur. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Pasta dilimini çizer. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Pastayı doldurur. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Poligonu çizer. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Poligonu doldurur. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Poligonu doldurur. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Dikdörtgeni çizer. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Dikdörtgeni çizer. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Dikdörtgeni doldurur. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Dizgiyi çizer. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Dizgiyi çizer. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Bu Graphics'in kırpma bölgesini, bir Rectangle yapısı tarafından belirtilen alanı dışlamak üzere günceller. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Bu Graphics'in kırpma bölgesini, bir Region tarafından belirtilen alanı dışlamak üzere günceller. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Bu Graphics'in kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Rectangle yapısının kesişimi olarak günceller. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Bu Graphics'in kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Region'un kesişimi olarak günceller. |
| [resetClip()](#resetClip--) | Kırpmayı sıfırlar. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Bu Graphics'in dünya dönüşümünü belirtilen Matris ile çarpar. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Bu Graphics'in dünya dönüşümünü belirtilen Matris ile belirtilen sırada çarpar. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Bu Graphics'in dönüşüm matrisine belirtilen çeviriyi ön ekleyerek koordinat sisteminin başlangıç noktasını değiştirir. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Bu Graphics'in dönüşüm matrisine belirtilen çeviriyi belirtilen sırada uygulayarak koordinat sisteminin başlangıç noktasını değiştirir. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Bu Graphics'in dönüşüm matrisine belirtilen rotasyonu uygular. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Bu Graphics'in dönüşüm matrisine belirtilen rotasyonu belirtilen sırada uygular. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Bu Graphics'in dönüşüm matrisine belirtilen ölçekleme işlemini nesnenin dönüşüm matrisine ön ekleyerek uygular. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Bu Graphics'in dönüşüm matrisine belirtilen ölçekleme işlemini belirtilen sırada uygular. |
| [getTransform()](#getTransform--) | Dünya dönüşümünü alır. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Dönüşümü ayarlar. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// Görüntünün piksel cinsinden boyutu
int deviceWidth = 600;
int deviceHeight = 400;

// Görüntünün milimetre cinsinden boyutu
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Bir EMF görüntüsü oluştur.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Görüntü kenarları boyunca 1 piksel genişliğinde siyah bir kalem kullanarak siyah bir dikdörtgen çizin.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Bir dikdörtgeni beyaz duman rengiyle doldurun.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// 1 piksel genişliğinde koyu yeşil bir kalem kullanarak iki çapraz çizgi çizin.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

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
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Bir metin dizesi çizin
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
com.aspose.imaging.fileformats.emf.EmfImage emfImage = graphics.endRecording();
try {
    emfImage.save(dir + "test.output.emf");
} finally {
    emfImage.dispose();
}
```

### MetafileRecorderGraphics2D() {#MetafileRecorderGraphics2D--}
```
public MetafileRecorderGraphics2D()
```


### getClip() {#getClip--}
```
public Region getClip()
```


Bu Graphics nesnesinin çizim bölgesini sınırlayan bir Region'ı alır veya ayarlar

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Bu Graphics nesnesinin çizim bölgesini sınırlayan bir Region'ı alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | Kırpma bölgesi. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Kırpma sınırlarını alır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka planın rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Arka planın rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### clear() {#clear--}
```
public void clear()
```


Graphics nesnesinin durumunu temizler

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Bir Rectangle yapısı tarafından belirlenen bir elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Elipsin sınırları. |
| startAngle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece cinsinden). |
| arcAngle | float | Başlangıç açısı parametresinden yayının son noktasına doğru saat yönünde ölçülen derece cinsinden açı. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Kübik bezier çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| pt1 | [Point](../../com.aspose.imaging/point) | Eğrinin başlangıç noktası. |
| pt2 | [Point](../../com.aspose.imaging/point) | Eğri için ilk kontrol noktası. |
| pt3 | [Point](../../com.aspose.imaging/point) | Eğri için ikinci kontrol noktası. |
| pt4 | [Point](../../com.aspose.imaging/point) | Eğrinin bitiş noktası. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Poli kübik bezier çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Noktalar. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Elipsi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Elipsin sınırları. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Elipsi doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Dolgunun özelliklerini belirleyen fırça. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Elipsin sınırları. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Belirtilen konumda, orijinal fiziksel boyutunu kullanarak belirtilen Görüntüyü çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çizilecek görüntü. |
| location | [Point](../../com.aspose.imaging/point) | Çizilen görüntünün sol üst köşesinin konumu. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Görüntüyü çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageBytes | byte[] | Görüntü baytları. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef dikdörtgen. |
| srcUnit | int | Kaynak birim. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Görüntüyü çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef dikdörtgen. |
| srcUnit | int | Kaynak birim. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Belirtilen konumda ve belirtilen boyutta, belirtilen Görüntünün belirtilen bölümünü çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çizilecek görüntü. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Çizilen görüntünün konumunu ve boyutunu belirten dikdörtgen yapısı. Görüntü, dikdörtgene sığacak şekilde ölçeklendirilir. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Çizilecek görüntü nesnesinin bölümünü belirten dikdörtgen yapısı. |
| srcUnit | int | srcRect parametresi tarafından kullanılan ölçü birimleri. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Çizgiyi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| x1 | int | İlk noktanın x koordinatı. |
| y1 | int | İlk noktanın y koordinatı. |
| x2 | int | İkinci noktanın x koordinatı. |
| y2 | int | İkinci noktanın y koordinatı. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Çizgiyi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| pt1 | [Point](../../com.aspose.imaging/point) | İlk nokta. |
| pt2 | [Point](../../com.aspose.imaging/point) | İkinci nokta. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Poligon çizgisini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Noktalar. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Yolu çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Çizilecek yol. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Yolu doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| brush | [Brush](../../com.aspose.imaging/brush) | Dolgunun özelliklerini belirleyen fırça. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Doldurulacak yol. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Pasta dilimini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Elipsin sınırları. |
| startAngle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece cinsinden). |
| sweepAngle | float | Başlangıç açısı parametresinden yayının son noktasına doğru saat yönünde ölçülen derece cinsinden açı. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Pastayı doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Dolgunun özelliklerini belirleyen fırça. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Elipsin sınırları. |
| startAngle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece cinsinden). |
| sweepAngle | float | Başlangıç açısı parametresinden yayının son noktasına doğru saat yönünde ölçülen derece cinsinden açı. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Poligonu çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Noktalar. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Poligonu doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Dolgunun özelliklerini belirleyen fırça. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Noktalar. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Poligonu doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Dolgunun özelliklerini belirleyen fırça. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Noktalar. |
| fillMode | int | Doldurma modu. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dikdörtgeni çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | int | Çizilecek dikdörtgenin genişliği. |
| yükseklik | int | Çizilecek dikdörtgenin yüksekliği. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Dikdörtgeni çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Şeklin rengini, genişliğini ve stilini belirleyen kalem. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Çizilecek dikdörtgen. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Dikdörtgeni doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Dolgunun özelliklerini belirleyen fırça. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Doldurulacak dikdörtgen. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Dizgiyi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dize | java.lang.String | Dize. |
| font | [Font](../../com.aspose.imaging/font) | Dizenin metin biçimini tanımlayan yazı tipi. |
| color | [Color](../../com.aspose.imaging/color) | Metin rengi. |
| x | int | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | int | Çizilen metnin sol üst köşesinin y koordinatı. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // İlk olarak, görüntü boyutunu alın
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // İkinci olarak, görüntünün ana diyagonalı boyunca bir metin dizesi yerleştirmek için bir dönüşüm hesaplayın -
    // sol üst köşeden sağ alt köşeye.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Ardından, dönüşümü ayarlayın.
    graphics.setTransform(transform);

    // Son olarak, ana diyagonal boyunca bir filigran (pembe renkli metin dizesi) yerleştirin.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Filigranlı görüntüyü başka bir EMF dosyasına kaydedin.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

### drawString(String string, Font font, Color color, int x, int y, float angle) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-}
```
public void drawString(String string, Font font, Color color, int x, int y, float angle)
```


Dizgiyi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dize | java.lang.String | Dize. |
| font | [Font](../../com.aspose.imaging/font) | Dizenin metin biçimini tanımlayan yazı tipi. |
| color | [Color](../../com.aspose.imaging/color) | Metin rengi. |
| x | int | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | int | Çizilen metnin sol üst köşesinin y koordinatı. |
| angle | float | Cihazın x ekseni ile kaçış vektörü arasındaki açı derece cinsinden. Kaçış vektörü, bir metin satırının temel çizgisine paraleldir. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Bu Graphics'in kırpma bölgesini, bir Rectangle yapısı tarafından belirtilen alanı dışlamak üzere günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Klip bölgesinden hariç tutulacak dikdörtgeni belirten dikdörtgen yapısı. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Bu Graphics'in kırpma bölgesini, bir Region tarafından belirtilen alanı dışlamak üzere günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Klip bölgesinden hariç tutulacak bölgeyi belirten bölge. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Bu Graphics'in kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Rectangle yapısının kesişimi olarak günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Mevcut klip bölgesiyle kesişecek dikdörtgen yapısı. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Bu Graphics'in kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Region'un kesişimi olarak günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Mevcut bölgeyle kesişecek bölge. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Kırpmayı sıfırlar.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Bu Graphics'in dünya dönüşümünü belirtilen Matris ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Dünya dönüşümünü çarpan matris. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Bu Graphics'in dünya dönüşümünü belirtilen Matris ile belirtilen sırada çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Dünya dönüşümünü çarpan matris. |
| sıra | int | Çarpmanın sırası. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Bu Graphics'in dönüşüm matrisine belirtilen çeviriyi ön ekleyerek koordinat sisteminin başlangıç noktasını değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Çevirmenin x koordinatı. |
| y | float | Çevirmenin y koordinatı. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Bu Graphics'in dönüşüm matrisine belirtilen çeviriyi belirtilen sırada uygulayarak koordinat sisteminin başlangıç noktasını değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Çevirmenin x koordinatı. |
| y | float | Çevirmenin y koordinatı. |
| sıra | int | Çevirmenin dönüşüm matrisine ön eklenip ya da son eklenip eklenmediğini belirtir. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Bu Graphics'in dönüşüm matrisine belirtilen rotasyonu uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı derece cinsinden. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Bu Graphics'in dönüşüm matrisine belirtilen rotasyonu belirtilen sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı derece cinsinden. |
| center | [PointF](../../com.aspose.imaging/pointf) | Dönme merkezi. |
| sıra | int | Dönüşün matris dönüşümüne son eklenip ön eklenip eklenmediğini belirtir. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Bu Graphics'in dönüşüm matrisine belirtilen ölçekleme işlemini nesnenin dönüşüm matrisine ön ekleyerek uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | X yönündeki ölçek faktörü. |
| sy | float | Y yönündeki ölçek faktörü. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Bu Graphics'in dönüşüm matrisine belirtilen ölçekleme işlemini belirtilen sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | X yönündeki ölçek faktörü. |
| sy | float | Y yönündeki ölçek faktörü. |
| sıra | int | Ölçekleme işleminin dönüşüm matrisine ön eklenip son eklenip eklenmediğini belirtir. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Dünya dönüşümünü alır.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Dönüşümü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Yeni dönüşüm matrisi. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // İlk olarak, görüntü boyutunu alın
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // İkinci olarak, görüntünün ana diyagonalı boyunca bir metin dizesi yerleştirmek için bir dönüşüm hesaplayın -
    // sol üst köşeden sağ alt köşeye.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Ardından, dönüşümü ayarlayın.
    graphics.setTransform(transform);

    // Son olarak, ana diyagonal boyunca bir filigran (pembe renkli metin dizesi) yerleştirin.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Filigranlı görüntüyü başka bir EMF dosyasına kaydedin.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

