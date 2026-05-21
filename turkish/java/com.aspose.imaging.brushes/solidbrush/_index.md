---
title: "SolidBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Katı fırça, belirli bir renk ile sürekli çizim yapmak için tasarlanmıştır."
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

Solid brush, belirli bir renk ile sürekli çizim yapmak için tasarlanmıştır. Bu sınıf kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Yeni bir `SolidBrush` sınıfı örneği başlatır. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | Yeni bir `SolidBrush` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | Fırça rengini alır veya ayarlar. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Fırça rengini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
Bu örnek, Image yüzeyinde ilkel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PNG formatında yeni bir Image oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Image yüzeyinde ilkel şekiller çizer.
``` java
// FileStream örneği oluşturur.
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // PngOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın.
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // PngOptions için Kaynağı ayarlayın.
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Image örneği oluşturun
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Graphics sınıfının bir örneğini oluşturun ve başlatın
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Graphics yüzeyini temizleyin
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Pen nesnesi olarak Siyah com.aspose.imaging.Color belirterek bir Yay çizin,
        // Yayı çevreleyen bir Dikdörtgen, Başlangıç Açısı ve Tarama Açısı
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Pen nesnesi olarak Mavi com.aspose.imaging.Color ve koordinat Noktaları belirterek bir Bezier çizin.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Pen nesnesi olarak Yeşil com.aspose.imaging.Color ve bir dizi Nokta belirterek bir Eğri çizin.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Pen nesnesi ve çevreleyen bir Dikdörtgen kullanarak bir Elips çizin.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Bir Çizgi çizin
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Bir Pasta dilimi çizin
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Pen nesnesi olarak Kırmızı com.aspose.imaging.Color ve bir dizi Nokta belirterek bir Çokgen çizin.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Bir Dikdörtgen çizin
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın.
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // SolidBrush nesnesi ve Font kullanarak, belirli bir Noktada bir Dize çizin.
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Tüm değişiklikleri kaydedin.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Yeni bir `SolidBrush` sınıfı örneği başlatır.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


Yeni bir `SolidBrush` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Solid brush rengi. |

### getColor() {#getColor--}
```
public Color getColor()
```


Fırça rengini alır veya ayarlar.

Değer: Fırça rengi.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
Bu örnek, Image yüzeyinde ilkel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PNG formatında yeni bir Image oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Image yüzeyinde ilkel şekiller çizer.
``` java
// FileStream örneği oluşturur.
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // PngOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın.
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // PngOptions için Kaynağı ayarlayın.
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Image örneği oluşturun
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Graphics sınıfının bir örneğini oluşturun ve başlatın
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Graphics yüzeyini temizleyin
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Pen nesnesi olarak Siyah com.aspose.imaging.Color belirterek bir Yay çizin,
        // Yayı çevreleyen bir Dikdörtgen, Başlangıç Açısı ve Tarama Açısı
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Pen nesnesi olarak Mavi com.aspose.imaging.Color ve koordinat Noktaları belirterek bir Bezier çizin.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Pen nesnesi olarak Yeşil com.aspose.imaging.Color ve bir dizi Nokta belirterek bir Eğri çizin.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Pen nesnesi ve çevreleyen bir Dikdörtgen kullanarak bir Elips çizin.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Bir Çizgi çizin
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Bir Pasta dilimi çizin
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Pen nesnesi olarak Kırmızı com.aspose.imaging.Color ve bir dizi Nokta belirterek bir Çokgen çizin.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Bir Dikdörtgen çizin
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın.
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // SolidBrush nesnesi ve Font kullanarak, belirli bir Noktada bir Dize çizin.
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Tüm değişiklikleri kaydedin.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Fırça rengini alır veya ayarlar.

Değer: Fırça rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | java.lang.Object |  |

**Returns:**
boolean
