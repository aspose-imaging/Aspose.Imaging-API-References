---
title: "HatchBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir tarama stiline, ön plan rengine ve arka plan rengine sahip dikdörtgen bir fırça tanımlar."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Bir tarama stiline, ön plan rengine ve arka plan rengine sahip dikdörtgen bir fırça tanımlar. Bu sınıf kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Tarama çizgilerinin rengini alır. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Tarama çizgilerinin rengini ayarlar. |
| [getBackgroundColor()](#getBackgroundColor--) | Tarama çizgileri arasındaki boşlukların rengini alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Tarama çizgileri arasındaki boşlukların rengini ayarlar. |
| [getHatchStyle()](#getHatchStyle--) | Bu fırçanın tarama stilini alır. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Bu fırçanın tarama stilini ayarlar. |

## Example: This example shows the creation and usage Pen objects.
Bu örnek, Pen nesnelerinin oluşturulmasını ve kullanımını gösterir. Örnek yeni bir Image oluşturur ve Image yüzeyine Dikdörtgenler çizer.
``` java

// BmpOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// FileCreateSource bir örneği oluşturun ve bunu BmpOptions örneği için Source olarak atayın
// İkinci Boolean parametresi, oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Belirtilen Yolda bir Image örneği oluştur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Graphics'in bir örneğini oluştur ve Image nesnesiyle başlat.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Grafik yüzeyini Beyaz Renk ile temizle.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Renk Kırmızı ve genişlik 5 olan bir Pen örneği oluştur.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // HatchBrush'ın bir örneğini oluştur ve özelliklerini ayarla.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Pen'in bir örneğini oluştur ve HatchBrush nesnesi ve genişlik ile başlat.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Pen nesnesini belirterek Dikdörtgenler çizin.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Pen nesnesini belirterek Dikdörtgenler çizin.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Tüm değişiklikleri kaydedin.
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Tarama çizgilerinin rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Tarama çizgilerinin rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Tarama çizgilerinin rengi. |


**Example: This example shows the creation and usage Pen objects.**
Bu örnek, Pen nesnelerinin oluşturulmasını ve kullanımını gösterir. Örnek yeni bir Image oluşturur ve Image yüzeyine Dikdörtgenler çizer.
``` java

// BmpOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// FileCreateSource bir örneği oluşturun ve bunu BmpOptions örneği için Source olarak atayın
// İkinci Boolean parametresi, oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Belirtilen Yolda bir Image örneği oluştur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Graphics'in bir örneğini oluştur ve Image nesnesiyle başlat.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Grafik yüzeyini Beyaz Renk ile temizle.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Renk Kırmızı ve genişlik 5 olan bir Pen örneği oluştur.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // HatchBrush'ın bir örneğini oluştur ve özelliklerini ayarla.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Pen'in bir örneğini oluştur ve HatchBrush nesnesi ve genişlik ile başlat.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Pen nesnesini belirterek Dikdörtgenler çizin.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Pen nesnesini belirterek Dikdörtgenler çizin.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Tüm değişiklikleri kaydedin.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Tarama çizgileri arasındaki boşlukların rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Tarama çizgileri arasındaki boşlukların rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Tarama çizgileri arasındaki boşlukların rengi. |


**Example: This example shows the creation and usage Pen objects.**
Bu örnek, Pen nesnelerinin oluşturulmasını ve kullanımını gösterir. Örnek yeni bir Image oluşturur ve Image yüzeyine Dikdörtgenler çizer.
``` java

// BmpOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// FileCreateSource bir örneği oluşturun ve bunu BmpOptions örneği için Source olarak atayın
// İkinci Boolean parametresi, oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Belirtilen Yolda bir Image örneği oluştur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Graphics'in bir örneğini oluştur ve Image nesnesiyle başlat.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Grafik yüzeyini Beyaz Renk ile temizle.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Renk Kırmızı ve genişlik 5 olan bir Pen örneği oluştur.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // HatchBrush'ın bir örneğini oluştur ve özelliklerini ayarla.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Pen'in bir örneğini oluştur ve HatchBrush nesnesi ve genişlik ile başlat.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Pen nesnesini belirterek Dikdörtgenler çizin.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Pen nesnesini belirterek Dikdörtgenler çizin.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Tüm değişiklikleri kaydedin.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Bu fırçanın tarama stilini alır.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Bu fırçanın tarama stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

