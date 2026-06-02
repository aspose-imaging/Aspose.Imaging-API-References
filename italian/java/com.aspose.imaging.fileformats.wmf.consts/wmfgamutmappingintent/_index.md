---
title: "WmfGamutMappingIntent"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione GamutMappingIntent specifica la relazione tra i colori logici e fisici."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

L'enumerazione GamutMappingIntent specifica la relazione tra i colori logici e fisici.
## Campi

| Campo | Descrizione |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Specificare che il punto bianco DEVE essere mantenuto. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Specifica che la saturazione DEVE essere mantenuta. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Specifica che una corrispondenza colorimetrica DEVE essere mantenuta. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Specifica che il contrasto DEVE essere mantenuto. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Specifica che il punto di bianco DEVE essere mantenuto. Tipicamente usato quando i colori logici DEVONO essere abbinati al loro colore fisico più vicino nello spazio colore di destinazione. Intento: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Specifica che la saturazione DEVE essere mantenuta. Tipicamente usato per grafici aziendali e altre situazioni in cui la dithering non è richiesta. Intento: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Specifica che una corrispondenza colorimetrica DEVE essere mantenuta. Tipicamente usato per progetti grafici e colori denominati. Intento: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Specifica che il contrasto DEVE essere mantenuto. Tipicamente usato per fotografie e immagini naturali. Intento: Picture ICC name: Perceptual

