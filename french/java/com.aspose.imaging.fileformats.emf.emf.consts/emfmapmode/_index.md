---
title: "EmfMapMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération MapMode est utilisée pour définir l'unité de mesure permettant de transformer les unités d'espace de page en unités d'espace dispositif et pour définir l'orientation des axes de dessin."
type: docs
weight: 30
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

L'énumération MapMode est utilisée pour définir l'unité de mesure permettant de transformer les unités d'espace de page en unités d'espace dispositif et pour définir l'orientation des axes de dessin.
## Champs

| Champ | Description |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | Chaque unité logique est mappée à un pixel d'appareil. |
| [MM_LOMETRIC](#MM-LOMETRIC) | Chaque unité logique est mappée à 0,1 millimètre. |
| [MM_HIMETRIC](#MM-HIMETRIC) | Chaque unité logique est mappée à 0,01 millimètre. |
| [MM_LOENGLISH](#MM-LOENGLISH) | Chaque unité logique est mappée à 0,01 pouce. |
| [MM_HIENGLISH](#MM-HIENGLISH) | Chaque unité logique est mappée à 0,001 pouce. |
| [MM_TWIPS](#MM-TWIPS) | Chaque unité logique est mappée à un vingtième du point d'imprimante (1/1440 pouce, également appelé "twip"). |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | Les unités logiques sont mappées à des unités arbitraires avec des axes à échelle égale; c’est‑à‑dire, une unité le long de l’axe x est égale à une unité le long de l’axe y. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | Les unités logiques sont mappées à des unités arbitraires avec des axes à échelle arbitraire. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


Chaque unité logique est mappée à un pixel d'appareil. Le x positif est vers la droite; le y positif est vers le bas.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


Chaque unité logique est mappée à 0,1 millimètre. Le x positif est vers la droite; le y positif est vers le haut.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


Chaque unité logique est mappée à 0,01 millimètre. Le x positif est vers la droite; le y positif est vers le haut.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


Chaque unité logique est mappée à 0,01 pouce. Le x positif est vers la droite; le y positif est vers le haut

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


Chaque unité logique est mappée à 0,001 pouce. Le x positif est vers la droite; le y positif est vers le haut.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


Chaque unité logique est mappée à un vingtième du point d'imprimante (1/1440 pouce, également appelé "twip"). Le x positif est vers la droite; le y positif est vers le haut.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


Les unités logiques sont mappées à des unités arbitraires avec des axes à échelle égale; c’est‑à‑dire, une unité le long de l’axe x est égale à une unité le long de l’axe y. Les enregistrements EMR\_SETWINDOWEXTEX et EMR\_SETVIEWPORTEXTEX DOIVENT être utilisés pour spécifier les unités et l’orientation des axes. Des ajustements DOIVENT être effectués si nécessaire pour garantir que les unités x et y conservent la même taille. Par exemple, lorsque l’étendue de la fenêtre est définie, le viewport DOIT être ajusté pour maintenir les unités isotropes.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


Les unités logiques sont mappées à des unités arbitraires avec des axes à échelle arbitraire. Les enregistrements EMR\_SETWINDOWEXTEX et EMR\_SETVIEWPORTEXTEX DOIVENT être utilisés pour spécifier les unités, l’orientation et le redimensionnement.

