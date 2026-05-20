---
title: "EmfPlusBrushDataFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I flag BrushData specificano le proprietà dei pennelli grafici, inclusa la presenza di campi dati opzionali."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

I flag BrushData specificano le proprietà dei pennelli grafici, inclusa la presenza di campi dati opzionali. Questi flag possono essere combinati per specificare più opzioni.
## Campi

| Campo | Descrizione |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | Questo flag ha significato negli oggetti [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (sezione 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | Questo flag è significativo negli oggetti [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (sezione 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) e negli oggetti `EmfPlusTextureBrushData` (sezione 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData. |
| [BrushDataFocusScales](#BrushDataFocusScales) | Questo flag è significativo negli oggetti EmfPlusPathGradientBrushData. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData e EmfPlusTextureBrushData. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | Questo flag è significativo negli oggetti EmfPlusTextureBrushData. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


Questo flag è significativo negli oggetti [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (sezione 2.2.2.29). Se impostato, un oggetto [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) (sezione 2.2.2.6) DEVE essere specificato nel campo BoundaryData dell'oggetto dati del pennello. Se non impostato, un oggetto [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) (sezione 2.2.2.7) DEVE essere specificato nel campo BoundaryData dell'oggetto dati del pennello.

--------------------

I pennelli grafici sono specificati dagli oggetti [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush)

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


Questo flag è significativo negli oggetti [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (sezione 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) e negli oggetti `EmfPlusTextureBrushData` (sezione 2.2.2.45). Se impostato, una matrice di trasformazione 2x3 dallo spazio mondo allo spazio dispositivo DEVE essere specificata nel campo OptionalData dell'oggetto dati del pennello.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData. Se impostato, un oggetto [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) (sezione 2.2.2.4) DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData. Se impostato, un oggetto [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) (sezione 2.2.2.5) che specifica un modello di fusione lungo un gradiente orizzontale DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData. Se impostato, un oggetto EmfPlusBlendFactors che specifica un modello di fusione lungo un gradiente verticale DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


Questo flag è significativo negli oggetti EmfPlusPathGradientBrushData. Se impostato, un[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) (sezione 2.2.2.18) DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData e EmfPlusTextureBrushData. Se impostato, il pennello DEVE già essere corretto gamma; cioè, la luminosità e l'intensità di uscita sono state corrette per corrispondere all'immagine di input.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


Questo flag è significativo negli oggetti EmfPlusTextureBrushData. Se impostato, una trasformazione dallo spazio mondo allo spazio dispositivo NON DEVE essere applicata al pennello texture.

