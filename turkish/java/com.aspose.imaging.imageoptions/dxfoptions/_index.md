---
title: "DxfOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Drawing Interchange Format DXF vektör görüntüsü oluşturma API'si, AutoCAD çizim dosyalarını hassasiyet ve esneklikle oluşturmak için özelleştirilmiş çözümler sunar."
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

Drawing Interchange Format (DXF) vektör görüntüsü oluşturma API'si, AutoCAD çizim dosyalarını hassasiyet ve esneklikle oluşturmak için özelleştirilmiş çözümler sunar. Özellikle metin satırları ve Bezier eğrileriyle çalışmak için tasarlanmış olup, geliştiriciler bu öğeleri verimli bir şekilde manipüle edebilir, Bezier noktalarını sayabilir ve eğrileri çokgen çizgilere dönüştürerek sorunsuz bir dışa aktarma sağlayabilir; bu sayede DXF vektör görüntülerinde uyumluluk ve doğruluk garantilenir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Coping yapıcı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | Bezier eğrilerini çokgen çizgilere dönüştürürken oluşturulacak nokta sayısı, minimum 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | Bezier eğrilerini çokgen çizgilere dönüştürürken oluşturulacak nokta sayısı, minimum 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | \#textAsLines `true` olarak ayarlandığında çalışır. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | \#textAsLines `true` olarak ayarlandığında çalışır. |
| [getTextAsLines()](#getTextAsLines--) | Metnin çokgen çizgilerden oluşan konturlar (varsayılan) ya da düzenlenebilir Autocad TEXT varlıkları olarak dışa aktarılması. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Metnin çokgen çizgilerden oluşan konturlar (varsayılan) ya da düzenlenebilir Autocad TEXT varlıkları olarak dışa aktarılması. |

## Example: This example demonstrates export to Dxf format

``` java

//Image örneği oluşturun ve disk konumundaki mevcut bir görüntü dosyasıyla başlatın.
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Coping yapıcı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | Kopyalama için kaynak seçenekleri |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


Bezier eğrilerini çokgen çizgilere dönüştürürken oluşturulacak nokta sayısı, minimum 4. (/) ve (/) her ikisi de `true` olarak ayarlandığında kullanılır.

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


Bezier eğrilerini çokgen çizgilere dönüştürürken oluşturulacak nokta sayısı, minimum 4. (/) ve (/) her ikisi de `true` olarak ayarlandığında kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


\#textAsLines `true` olarak ayarlandığında çalışır. Metin konturlarındaki Bezier eğrilerini çok noktalı çokgen çizgilere dönüştürülüp dönüştürülmeyeceği.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


\#textAsLines `true` olarak ayarlandığında çalışır. Metin konturlarındaki Bezier eğrilerini çok noktalı çokgen çizgilere dönüştürülüp dönüştürülmeyeceği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Metnin çokgen çizgilerden oluşan konturlar (varsayılan) ya da düzenlenebilir Autocad TEXT varlıkları olarak dışa aktarılıp aktarılmayacağı. Bu seçenek ayarlanırsa

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Metnin çokgen çizgilerden oluşan konturlar (varsayılan) ya da düzenlenebilir Autocad TEXT varlıkları olarak dışa aktarılıp aktarılmayacağı. Bu seçenek ayarlanırsa

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

