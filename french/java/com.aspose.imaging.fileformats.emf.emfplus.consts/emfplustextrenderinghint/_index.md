---
title: "EmfPlusTextRenderingHint"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération TextRenderingHint définit les types d'optimisation du texte et d'anti‑aliasage qui affectent la qualité du rendu du texte."
type: docs
weight: 52
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

L'énumération TextRenderingHint définit les types d'optimisation du texte et d'anticrénelage, qui affectent la qualité du rendu du texte.
## Champs

| Champ | Description |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Spécifie que chaque caractère de texte DOIT être dessiné en utilisant les paramètres de lissage des polices configurés sur le système d'exploitation. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe anti‑aliasé avec lissage. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Spécifie que chaque caractère de texte est dessiné en utilisant son bitmap de glyphe anti‑aliasé sans optimisation. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe ClearType avec lissage. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Spécifie que chaque caractère de texte DOIT être dessiné en utilisant les paramètres de lissage des polices configurés sur le système d'exploitation.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe. Le lissage PEUT être utilisé pour améliorer l'apparence des tiges et de la courbure des glyphes.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe. Le lissage n'est pas utilisé.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe anti‑aliasé avec lissage. Le rendu est de haute qualité grâce à l'anti‑aliasage, mais à un coût de performance plus élevé.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Spécifie que chaque caractère de texte est dessiné en utilisant son bitmap de glyphe anti‑aliasé sans optimisation. Une meilleure qualité résulte de l'anti‑aliasage, mais les différences de largeur des tiges PEUVENT être perceptibles car l'optimisation est désactivée.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Spécifie que chaque caractère de texte DOIT être dessiné en utilisant son bitmap de glyphe ClearType avec lissage. Il s'agit du réglage d'optimisation du texte de la plus haute qualité, utilisé pour tirer parti des fonctionnalités de police ClearType.

