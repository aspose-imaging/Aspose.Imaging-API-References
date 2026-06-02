---
title: "EmfPlusTextRenderingHint"
second_title: "Aspose.Imaging för Java API-referens"
description: "TextRenderingHint‑enumerationen definierar typer av texthintning och antialiasing som påverkar kvaliteten på textrendering."
type: docs
weight: 52
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

TextRenderingHint‑enumerationen definierar typer av texthintning och kantutjämning, vilket påverkar kvaliteten på textrenderingen.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Anger att varje tecken SHOULD ritas med de teckensnittsutjämningsinställningar som har konfigurerats i operativsystemet. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Anger att varje tecken SHOULD ritas med sin glyf-bitmap. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Anger att varje tecken SHOULD ritas med sin glyf-bitmap. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Anger att varje tecken SHOULD ritas med sin antialiasade glyf-bitmap med utjämning. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Anger att varje tecken ritas med sin antialiasade glyf-bitmap utan hintning. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Anger att varje tecken SHOULD ritas med sin ClearType-glyf-bitmap med utjämning. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Anger att varje tecken SHOULD ritas med de teckensnittsutjämningsinställningar som har konfigurerats i operativsystemet.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Anger att varje tecken SHOULD ritas med sin glyf-bitmap. Utjämning MAY användas för att förbättra utseendet på teckenstammar och kurvatur.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Anger att varje tecken SHOULD ritas med sin glyf-bitmap. Utjämning används inte.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Anger att varje tecken SHOULD ritas med sin antialiasade glyf-bitmap med utjämning. Renderingen är av hög kvalitet på grund av antialiasing, men med högre prestandakostnad.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Anger att varje tecken ritas med sin antialiasade glyf-bitmap utan hintning. Bättre kvalitet uppnås genom antialiasing, men skillnader i stambredd MAY märkas eftersom hintning är avstängd.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Anger att varje tecken SHOULD ritas med sin ClearType-glyf-bitmap med utjämning. Detta är den högsta kvalitetens texthintningsinställning, som används för att utnyttja ClearType-teckensnittsfunktioner.

