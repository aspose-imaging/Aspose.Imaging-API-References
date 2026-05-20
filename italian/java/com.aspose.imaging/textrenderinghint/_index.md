---
title: "TextRenderingHint"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica la qualità del rendering del testo."
type: docs
weight: 115
url: /it/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Specifica la qualità del rendering del testo.
## Campi

| Campo | Descrizione |
| --- | --- |
| [SystemDefault](#SystemDefault) | Ogni carattere è disegnato usando il suo bitmap di glifo, con il suggerimento di rendering predefinito del sistema. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Ogni carattere è disegnato usando il suo bitmap di glifo. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Ogni carattere è disegnato usando il suo bitmap di glifo. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato con hinting. |
| [AntiAlias](#AntiAlias) | Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato senza hinting. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Ogni carattere è disegnato usando il suo bitmap di glifo ClearType con hinting. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Ogni carattere è disegnato usando il suo bitmap di glifo. Il testo sarà disegnato usando le impostazioni di smussatura dei caratteri che l'utente ha selezionato per il sistema.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Ogni carattere è disegnato usando il suo bitmap di glifo. L'hinting è usato per migliorare l'aspetto dei caratteri su steli e curvature.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Ogni carattere è disegnato usando il suo bitmap di glifo. L'hinting non è usato.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato con hinting. Qualità molto migliore grazie all'antialiasing, ma a un costo di prestazioni più elevato.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato senza hinting. Qualità migliore grazie all'antialiasing. Le differenze di larghezza degli steli possono essere evidenti perché l'hinting è disattivato.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Ogni carattere è disegnato usando il suo bitmap di glifo ClearType con hinting. L'impostazione di qualità più alta. Usato per sfruttare le funzionalità dei font ClearType.

