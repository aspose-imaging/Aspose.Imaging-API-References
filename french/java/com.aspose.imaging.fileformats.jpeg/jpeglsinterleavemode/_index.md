---
title: "JpegLsInterleaveMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit le mode d'entrelacement pour les données de pixels couleur multi-composants."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Définit le mode d'entrelacement pour les données de pixels multi-composants (couleur).
## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Les données sont encodées et stockées composant par composant : RRRGGGBBB. |
| [Line](#Line) | Le mode d'entrelacement est par ligne. |
| [Sample](#Sample) | Les données sont encodées et stockées par échantillon. |
### None {#None}
```
public static final int None
```


Les données sont encodées et stockées composant par composant : RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


Le mode d'entrelacement est par ligne. Une ligne complète de chaque composant est encodée avant de passer à la ligne suivante.

### Sample {#Sample}
```
public static final int Sample
```


Les données sont encodées et stockées par échantillon. Pour les images couleur, c'est le format tel que RGBRGBRGB.

