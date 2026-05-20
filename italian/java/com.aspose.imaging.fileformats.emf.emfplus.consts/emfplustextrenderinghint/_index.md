---
title: "EmfPlusTextRenderingHint"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione TextRenderingHint definisce i tipi di hinting del testo e anti-aliasing che influenzano la qualità del rendering del testo."
type: docs
weight: 52
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

L'enumerazione TextRenderingHint definisce i tipi di hinting del testo e anti-aliasing, che influenzano la qualità del rendering del testo.
## Campi

| Campo | Descrizione |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando le impostazioni di smoothing dei font configurate nel sistema operativo. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo anti-aliasato con smoothing. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Specifica che ogni carattere di testo è disegnato utilizzando il suo bitmap di glifo anti-aliasato senza hinting. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo ClearType con smoothing. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando le impostazioni di smoothing dei font configurate nel sistema operativo.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo. Lo smoothing MAY essere usato per migliorare l'aspetto dei tratti e della curvatura dei glifi dei caratteri.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo. Lo smoothing non è usato.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo anti-aliasato con smoothing. Il rendering è di alta qualità grazie all'anti-aliasing, ma comporta un costo di prestazioni più elevato.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Specifica che ogni carattere di testo è disegnato utilizzando il suo bitmap di glifo anti-aliasato senza hinting. Una migliore qualità deriva dall'anti-aliasing, ma le differenze di larghezza dei tratti MAY essere evidenti perché l'hinting è disattivato.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Specifica che ogni carattere di testo SHOULD essere disegnato utilizzando il suo bitmap di glifo ClearType con smoothing. Questa è l'impostazione di hinting del testo di massima qualità, utilizzata per sfruttare le funzionalità dei font ClearType.

