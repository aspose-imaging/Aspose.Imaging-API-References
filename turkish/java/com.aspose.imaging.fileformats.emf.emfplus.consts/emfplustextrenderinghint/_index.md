---
title: "EmfPlusTextRenderingHint"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TextRenderingHint sayımı, metin ipucu ve anti-aliasing türlerini tanımlar ve bu, metin renderleme kalitesini etkiler."
type: docs
weight: 52
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

TextRenderingHint sayımı, metin ipucu ve anti-aliasing türlerini tanımlar; bu, metin render kalitesini etkiler.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Her metin karakterinin, işletim sisteminde yapılandırılmış olan font-yumuşatma ayarları kullanılarak SHOULD çizilmesi gerektiğini belirtir. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Her metin karakterinin, glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Her metin karakterinin, glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Her metin karakterinin, anti-aliasing uygulanmış ve yumuşatma içeren glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Her metin karakterinin, ipucu olmadan anti-aliasing uygulanmış glif bitmap'i kullanılarak çizildiğini belirtir. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Her metin karakterinin, yumuşatma içeren ClearType glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Her metin karakterinin, işletim sisteminde yapılandırılmış olan font-yumuşatma ayarları kullanılarak SHOULD çizilmesi gerektiğini belirtir.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Her metin karakterinin, glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. Yumuşatma, karakter glif saplarının ve eğriliğinin görünümünü iyileştirmek için MAY kullanılabilir.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Her metin karakterinin, glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. Yumuşatma kullanılmaz.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Her metin karakterinin, yumuşatma içeren anti-aliasing uygulanmış glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. Renderleme, anti-aliasing sayesinde yüksek kalitededir, ancak daha yüksek bir performans maliyeti vardır.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Her metin karakterinin, ipucu olmadan anti-aliasing uygulanmış glif bitmap'i kullanılarak çizildiğini belirtir. Anti-aliasing daha iyi kalite sağlar, ancak ipucu kapalı olduğundan sap genişliği farkları MAY fark edilebilir.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Her metin karakterinin, yumuşatma içeren ClearType glif bitmap'i kullanılarak SHOULD çizilmesi gerektiğini belirtir. Bu, ClearType font özelliklerinden yararlanmak için kullanılan en yüksek kalite metin ipucu ayarıdır.

