---
title: "TextRenderingHint"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Metin renderleme kalitesini belirtir."
type: docs
weight: 115
url: /tr/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Metin renderleme kalitesini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [SystemDefault](#SystemDefault) | Her karakter, sistemin varsayılan render ipucu ile glif bitmap'i kullanılarak çizilir. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Her karakter, glif bitmap'i kullanılarak çizilir. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Her karakter, glif bitmap'i kullanılarak çizilir. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Her karakter, ipucu ile antialias'li glif bitmap'i kullanılarak çizilir. |
| [AntiAlias](#AntiAlias) | Her karakter, ipucu olmadan antialias'li glif bitmap'i kullanılarak çizilir. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Her karakter, ipucu ile glif ClearType bitmap'i kullanılarak çizilir. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Her karakter, sistemin varsayılan render ipucu ile glif bitmap'i kullanılarak çizilir. Metin, kullanıcının sistem için seçtiği font yumuşatma ayarlarıyla çizilecektir.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Her karakter, glif bitmap'i kullanılarak çizilir. İpucu, karakterlerin gövde ve eğrilik üzerindeki görünümünü iyileştirmek için kullanılır.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Her karakter, glif bitmap'i kullanılarak çizilir. İpucu kullanılmaz.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Her karakter, ipucu ile antialias'li glif bitmap'i kullanılarak çizilir. Antialiasing sayesinde çok daha iyi kalite, ancak daha yüksek performans maliyeti.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Her karakter, ipucu olmadan antialias'li glif bitmap'i kullanılarak çizilir. Antialiasing sayesinde daha iyi kalite. İpucu kapalı olduğundan gövde genişliği farkları fark edilebilir.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Her karakter, ipucu ile glif ClearType bitmap'i kullanılarak çizilir. En yüksek kalite ayarı. ClearType font özelliklerinden yararlanmak için kullanılır.

