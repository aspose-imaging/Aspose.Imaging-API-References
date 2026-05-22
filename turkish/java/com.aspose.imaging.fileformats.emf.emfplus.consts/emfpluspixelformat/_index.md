---
title: "EmfPlusPixelFormat"
second_title: "Aspose.Imaging for Java API Referansı"
description: "PixelFormat sayımı, EMF bitmap'lerinde desteklenen piksel formatlarını tanımlar."
type: docs
weight: 43
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

PixelFormat sayımı, EMF+ bitmap'lerde desteklenen piksel formatlarını tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | Biçim belirtilmemiştir. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | Biçim monokromdur ve bir renk paleti arama tablosu kullanılır. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | Biçim 16 renkli ve bir renk paleti arama tablosu kullanılır. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | Biçim 256 renkli ve bir renk paleti arama tablosu kullanılır. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | Biçim piksel başına 16 bitten oluşur, gri tonlamalıdır. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | Biçim piksel başına 16 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 5 bit kullanılır. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | Biçim piksel başına 16 bitten oluşur; kırmızı bileşen için 5 bit, yeşil bileşen için 6 bit ve mavi bileşen için 5 bit kullanılır. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | Biçim piksel başına 16 bitten oluşur; alfa bileşeni için 1 bit ve kırmızı, yeşil ve mavi bileşenler için her biri 5 bit kullanılır. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | Biçim piksel başına 24 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | Biçim piksel başına 32 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | Biçim piksel başına 32 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | Biçim piksel başına 32 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | Biçim piksel başına 48 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 16 bit kullanılır. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | Biçim piksel başına 64 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 16 bit kullanılır. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | Biçim piksel başına 64 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 16 bit kullanılır. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


Biçim belirtilmemiştir.

--------------------

Piksel formatları, [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap) nesneleri tarafından belirtilir. Aşağıdaki gibi kodlanırlar: - Bits 0-7: Sıfırdan başlayan piksel formatı sabitlerinin numaralandırması. - Bits 8-15: Piksel başına toplam bit sayısı. - Bit 16: Ayarlanmışsa, renk değeri bir palete indekslenir. - Bit 17: Ayarlanmışsa, renk değeri GDI tarafından desteklenen bir biçimdedir. - Bit 18: Ayarlanmışsa, renk değerinin alfa bileşeni vardır. - Bit 19: Ayarlanmışsa, renk değerinin önceden çarpılmış alfa bileşeni vardır. - Bit 20: Ayarlanmışsa, kanal başına 16 bit genişletilmiş renkler desteklenir. - Bits 21-31: Rezerv.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


Biçim monokromdur ve bir renk paleti arama tablosu kullanılır.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


Biçim 16 renkli ve bir renk paleti arama tablosu kullanılır.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


Biçim 256 renkli ve bir renk paleti arama tablosu kullanılır.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


Biçim piksel başına 16 bitten oluşur, gri tonlamalıdır.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


Biçim piksel başına 16 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 5 bit kullanılır. Kalan bit kullanılmaz.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


Biçim piksel başına 16 bitten oluşur; kırmızı bileşen için 5 bit, yeşil bileşen için 6 bit ve mavi bileşen için 5 bit kullanılır.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


Biçim piksel başına 16 bitten oluşur; alfa bileşeni için 1 bit ve kırmızı, yeşil ve mavi bileşenler için her biri 5 bit kullanılır.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


Biçim piksel başına 24 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


Biçim piksel başına 32 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır. Kalan 8 bit kullanılmaz.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


Biçim piksel başına 32 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


Biçim piksel başına 32 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 8 bit kullanılır. Kırmızı, yeşil ve mavi bileşenler alfa bileşenine göre önceden çarpılmıştır.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


Biçim piksel başına 48 bitten oluşur; kırmızı, yeşil ve mavi bileşenler için her biri 16 bit kullanılır.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


Biçim piksel başına 64 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 16 bit kullanılır.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


Biçim piksel başına 64 bitten oluşur; alfa, kırmızı, yeşil ve mavi bileşenler için her biri 16 bit kullanılır. Kırmızı, yeşil ve mavi bileşenler alfa bileşenine göre önceden çarpılmıştır.

