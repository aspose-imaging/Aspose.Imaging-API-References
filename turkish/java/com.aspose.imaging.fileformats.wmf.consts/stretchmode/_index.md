---
title: "StretchMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu Sınıflama, sistemin bir bitmap'in satır veya sütunlarını mevcut piksellerle nasıl birleştirdiğini tanımlayan bitmap germe modunu belirtir."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

Bu [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) Sınıflama, sistemin bir bitmap'in satır veya sütunlarını mevcut piksellerle nasıl birleştirdiğini tanımlayan bitmap germe modunu belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Elimin edilen ve mevcut piksellerin renk değerlerini kullanarak Boolean AND işlemi gerçekleştirir. |
| [WhiteOnBlack](#WhiteOnBlack) | Elimin edilen ve mevcut piksellerin renk değerlerini kullanarak Boolean OR işlemi gerçekleştirir. |
| [ColorOnColor](#ColorOnColor) | Piksel'leri siler. |
| [HalfTone](#HalfTone) | Kaynak dikdörtgenden pikselleri hedef dikdörtgendeki piksel bloklarına eşler. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Elimin edilen ve mevcut piksellerin renk değerlerini kullanarak Boolean AND işlemi gerçekleştirir. Bitmap tek renkli bir bitmap ise, bu mod beyaz piksellerin pahasına siyah pikselleri korur.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Elimin edilen ve mevcut piksellerin renk değerlerini kullanarak Boolean OR işlemi gerçekleştirir. Bitmap tek renkli bir bitmap ise, bu mod siyah piksellerin pahasına beyaz pikselleri korur.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Piksel'leri siler. Bu mod, bilgilerini korumaya çalışmadan tüm elimin edilen piksel satırlarını siler.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Kaynak dikdörtgenden pikselleri hedef dikdörtgendeki piksel bloklarına eşler. Hedef piksel bloğunun ortalama rengi, kaynak piksellerin rengini yaklaşık olarak yansıtır.

