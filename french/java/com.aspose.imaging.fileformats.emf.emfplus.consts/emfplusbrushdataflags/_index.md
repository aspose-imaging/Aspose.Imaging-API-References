---
title: "EmfPlusBrushDataFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les indicateurs BrushData spécifient les propriétés des pinceaux graphiques, y compris la présence de champs de données optionnels."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

Les indicateurs BrushData spécifient les propriétés des pinceaux graphiques, y compris la présence de champs de données optionnels. Ces indicateurs peuvent être combinés pour spécifier plusieurs options.
## Champs

| Champ | Description |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | Ce drapeau a du sens dans les objets [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (section 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | Ce drapeau est significatif dans les objets [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (section 2.2.2.24), les objets [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) et les objets `EmfPlusTextureBrushData` (section 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData. |
| [BrushDataFocusScales](#BrushDataFocusScales) | Ce drapeau est significatif dans les objets EmfPlusPathGradientBrushData. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData et EmfPlusTextureBrushData. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | Ce drapeau est significatif dans les objets EmfPlusTextureBrushData. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


Ce drapeau est significatif dans les objets [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (section 2.2.2.29). Si le drapeau est défini, un objet [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) (section 2.2.2.6) DOIT être spécifié dans le champ BoundaryData de l'objet de données du pinceau. Si le drapeau n'est pas défini, un objet [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) (section 2.2.2.7) DOIT être spécifié dans le champ BoundaryData de l'objet de données du pinceau.

--------------------

Les pinceaux graphiques sont spécifiés par les objets [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) objects

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


Ce drapeau est significatif dans les objets [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (section 2.2.2.24), les objets [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) et les objets `EmfPlusTextureBrushData` (section 2.2.2.45). Si le drapeau est défini, une matrice de transformation 2x3 de l'espace monde vers l'espace dispositif DOIT être spécifiée dans le champ OptionalData de l'objet de données du pinceau.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData. Si le drapeau est défini, un objet [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) (section 2.2.2.4) DOIT être spécifié dans le champ OptionalData de l'objet de données du pinceau.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData. Si le drapeau est défini, un objet [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) (section 2.2.2.5) qui spécifie un motif de mélange le long d'un dégradé horizontal DOIT être spécifié dans le champ OptionalData de l'objet de données du pinceau.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData. Si le drapeau est défini, un objet EmfPlusBlendFactors qui spécifie un motif de mélange le long d'un dégradé vertical DOIT être spécifié dans le champ OptionalData de l'objet de données du pinceau.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


Ce drapeau est significatif dans les objets EmfPlusPathGradientBrushData. Si le drapeau est défini, un objet [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) (section 2.2.2.18) DOIT être spécifié dans le champ OptionalData de l'objet de données du pinceau.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData et EmfPlusTextureBrushData. Si le drapeau est défini, le pinceau DOIT déjà être corrigé gamma ; c'est‑à‑dire que la luminosité et l'intensité de sortie ont été corrigées pour correspondre à l'image d'entrée.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


Ce drapeau est significatif dans les objets EmfPlusTextureBrushData. Si le drapeau est défini, une transformation de l'espace monde vers l'espace dispositif NE DOIT PAS être appliquée au pinceau de texture.

