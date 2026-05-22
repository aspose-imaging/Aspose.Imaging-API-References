---
title: "Pen"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Çizgileri, eğrileri ve şekilleri çizmek için kullanılan bir nesneyi tanımlar."
type: docs
weight: 81
url: /tr/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Çizgileri, eğrileri ve şekilleri çizmek için kullanılan bir nesneyi tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | Belirtilen renk ile `Pen` sınıfının yeni bir örneğini başlatır. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | Belirtilen `Color` ve `Pen.Width` özellikleriyle `Pen` sınıfının yeni bir örneğini başlatır. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | Belirtilen `Brush` ile `Pen` sınıfının yeni bir örneğini başlatır. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | Belirtilen `Brush` ve `Pen.Width` ile `Pen` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Bu `Pen`in genişliğini, çizim için kullanılan Graphics nesnesinin birimlerinde alır. |
| [setWidth(float value)](#setWidth-float-) | Bu `Pen`in genişliğini, çizim için kullanılan Graphics nesnesinin birimlerinde ayarlar. |
| [getStartCap()](#getStartCap--) | Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılan kapak stilini alır. |
| [setStartCap(int value)](#setStartCap-int-) | Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılan kapak stilini ayarlar. |
| [getEndCap()](#getEndCap--) | Bu `Pen` ile çizilen çizgilerin sonunda kullanılan kapak stilini alır. |
| [setEndCap(int value)](#setEndCap-int-) | Bu `Pen` ile çizilen çizgilerin sonunda kullanılan kapak stilini ayarlar. |
| [getDashCap()](#getDashCap--) | Bu `Pen` ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini alır. |
| [setDashCap(int value)](#setDashCap-int-) | Bu `Pen` ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini ayarlar. |
| [getLineJoin()](#getLineJoin--) | Bu `Pen` ile çizilen iki ardışık çizginin uçları için birleştirme stilini alır. |
| [setLineJoin(int value)](#setLineJoin-int-) | Bu `Pen` ile çizilen iki ardışık çizginin uçları için birleştirme stilini ayarlar. |
| [getCustomStartCap()](#getCustomStartCap--) | Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak alır. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak ayarlar. |
| [getCustomEndCap()](#getCustomEndCap--) | Bu `Pen` ile çizilen çizgilerin sonunda kullanılacak özel bir kapak alır. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | Bu `Pen` ile çizilen çizgilerin sonunda kullanılacak özel bir kapak ayarlar. |
| [getMiterLimit()](#getMiterLimit--) | Köşeli bir köşedeki birleştirme kalınlığının sınırını alır. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Miter köşesindeki birleşmenin kalınlık sınırını ayarlar. |
| [getAlignment()](#getAlignment--) | Bu `Pen` için hizalamayı alır. |
| [setAlignment(int value)](#setAlignment-int-) | Bu `Pen` için hizalamayı ayarlar. |
| [getTransform()](#getTransform--) | Bu `Pen` için geometrik dönüşümün bir kopyasını alır. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Bu `Pen` için geometrik dönüşümün bir kopyasını ayarlar. |
| [getPenType()](#getPenType--) | Bu `Pen` ile çizilen çizgilerin stilini alır. |
| [getColor()](#getColor--) | Bu `Pen`'in rengini alır. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Bu `Pen`'in rengini ayarlar. |
| [getBrush()](#getBrush--) | Bu `Pen`'in özelliklerini belirleyen `Brush`'ı alır. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | Bu `Pen`'in özelliklerini belirleyen `Brush`'ı ayarlar. |
| [getDashStyle()](#getDashStyle--) | Bu `Pen` ile çizilen kesikli çizgiler için kullanılan stili alır. |
| [setDashStyle(int value)](#setDashStyle-int-) | Bu `Pen` ile çizilen kesikli çizgiler için kullanılan stili ayarlar. |
| [getDashOffset()](#getDashOffset--) | Bir çizginin başlangıcından kesik desenin başlangıcına olan mesafeyi alır. |
| [setDashOffset(float value)](#setDashOffset-float-) | Bir çizginin başlangıcından kesik desenin başlangıcına olan mesafeyi ayarlar. |
| [getDashPattern()](#getDashPattern--) | Özel kesik ve boşluklardan oluşan bir dizi alır. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Özel kesik ve boşluklardan oluşan bir dizi ayarlar. |
| [getCompoundArray()](#getCompoundArray--) | Bir bileşik kalemi belirten değerlerden oluşan bir dizi alır. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Bir bileşik kalemi belirten değerlerden oluşan bir dizi ayarlar. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Bu `Pen` ile çizilen çizgilerin sonlandırılmasında kullanılan kapak stilini belirleyen değerleri ayarlar. |
| [resetTransform()](#resetTransform--) | Bu `Pen` için geometrik dönüşüm matrisini birim matrisine sıfırlar. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Bu `Pen` için dönüşüm matrisini belirtilen `Matrix` ile çarpar. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Bu `Pen` için dönüşüm matrisini belirtilen `Matrix` ile belirtilen sırada çarpar. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Yerel geometrik dönüşümü belirtilen boyutlarla kaydırır. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada kaydırır. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen faktörlerle belirtilen sırada ölçeklendir. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Yerel geometrik dönüşümü belirtilen açıyla döndürür. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırada döndürür. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) |  |

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

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


Belirtilen renk ile `Pen` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | `Pen`'in rengini gösteren bir `Color` yapısı. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


Belirtilen `Color` ve `Pen.Width` özellikleriyle `Pen` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | `Pen`'in rengini gösteren bir `Color` yapısı. |
| genişlik | float | Bu `Pen`'in genişliğini gösteren bir değer. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


Belirtilen `Brush` ile `Pen` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Bu `Pen`'in doldurma özelliklerini belirleyen bir `Brush`. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


Belirtilen `Brush` ve `Pen.Width` ile `Pen` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Bu `Pen`'in özelliklerini belirleyen bir `Brush`. |
| genişlik | float | Yeni `Pen`'in genişliği. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Bu `Pen`in genişliğini, çizim için kullanılan Graphics nesnesinin birimlerinde alır.

**Returns:**
float - Bu `Pen`'in genişliği.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Bu `Pen`in genişliğini, çizim için kullanılan Graphics nesnesinin birimlerinde ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Pen`'in genişliği. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılan kapak stilini alır.

**Returns:**
int - Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılan uç stilini temsil eden `LineCap` değerlerinden biri.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılan kapak stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılan uç stilini temsil eden `LineCap` değerlerinden biri. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Bu `Pen` ile çizilen çizgilerin sonunda kullanılan kapak stilini alır.

**Returns:**
int - Bu `Pen` ile çizilen çizgilerin sonunda kullanılan uç stilini temsil eden `LineCap` değerlerinden biri.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Bu `Pen` ile çizilen çizgilerin sonunda kullanılan kapak stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `Pen` ile çizilen çizgilerin sonunda kullanılan uç stilini temsil eden `LineCap` değerlerinden biri. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Bu `Pen` ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini alır.

**Returns:**
int - Bu `Pen` ile çizilen kesikli çizgileri oluşturan tirelerin başlangıç ve sonunda kullanılan uç stilini temsil eden `DashCap` değerlerinden biri.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Bu `Pen` ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `Pen` ile çizilen kesikli çizgileri oluşturan tirelerin başlangıç ve sonunda kullanılan uç stilini temsil eden `DashCap` değerlerinden biri. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Bu `Pen` ile çizilen iki ardışık çizginin uçları için birleştirme stilini alır.

**Returns:**
int - Bu `Pen` ile çizilen iki ardışık çizginin uçları için birleşim stilini temsil eden bir `LineJoin`.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Bu `Pen` ile çizilen iki ardışık çizginin uçları için birleştirme stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bir `LineJoin`, bu `Pen` ile çizilen iki ardışık çizginin uçlarındaki birleşim stilini temsil eder. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak alır.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Bu `Pen` ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Bir `CustomLineCap`, bu `Pen` ile çizilen çizgilerin başlangıcında kullanılan kapağı temsil eder. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Bu `Pen` ile çizilen çizgilerin sonunda kullanılacak özel bir kapak alır.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Bu `Pen` ile çizilen çizgilerin sonunda kullanılacak özel bir kapak ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Bir `CustomLineCap`, bu `Pen` ile çizilen çizgilerin sonunda kullanılan kapağı temsil eder. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Köşeli bir köşedeki birleştirme kalınlığının sınırını alır.

**Returns:**
float - Keskin köşedeki birleşimin kalınlık sınırı.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Miter köşesindeki birleşmenin kalınlık sınırını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Keskin köşedeki birleşimin kalınlık sınırı. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Bu `Pen` için hizalamayı alır.

**Returns:**
int - Bir `PenAlignment`, bu `Pen` için hizalamayı temsil eder.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Bu `Pen` için hizalamayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bir `PenAlignment`, bu `Pen` için hizalamayı temsil eder. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Bu `Pen` için geometrik dönüşümün bir kopyasını alır.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Bu `Pen` için geometrik dönüşümün bir kopyasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | Bu `Matrix` kopyası, bu `Pen` için geometrik dönüşümü temsil eder. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


Bu `Pen` ile çizilen çizgilerin stilini alır.

**Returns:**
int - Bir `PenType` enum'ı, bu `Pen` ile çizilen çizgilerin stilini belirtir.
### getColor() {#getColor--}
```
public Color getColor()
```


Bu `Pen`'in rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Bu `Pen`'in rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Bir `Color` yapısı, bu `Pen`in rengini temsil eder. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Bu `Pen`'in özelliklerini belirleyen `Brush`'ı alır.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


Bu `Pen`'in özelliklerini belirleyen `Brush`'ı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | Bir `Brush`, bu `Pen`in özelliklerini belirler. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Bu `Pen` ile çizilen kesikli çizgiler için kullanılan stili alır.

**Returns:**
int - Bir `DashStyle`, bu `Pen` ile çizilen kesikli çizgilerde kullanılan stili temsil eder.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Bu `Pen` ile çizilen kesikli çizgiler için kullanılan stili ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bir `DashStyle`, bu `Pen` ile çizilen kesikli çizgilerde kullanılan stili temsil eder. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Bir çizginin başlangıcından kesik desenin başlangıcına olan mesafeyi alır.

**Returns:**
float - Bir çizginin başlangıcından dash deseninin başlangıcına olan mesafe.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Bir çizginin başlangıcından kesik desenin başlangıcına olan mesafeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bir çizginin başlangıcından dash deseninin başlangıcına olan mesafe. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Özel kesik ve boşluklardan oluşan bir dizi alır.

**Returns:**
float[] - Kesikli çizgilerde dönüşümlü çizgi ve boşluk uzunluklarını belirten gerçek sayıların dizisi.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Özel kesik ve boşluklardan oluşan bir dizi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | Kesikli çizgilerde dönüşümlü çizgi ve boşluk uzunluklarını belirten gerçek sayıların dizisi. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Bileşik bir kalemi belirten değerler dizisini alır. Bileşik kalem, paralel çizgiler ve boşluklardan oluşan bileşik bir çizgi çizer.

**Returns:**
float[] - Bileşik dizi olarak gerçek sayıların dizisi. Dizideki öğeler artan sırada olmalı, 0'dan küçük olmamalı ve 1'den büyük olmamalıdır.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Bileşik bir kalemi belirten değerler dizisini ayarlar. Bileşik kalem, paralel çizgiler ve boşluklardan oluşan bileşik bir çizgi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | Bileşik dizi olarak gerçek sayıların dizisi. Dizideki öğeler artan sırada olmalı, 0'dan küçük olmamalı ve 1'den büyük olmamalıdır. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Bu `Pen` ile çizilen çizgilerin sonlandırılmasında kullanılan kapak stilini belirleyen değerleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startCap | int | Bir `LineCap`, bu `Pen` ile çizilen çizgilerin başlangıcında kullanılacak kapak stilini temsil eder. |
| endCap | int | Bir `LineCap`, bu `Pen` ile çizilen çizgilerin sonunda kullanılacak kapak stilini temsil eder. |
| dashCap | int | Bir `LineCap`, bu `Pen` ile çizilen kesikli çizgilerin başlangıcında veya sonunda kullanılacak kapak stilini temsil eder. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Bu `Pen` için geometrik dönüşüm matrisini birim matrisine sıfırlar.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Bu `Pen` için dönüşüm matrisini belirtilen `Matrix` ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Dönüşüm matrisini çarpmak için kullanılan `Matrix` nesnesi. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Bu `Pen` için dönüşüm matrisini belirtilen `Matrix` ile belirtilen sırada çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Dönüşüm matrisini çarpmak için kullanılan `Matrix`. |
| sıra | int | Çarpma işleminin gerçekleştirileceği sıra. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |
| sıra | int | Çevirinin uygulanacağı sıra (ön ekleme veya ekleme). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçekleneceği faktör. |
| sy | float | Dönüşümün y ekseni yönünde ölçekleneceği faktör. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Yerel geometrik dönüşümü belirtilen faktörlerle belirtilen sırada ölçeklendir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçekleneceği faktör. |
| sy | float | Dönüşümün y ekseni yönünde ölçekleneceği faktör. |
| sıra | int | Ölçekleme matrisinin eklenip eklenmeyeceğini belirten bir `MatrixOrder`. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem rotasyonu dönüşüme ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırada döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı. |
| sıra | int | Rotasyon matrisinin eklenip eklenmeyeceğini belirten bir `MatrixOrder`. |

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
int
