---
title: "WmfGamutMappingIntent"
second_title: "Aspose.Imaging for Java API Referansı"
description: "GamutMappingIntent Sıralaması, mantıksal ve fiziksel renkler arasındaki ilişkiyi belirtir."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

GamutMappingIntent Sıralaması, mantıksal ve fiziksel renkler arasındaki ilişkiyi belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Beyaz noktasının korunması GEREKİR. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Doygunluğun SHOULD korunması gerektiğini belirtir. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Renk ölçüm eşleşmesinin SHOULD korunması gerektiğini belirtir. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Kontrastın SHOULD korunması gerektiğini belirtir. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Beyaz noktasının SHOULD korunması gerektiğini belirtir. Genellikle mantıksal renklerin MUST hedef renk gamındaki en yakın fiziksel renkle eşleştirilmesi gerektiğinde kullanılır. Amaç: Eşleştirme ICC adı: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Doygunluğun SHOULD korunması gerektiğini belirtir. Genellikle iş grafikleri ve benzeri, dithering'in gerekmediği durumlarda kullanılır. Amaç: Grafik ICC adı: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Renk ölçüm eşleşmesinin SHOULD korunması gerektiğini belirtir. Genellikle grafik tasarımları ve adlandırılmış renkler için kullanılır. Amaç: Kanıt ICC adı: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Kontrastın SHOULD korunması gerektiğini belirtir. Genellikle fotoğraflar ve doğal görüntüler için kullanılır. Amaç: Resim ICC adı: Perceptual

