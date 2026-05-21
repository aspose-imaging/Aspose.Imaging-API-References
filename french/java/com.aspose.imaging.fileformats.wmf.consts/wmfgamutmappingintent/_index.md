---
title: "WmfGamutMappingIntent"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération GamutMappingIntent spécifie la relation entre les couleurs logiques et physiques."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

L'énumération GamutMappingIntent spécifie la relation entre les couleurs logiques et physiques.
## Champs

| Champ | Description |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Spécifie que le point blanc DOIT être maintenu. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Spécifie que la saturation DOIT être maintenue. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Spécifie qu'une correspondance colorimétrique DOIT être maintenue. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Spécifie que le contraste DOIT être maintenu. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Spécifie que le point blanc DOIT être maintenu. Typiquement utilisé lorsque les couleurs logiques DOIVENT être associées à leur couleur physique la plus proche dans la gamme de couleurs de destination. Intention : Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Spécifie que la saturation DOIT être maintenue. Typiquement utilisé pour les graphiques d'entreprise et autres situations où le tramage n'est pas requis. Intention : Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Spécifie qu'une correspondance colorimétrique DOIT être maintenue. Typiquement utilisé pour les conceptions graphiques et les couleurs nommées. Intention : Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Spécifie que le contraste DOIT être maintenu. Typiquement utilisé pour les photographies et les images naturelles. Intention : Picture ICC name: Perceptual

