---
title: "WmfCompression"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Compression Sıralaması, bir bitmap görüntüsü için sıkıştırma türünü belirtir."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

Compression Sıralaması, bir bitmap görüntüsü için sıkıştırma türünü belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BI_RGB](#BI-RGB) | Bitmap, sıkıştırılmamış kırmızı yeşil mavi (RGB) formatındadır; sıkıştırılmaz ve renk maskeleri kullanmaz. |
| [BI_RLE8](#BI-RLE8) | 8 bit/piksel bitmapler için koşu uzunluğu kodlaması (RLE) sıkıştırması kullanan bir RGB formatı. |
| [BI_RLE4](#BI-RLE4) | 4 bit/piksel bitmapler için RLE sıkıştırması kullanan bir RGB formatı. |
| [BI_BITFIELDS](#BI-BITFIELDS) | Bitmap sıkıştırılmamıştır ve renk tablosu, her pikselin kırmızı, yeşil ve mavi bileşenlerini sırasıyla belirten üç DWORD renk maskesinden oluşur. |
| [BI_JPEG](#BI-JPEG) | Görüntü, [JFIF] içinde belirtildiği gibi bir JPEG görüntüsüdür. |
| [BI_PNG](#BI-PNG) | Görüntü, [RFC2083] içinde belirtildiği gibi bir PNG görüntüsüdür. |
| [BI_CMYK](#BI-CMYK) | Görüntü sıkıştırılmamış bir CMYK formatıdır. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | 8 bit/piksel bitmapler için RLE sıkıştırması kullanan bir CMYK formatı. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | 4 bit/piksel bitmapler için RLE sıkıştırması kullanan bir CMYK formatı. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


Bitmap, sıkıştırılmamış kırmızı yeşil mavi (RGB) formatındadır; sıkıştırılmaz ve renk maskeleri kullanmaz.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


8 bit/piksel bitmapler için koşu uzunluğu kodlaması (RLE) sıkıştırması kullanan bir RGB formatı. Sıkıştırma, bir sayım baytı ve ardından bir renk indeksi içeren bir bayttan oluşan 2 baytlık bir format kullanır.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


4 bit/piksel bitmapler için RLE sıkıştırması kullanan bir RGB formatı. Sıkıştırma, bir sayım baytı ve ardından iki kelime uzunluğunda renk indeksi içeren 2 baytlık bir format kullanır.

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


Bitmap sıkıştırılmamıştır ve renk tablosu, her pikselin kırmızı, yeşil ve mavi bileşenlerini sırasıyla belirten üç DWORD renk maskesinden oluşur. Bu, 16 ve 32 bit/piksel bitmaplerle kullanıldığında geçerlidir.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


Görüntü, [JFIF] içinde belirtildiği gibi bir JPEG görüntüsüdür. Bu değer yalnızca JPEG geçişi gibi belirli bitmap işlemlerinde kullanılmalıdır. Uygulama, JPEG geçişi desteğini sorgulamalıdır, çünkü tüm cihazlar JPEG geçişini desteklemez. RGB olmayan bitmaplerin kullanılması, metafilin diğer cihazlara taşınabilirliğini sınırlayabilir. Örneğin, görüntü aygıt bağlamları genellikle bu geçişi desteklemez.

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


Görüntü, [RFC2083] içinde belirtildiği gibi bir PNG görüntüsüdür. Bu değer yalnızca JPEG/PNG geçişi gibi belirli bitmap işlemlerinde kullanılmalıdır. Uygulama, geçiş desteğini sorgulamalıdır, çünkü tüm cihazlar JPEG/PNG geçişini desteklemez. RGB olmayan bitmaplerin kullanılması, metafilin diğer cihazlara taşınabilirliğini sınırlayabilir. Örneğin, görüntü aygıt bağlamları genellikle bu geçişi desteklemez.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


Görüntü sıkıştırılmamış bir CMYK formatıdır.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


8 bit/piksel bitmapler için RLE sıkıştırması kullanan bir CMYK formatı. Sıkıştırma, bir sayım baytı ve ardından bir renk indeksi içeren bir bayttan oluşan 2 baytlık bir format kullanır.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


4 bit/piksel bitmapler için RLE sıkıştırması kullanan bir CMYK formatı. Sıkıştırma, bir sayım baytı ve ardından iki kelime uzunluğunda renk indeksi içeren 2 baytlık bir format kullanır.

